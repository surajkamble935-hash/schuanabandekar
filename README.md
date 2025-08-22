# Schauna Bandekar – Portfolio Website

This is a personal portfolio website with a Creative Corner powered by Google Gemini API.

## 🚀 Run Locally
1. Open `index.html` directly in your browser  
   OR run a local server:
   ```bash
   python3 -m http.server 8000
   ```
   then visit http://localhost:8000

## 🔑 Configure Gemini API
1. Get a free API key from [Google AI Studio](https://aistudio.google.com/).
2. In `index.html`, replace `YOUR_API_KEY_HERE` with your key.

## 📩 Contact Form Setup
The site uses [Formspree](https://formspree.io/) for email contact.
1. Sign up for free at Formspree.
2. Create a new form → copy your **Form ID** (looks like `abcd1234`).
3. In `index.html`, replace:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
   with your Formspree form URL.

Now all form submissions will be delivered to your email.

## 🎨 Customize Content
- Replace images inside `/assets/`
- Update text in `index.html`
- Add your own projects, skills, education, etc.

## 🌍 Deploy Online
**Option A – Netlify**
1. Go to [Netlify](https://netlify.com)
2. Drag & drop the `portfolio-site/` folder → Done!

**Option B – GitHub Pages**
1. Create a GitHub repo → Upload files
2. In repo settings → Pages → Deploy from `main` branch
3. Your portfolio will be live at: `https://username.github.io/portfolio-site/`
