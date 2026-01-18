# TakeProfit — Automatic Crypto Bot (Team Project) | Showcase

![TakeProfit screenshot](./takeprofit.png)

This repository is a **public showcase** of the TakeProfit project built during AIT training.  
The original deployed website is **offline** (domain was not renewed), so this repo preserves:
- screenshots
- feature overview
- my contribution

---

## Project summary
**TakeProfit** is a fullstack web application for automated crypto trading workflows.

- **Frontend:** React + TypeScript + Vite (TailwindCSS, Redux)
- **Backend:** Java 17 + Spring Boot (Spring Security + JWT)
- **Database:** MongoDB (Atlas)
- **API docs:** Swagger / OpenAPI
- **Team size:** 5 (developers + QA)
- **Delivery style:** Git workflow, branches, PRs, code reviews

---

## Project status (selected)
- ✅ Basic authentication endpoints
- ✅ JWT authorization
- ✅ Swagger / OpenAPI documentation
- ✅ MongoDB connection
- ✅ Email confirmation flow
- ✅ Tests (backend)

---

## Key features (high level)
- Authentication & user flows (roles: USER / ADMIN)
- Trading dashboard UI (charts, modes, status)
- Bot management (create/update/delete, simulation concept)
- API-driven architecture (frontend ↔ backend)

---

## API overview (selected)
- `POST /api/v1/register` — registration  
- `POST /api/v1/login` — login (JWT)  
- `GET /api/v1/bots` — list bots  
- `POST /api/v1/bots` — create bot  
- `GET /api/v1/symbols` — trading pairs  
- `GET /candles/{symbol}` — chart data  

---

## My contribution
- Implemented frontend pages/components and API integration
- Worked with state management and UI structure (React/TS)
- Participated in team development process (branches, PRs, reviews)
- Coordinated with QA and backend teammates during testing/debugging

---

## Source code
The full source code is kept in private repositories (**available on request**):
- Frontend: https://github.com/IngaPal/takeprofit-frontend
- Backend: https://github.com/IngaPal/takeprofit-backend
