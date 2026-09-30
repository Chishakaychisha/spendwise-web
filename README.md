# SpendWise Web

A responsive React personal-finance dashboard. It is designed as a polished frontend companion to the SpendWise Spring Boot API, while remaining usable as a standalone prototype.

## Highlights

- React component and hook-based state management
- Live monthly-spend total derived from transaction data
- Controlled add-expense form
- Responsive CSS Grid layout for desktop and mobile
- Original dashboard visual system

## Run

```bash
npm install
npm run dev
```

Use `npm run build` for a production build.

## Structure

```text
src/App.jsx  dashboard state and UI
src/App.css  responsive design system
```

## Roadmap

Connect to the SpendWise API, add authentication, budget charts, categories, date filters, and PostgreSQL persistence.

**Stack:** React · Vite · JavaScript · CSS
