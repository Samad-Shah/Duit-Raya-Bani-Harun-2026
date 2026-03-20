# 🌙 Berapa Duit Raya Saya?

An interactive Hari Raya duit raya lottery web app. Guests enter their name, press a button, and are dramatically revealed a random duit raya amount.

## Features
- Randomised duit raya amount (RM2, RM5, RM10, RM20, RM50)
- Dramatic drumroll suspense sequence with Web Audio
- Unique sound per result (sad trombone / fanfare / epic crowd cheer)
- Confetti celebration
- Google Sheets logging via Google Forms
- Hidden admin panel (tap subtitle 5× → password)

## Setup

1. Deploy via GitHub Pages (see below)
2. Open the live URL on your phone
3. Access admin settings: tap **"✦ Selamat Hari Raya Aidilfitri ✦"** 5 times → enter password `admin123`
4. Configure duit raya amounts, probabilities, and Google Sheets URL

## Deploy to GitHub Pages

See deployment instructions in the repo settings → Pages → set source to `main` branch `/root`.

## Google Sheets Integration

1. Create a Google Form with 2 short-answer questions: **Nama** and **Jumlah**
2. Click the 3-dot menu → **Get pre-filled link** → fill dummy data → copy the URL
3. Change `/viewform` to `/formResponse` in the URL
4. Find the `entry.XXXXXXXXX` field IDs in the page source (Ctrl+U, search `entry.`)
5. Paste all three values into the admin panel

## License
MIT
