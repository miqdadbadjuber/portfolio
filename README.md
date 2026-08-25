# Miqdad Badjuber - Engineering Portfolio

Personal engineering portfolio and technical showcase of **Miqdad Badjuber**, focusing on Applied Machine Learning, LLM Context Engineering, Workflow Automation, and High-Performance Web Graphics.

Live Website: [https://miqdadbadjuber.id](https://miqdadbadjuber.id)

---

## Key Technical Highlights

- **Custom ASCII 3D Earth Canvas:** Procedural WebGL scene built with Three.js, rendering dynamic text-shaded planet geometry at 60 FPS with automatic GPU throttling when scrolled out of view.
- **Zero-Layout-Shift Architecture:** Pixel-locked subpage layout across desktop and mobile, stabilized scrollbar gutters, and instant native browser history back navigation.
- **Generative Engine Optimization (GEO):** Structured JSON-LD Schema.org metadata and `llms.txt` integration for automated indexing by AI search engines and LLM crawlers (Perplexity, ChatGPT, Claude).
- **Stealth Minimalist Interface:** Dark theme built with Space Grotesk and Inter typography, subtle HUD line accents, magnetic cursor interactions, and Lenis smooth scrolling.

---

## Featured Projects

1. **AntiSlop:** Deterministic rules and liveliness filters for AI coding assistants to eliminate generic AI-slop code and copy while preserving creative project design.
   - GitHub: [https://github.com/miqdadbadjuber/anti-slop](https://github.com/miqdadbadjuber/anti-slop)
   - Skills Listing: [https://skills.sh/miqdadbadjuber/anti-slop](https://skills.sh/miqdadbadjuber/anti-slop)

2. **ContextForge:** Token-efficient context engineering and prompt architecture toolkit designed for local codebases and production LLM workflows.
   - GitHub: [https://github.com/MiqdadBadjuber/contextforge](https://github.com/MiqdadBadjuber/contextforge)

3. **DiagramPilot:** AI-assisted natural language to architecture diagram and flowchart generation engine.
   - GitHub: [https://github.com/miqdadbadjuber/DiagramPilot-AI](https://github.com/miqdadbadjuber/DiagramPilot-AI)

4. **OpenFolio:** Clean, minimalist developer portfolio generator focused on engineering clarity and performance.
   - GitHub: [https://github.com/miqdadbadjuber/OpenFolio-AI](https://github.com/miqdadbadjuber/OpenFolio-AI)

5. **Applied ML & Workflow Automations:** End-to-end event-driven integrations, n8n pipelines, and specialized machine learning models.

---

## Tech Stack

- **Core:** Semantic HTML5, Modern Vanilla JavaScript (ES6+), CSS3
- **Styling:** Tailwind CSS (Precompiled Static Build)
- **Graphics & Motion:** Three.js (WebGL Canvas), GSAP, Lenis Smooth Scroll
- **Deployment:** Vercel (Clean URLs & Trailing Slash Routing), GitHub Pages

---

## Project Structure

```text
portfolio/
├── index.html                  # Main landing page
├── about/                      # Detailed About & background page
├── blog/                       # Technical blog and engineering essays
│   ├── index.html              # Article feed directory
│   ├── anti-ai-slop.html       # Article on Anti-AI-Slop design
│   ├── context-engineering-... # Essay on Context Engineering vs Fine-Tuning
│   ├── optimizing-canvas-...   # Engineering breakdown of 60 FPS ASCII Canvas
│   └── ai-agents-n8n-...       # Workflow automation & AI agents guide
├── projects/                   # Project showcase & deep-dive pages
├── credentials/                # Certifications and open-source contributions
├── assets/                     # Optimized images, certs, and 3D canvas files
│   ├── bumi.html               # Procedural Three.js ASCII Earth WebGL scene
│   └── images/                 # Optimized webp assets and favicons
├── llms.txt                    # Standardized AI / LLM crawler profile
├── sitemap.xml                 # Search engine sitemap for all 15 URLs
├── robots.txt                  # Web crawler permissions
└── vercel.json                 # Vercel deployment routing & security headers
```

---

## Local Development

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/miqdadbadjuber/portfolio.git
   cd portfolio
   ```

2. Start a local server:
   ```bash
   # Using Python 3
   python -m http.server 3000

   # Or using Node.js / npx
   npx serve .
   ```

3. Open your browser at `http://localhost:3000`.

---

## Customization & Attribution Guidelines

If you fork or clone this repository to build your own portfolio:

- **Replace Personal Identity:** Please replace all personal information (name, bio, social media links, contact details, and the 3D ASCII text configuration in `assets/bumi.html`) with your own.
- **Showcase Your Own Work:** The project case studies, technical essays, and credentials represent personal experience and original research. Please write your own authentic project showcases and articles rather than copying the text verbatim.
- **Open Architecture:** You are welcome to use the frontend architecture, responsive layout, and WebGL ASCII implementation as inspiration or a template for your personal portfolio.

---

## License

This project is open source and available under the [MIT License](LICENSE).

