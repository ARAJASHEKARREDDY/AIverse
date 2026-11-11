# AIverse — AI Tools Discovery Platform 🌌

**Live website:** https://aiverse-mu.vercel.app/

This repository is a fresh implementation of an AI tools discovery directory using **HTML, CSS, JavaScript, React, Bootstrap, Node.js and Express**. It is not the original source code of the deployed website. The sample catalogue and features are a starting point; compare them with the live application and update them before claiming they are exact.

## 1. How I built it
- HTML provides the page structure.
- CSS styles the interface and responsive layout.
- JavaScript handles interactions and data flow.
- React builds reusable components and manages interface state.
- Bootstrap 5 supports responsive layout and form controls.
- Node.js and Express provide REST API endpoints for the tool catalogue.
- Vite runs the frontend development server and builds production assets.

## 2. Starter features
- Search tools by name, description, category or tag.
- Filter by category and pricing label.
- Browse tool cards with descriptions and official links.
- Save favourites in browser local storage.
- Responsive desktop and mobile layout.
- API endpoints for tool list, categories, individual tools and health check.

## 3. How AIverse can help people
Students may discover learning and writing helpers; job seekers may explore tools for drafting and interview preparation; creators may find design, image, audio and video tools; professionals and small businesses may investigate productivity and research options. A central directory can make discovery easier, but users should verify generated information and check each provider's pricing, terms and privacy policy.

## 4. Future enhancements
- More verified tools and detailed categories.
- Advanced search, filters and side-by-side comparisons.
- User accounts and cloud-synced favourites.
- Community submissions with moderation.
- Verified pricing and last-checked dates.
- Automated broken-link checks, tests, accessibility and performance improvements.

See `docs/FUTURE_ROADMAP.md` and `docs/USER_BENEFITS.md`.

## Run locally
Requirements: Node.js 18+ and npm.

```bash
npm install
cp .env.example .env
npm run dev
```
Frontend: http://localhost:5173  
Backend health check: http://localhost:5000/api/health

## API endpoints
| Method | Endpoint | Purpose |
|---|---|---|
| GET | `/api/health` | Check server status |
| GET | `/api/categories` | List categories |
| GET | `/api/tools` | List/search/filter tools |
| GET | `/api/tools/:id` | Get one tool |

Example: `http://localhost:5000/api/tools?search=writing&category=All`

## Before publishing
Verify every catalogue entry and pricing detail against official sources. Never commit API keys, passwords or `.env` secrets. Add genuine screenshots and update this README to match the features you have actually tested.

**Status:** Starter implementation for further customisation.
