# AXON — AI Consulting Landing Page

A modern, production-grade landing page for a fictional AI consulting company called **AXON**. Built as a portfolio project to demonstrate frontend design and development skills.

## Live Demo

> Deploy via GitHub Pages: Settings → Pages → Branch: main → Save  
> Live at: `https://theokalogr-bit.github.io/Axon-ai-consulting-website`

## Preview

The page features a dark editorial luxury aesthetic — deep charcoal backgrounds, warm gold accents, and a fully animated neural network canvas in the hero section.

## What's Inside

### Brand Identity
- **Name & concept**: AXON — referencing neural axons and intelligent signal transmission
- **Logo**: Custom SVG neural-node mark with radiating spokes and terminal dots
- **Color palette**: Deep charcoal `#0c0b09` + warm gold `#d4aa50`
- **Typography**: Cormorant Garamond (serif display) + DM Mono (monospace) + Outfit (body)

### Page Sections
| Section | Description |
|---|---|
| Navigation | Fixed navbar with blur-on-scroll, logo, links, CTA button |
| Hero | Animated particle neural network canvas, headline, live metrics card |
| Clients | Trusted-by strip with 6 enterprise names |
| Services | 3×2 grid — 6 service cards with custom SVG icons |
| Process | 4-step horizontal timeline (Discover → Architect → Build → Scale) |
| Case Studies | Asymmetric layout with an on-brand data visualization graphic |
| Testimonial | Large italic pull quote with oversized decorative mark |
| Team | 3-column cards with abstract SVG portrait art |
| CTA | Full-width call-to-action with radial glow |
| Footer | 4-column with social links and legal bar |

### Technical Details
- **Single file** — all HTML, CSS, and JS in `index.html`, no build step needed
- **Tailwind-free** — 100% custom CSS with CSS variables for the design system
- **Animations** — CSS keyframes for hero entrance, JS canvas for the neural network, IntersectionObserver for scroll reveals
- **Custom cursor** — gold dot + lagging ring, switches on hover
- **Fully responsive** — mobile-first, collapses gracefully at 1024px and 640px
- **No placeholder images** — all visuals are inline SVG art matching the brand palette

## Running Locally

Requires [Node.js](https://nodejs.org/).

```bash
# Clone the repo
git clone https://github.com/theokalogr-bit/Axon-ai-consulting-website.git
cd Axon-ai-consulting-website

# Start the local server (serves on http://localhost:3000)
node serve.mjs
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
├── index.html       # Complete landing page (HTML + CSS + JS)
├── serve.mjs        # Simple Node.js static file server
├── screenshot.mjs   # Puppeteer screenshot utility (dev only)
└── package.json     # Node dependencies (puppeteer-core for screenshots)
```

## Skills Demonstrated

- UI/UX design from scratch (brand naming, logo, color system, typography pairing)
- Advanced CSS (custom properties, layered shadows, complex animations, grid/flexbox)
- Vanilla JavaScript (Canvas API, IntersectionObserver, custom cursor)
- SVG illustration (logo, icons, data visualization, abstract portrait art)
- Responsive design and mobile-first layout

---

*Built with Claude Code*
