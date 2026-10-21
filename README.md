# Zoom Travels

A modern, visually engaging travel website built with **Astro**, **Tailwind CSS**, and **GSAP**. Zoom Travels presents destinations, travel services, testimonials, FAQs, and contact information through an immersive single-page experience. 


[Visit My Live Website](https://zoomtravels.net)


## Features

- Modern travel-focused landing page
- Responsive navigation bar
- Hero section with visual media
- About section
- Travel services overview
- Testimonials section
- Frequently asked questions
- Contact section
- Footer with supporting navigation
- Dot-based section navigation
- Smooth animations powered by GSAP
- Fast, lightweight static site generated with Astro
- Tailwind CSS styling

## Built With

- [Astro](https://astro.build/) — Static site framework
- [Tailwind CSS](https://tailwindcss.com/) — Utility-first CSS framework
- [GSAP](https://gsap.com/) — Animation library
- JavaScript — Interactive behavior and animations

## 📁 Project Structure

```text
/
├── public/
│   ├── icons/
│   ├── hero-1.jpg
│   ├── hero.png
│   ├── hero-video.mp4
│   ├── lady-window.jpg
│ ├── logo.png
│   └── logo-white.png
├── src/
│   ├── components/
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   ├── DotNav.astro
│   │   ├── FAQ.astro
│   │   ├── Footer.astro
│   │   ├── Hero.astro
│ │ ├── Navbar.astro
│   │   ├── Services.astro
│   │   └── Testimonials.astro
│   ├── layouts/
│   ├── pages/
│   │   └── index.astro
│   └── styles/
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) 18 or newer
- npm

### Installation

Clone the repository:

```bash
git clone https://github.com/AishShafa/zoom-travels.git
```

Navigate into the project directory:

```bash
cd zoom-travels
```

Install the dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The site will be available at:

```text
http://localhost:4321
```

## 📜 Available Commands

| Command | Description |
| --- | --- |
| `npm install` | Install project dependencies |
| `npm run dev` | Start the local development server |
| `npm run build` | Build the production-ready site |
| `npm run preview` | Preview the production build locally |
| `npm run astro` | Run Astro CLI commands |

## 🏗️ Production Build

Create an optimized production build with:

```bash
npm run build
```

The generated files will be available in the `dist/` directory.

To preview the production build locally:

```bash
npm run preview
```

## 🎨 Customization

You can customize the website by editing:

- `src/components/` — Page sections and reusable Astro components
- `src/pages/index.astro` — Main page composition
- `src/styles/` — Global styles and Tailwind-related styling
- `public/` — Images, videos, logos, icons, and other static assets
- `astro.config.mjs` — Astro configuration

## 🌍 Deployment

This Astro project can be deployed to platforms such as:

- Vercel
- Netlify
- GitHub Pages
- Cloudflare Pages
- Any static hosting provider

Run `npm run build` and deploy the contents of the generated `dist/` directory.

