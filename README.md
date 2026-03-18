# CYBRIGE Ethical Hacker Masterclass — Landing Page

A dark-themed, conversion-focused landing page for the CYBRIGE Ethical Hacking Live Masterclass at ₹9.

## Tech Stack

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Razorpay Payment Links

## Features

- Live countdown timer to workshop date
- Razorpay payment integration on all CTA buttons
- Auto-rotating enrollment notification popup (30 names)
- Animated pulse CTA buttons
- YouTube student testimonial cards
- Student LinkedIn achievement gallery
- WhatsApp floating button
- Fully responsive (mobile + desktop)

## Folder Structure
```
project/
├── index.html
└── assets/
    ├── logo.png
    ├── trainer.jpg
    ├── yash.jpg
    ├── suman.jpg
    ├── ronak.jpg
    ├── prit.jpg
    ├── asu.jpg
    ├── sameer.jpg
    ├── ronak_kumar.jpg
    └── big_win.jpg
```

## How to Use

1. Clone the repo
2. Add your images to the `assets/` folder
3. Open `index.html` in any browser — no build step needed

## Key Things to Edit

| What | Where in index.html |
|---|---|
| Workshop date/time | `var deadline = new Date(...)` in the script at the bottom |
| Logo | `src="assets/logo.png"` (3 places — navbar, hero, footer) |
| Hero image | `src="assets/hero-banner.jpg"` in the hero section |
| Razorpay link | All `href="https://pages.razorpay.com/..."` on CTA buttons |
| Enrollment names | `enrollmentNotifications` array in the popup script |
| Social media links | Footer icon `href` values |

## Client

Cybrige Solutions — [cybrige_solutions](https://www.instagram.com/cybrige_solutions/)
