# Chandra Bose Boyapati · Supply Chain Portfolio

**Live site:** https://bose-bot.github.io/bose-bot-portfolio/

An interactive 3D portfolio for a supply chain, logistics and planning analyst. Built with **React 18**, **Three.js** and plain **HTML/CSS/JavaScript**. No build step: it is a single `index.html` plus an `img/` folder.

## What's inside
- **Hero reel**: a 35-second, five-scene 3D film of a supply chain (inventory, replenishment, suppliers, fulfillment, end to end) with a scrubbable timeline.
- **Four case studies**, each with a five-stage 3D story built from resume bullets:
  - End-to-end demand & supply planning (Taylor Logistics)
  - Line-side inventory control (Hindustan Unilever)
  - JIT material supply optimization (Hindustan Unilever)
  - Supply chain KPI dashboard & automation (project)
- **How I work**: a six-step planning approach.
- **Beat my forecast**: drag-to-edit forecast game with MAPE, bias and an auto-tune model (sample data).
- **Safety stock lab**: SS / ROP calculator with a 90-day inventory simulation and an auto-optimizer.
- **Skills warehouse**: every skill as a labelled crate in a 3D rack.
- **30-second view**, shipment-tracker progress rail, **Auto / Manual** motion modes and **Day / Dusk / Night** colour schemes.

## Run locally
Open `index.html` in a browser, or serve the folder:
```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on GitHub Pages
1. Upload these files to the `bose-bot/bose-bot-portfolio` repository (branch `main`).
2. On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**, choose `main` and `/ (root)`, then **Save**.
3. The site goes live at **https://bose-bot.github.io/bose-bot-portfolio/** within a minute or two.
4. Link previews (LinkedIn, WhatsApp, Slack) already point to `img/social-preview.jpg` at this address.

## Notes
- Libraries load from cdnjs and unpkg (React 18.3.1, ReactDOM 18.3.1, htm 3.1.1, Three.js r128).
- All images are original 3D renders made for this site.
- The forecast game uses sample data, and the planning feed is simulated; both are labelled on the page.
- Respects `prefers-reduced-motion`; colour scheme choice is remembered per visitor.
