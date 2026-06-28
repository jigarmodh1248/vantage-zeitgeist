# VANTAGE – Real-Time Digital Zeitgeist Observatory

A bold, editorial live dashboard that surfaces the top tech stories from [Hacker News](https://news.ycombinator.com/) and uses **Google Gemini AI** to analyse the #1 headline — giving it a one‑word emotional “vibe” and a 15‑word essence.

Live clock, buzz counter, marquee ticker, disruption meter, and a responsive trending grid – all in a single HTML file with zero build tools.

<img width="1347" height="768" alt="AI1" src="https://github.com/user-attachments/assets/3bf01fd1-da16-4dbf-826c-6988f8afa664" />
<img width="1349" height="768" alt="AI4" src="https://github.com/user-attachments/assets/33c83d83-35c9-4ffe-b6a7-8c993b93dfff" />
<img width="1349" height="768" alt="AI3" src="https://github.com/user-attachments/assets/d1def749-351b-4454-a9d9-a31dcee83ef2" />
<img width="1349" height="768" alt="AI2" src="https://github.com/user-attachments/assets/7f50da98-646f-43c2-92cb-6c78663ac5ee" />


## ✨ Features

- **Live Data** – Fetches the top 20 Hacker News stories and displays the top 10.
- **AI-Powered Vibe** – Gemini 1.5 Flash summarises the leading headline into an emotional vibe (e.g., Disruptive, Hopeful, Electric).
- **Marquee Ticker** – Persistent infinite‑scroll banner showing all 10 headlines.
- **Disruption Meter** – Visual bar showing the relative weight of the #1 story.
- **Asymmetrical Grid** – Feature‑first layout with smooth scroll‑reveal animations.
- **Latest Comments** – Displays the 5 most recent comments from the top story.
- **Dynamic Background** – Background subtly shifts towards teal as you scroll.
- **Graceful Degradation** – Works perfectly without an API key, showing an “AI Insight offline” banner.

## 🚀 Quick Start

1. **Download or clone** this repository.
2. **Open `index.html`** in any modern browser (Chrome, Edge, Firefox, Safari).
3. (Optional) **Add your Gemini API key** to enable AI analysis:
   - Open `index.html` in a text editor.
   - Find the line `const GEMINI_API_KEY = '';` near the top of the `<script>` block.
   - Insert your key between the quotes.
   - Save and refresh the browser.
4. **No server or build step required!**

> 💡 Get a free Gemini API key from [Google AI Studio](https://aistudio.google.com/apikey).

## 🧠 Technology

- **Frontend:** HTML5, CSS3 (Custom properties, Grid, Flexbox), vanilla JavaScript
- **Typography:** [Fraunces](https://fonts.google.com/specimen/Fraunces), [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [Inter](https://fonts.google.com/specimen/Inter)
- **APIs:** [Hacker News API](https://github.com/HackerNews/API), [Google Gemini API](https://ai.google.dev/gemini-api/docs)

## 📸 Preview


https://github.com/user-attachments/assets/63be83e4-7691-40ac-9eb1-c64ff3763a00


## ⚠️ API Key Security

If you plan to make your repository public, **never commit your real API key**. The `index.html` file uses a placeholder (`'YOUR_API_KEY'`) by default. Replace it only on your local copy, or keep the repository private.

## 📄 License

This project is for educational purposes. Feel free to use and adapt it.

---

Built with ❤️ for GTU SBTP 2026.
