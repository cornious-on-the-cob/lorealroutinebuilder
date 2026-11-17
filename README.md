# 💄 L'Oréal Routine Builder

An AI-powered beauty consultant web app that helps users build a personalized L'Oréal routine. Browse a curated catalog of 30 products across L'Oréal's brands (Lancôme, CeraVe, Kérastase, La Roche-Posay, Garnier, and more), select your favorites, and chat with an AI beauty consultant for tailored advice.

## ✨ Features

- **AI chat consultant** — powered by OpenAI through a Cloudflare Worker endpoint, with product-aware context (the consultant knows what you've selected)
- **Bilingual interface** — full English / Arabic support with automatic RTL layout switching
- **Routine builder** — select products and generate an organized skincare / makeup / hair routine
- **Search & category filtering** across the product catalog
- **Graceful degradation** — falls back to local responses if the AI service is unreachable
- Fully responsive, built with **vanilla HTML, CSS, and JavaScript** — no frameworks

## 🚀 Live Demo

[View Live Site](https://cornious-on-the-cob.github.io/lorealroutinebuilder/)

## 🛠️ Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript (ES5-compatible)
- Cloudflare Workers (API proxy)
- OpenAI API (chat completions)
- Font Awesome icons

## 💻 Run Locally

```bash
git clone https://github.com/cornious-on-the-cob/lorealroutinebuilder
cd lorealroutinebuilder
```

Then open `index.html` in your browser — no build step required.

## 📚 What I Learned

- Integrating a third-party AI API through a serverless proxy (keeping keys off the client)
- Internationalization and RTL layout handling
- Managing UI state and chat history without a framework
- Defensive UX: typing indicators, error handling, and offline fallbacks
