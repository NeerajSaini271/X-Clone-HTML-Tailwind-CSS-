# X-Clone (HTML + Tailwind CSS)
X (Twitter) UI built with HTML + Tailwind CSS

![X Clone screenshot](img/X%20Clone.png)

**Live demo:** https://x-clone-bm.netlify.app/

## Summary
This is a front-end replica of the X (formerly Twitter) homepage UI, built using **HTML5** and **Tailwind CSS** (via Play CDN). It demonstrates layout structure, responsive utility classes, and a clean, mobile-first approach.

## Features
- Header, sidebar, main timeline, tweet composer, and footer — visually aligned with X’s UI  
- Responsive layout using Tailwind’s breakpoints and utility classes  
- Uses Tailwind Play CDN (no local build) for rapid prototyping  

## Tech Stack
- HTML5  
- Tailwind CSS (Play CDN)  
- (Future option: Tailwind local build & purge)

## Live Demo
[https://x-clone-bm.netlify.app/](https://x-clone-bm.netlify.app/)

## Getting Started

1. Clone or download this repository.  
2. Ensure the `img/` folder contains `X Clone.png`.  
3. Open `index.html` in your browser.

Because it uses the Tailwind CDN, you don’t need Node or build tools to see the UI.

## Tailwind Play CDN usage

This project includes a `<script>` tag like:

```html
<script src="https://cdn.tailwindcss.com"></script>
