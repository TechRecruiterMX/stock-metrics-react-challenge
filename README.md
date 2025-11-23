# 🧮 Stock Metrics Challenge (React)

A frontend coding challenge where you will consume a financial API, process 2,500 records, and compute multiple analytics using React.

---

## 🎯 Objective

Build a React web application that:

1. Calls the API **five times** (pages 1–5, each returning 500 items).
2. Combines all responses into a **single dataset of 2,500 records**.
3. Calculates and displays the following metrics:

### 📉 Metric 1  
**The lowest value across all `low` fields** available in the dataset.

### 📈 Metric 2  
**The average of all `open` values from the year 2020.**

### 🧭 Metric 3  
**The date where the difference between `high` and `low` is the largest.**

The UI can be a table, cards, chart, or any clear visual representation.

Include:

- A loading state
- An error state
- A clean and usable interface

---

## ⚙️ Technical Requirements

You may use:

- **React 18+** (Create React App, Vite, or Next.js)
- JavaScript or TypeScript
- Libraries such as:
  - `axios` or `fetch` for API calls
  - `chart.js` or `recharts` (optional)
  - `tailwindcss`, `styled-components`, or similar (optional)

---

## 📦 Deliverables

Your submission must include:

- A main component (`App.jsx` or `App.tsx`)
- Logic that performs **paginated API requests**
- Metric calculations
- Visual rendering of results (table, cards, or charts)

You may submit:

- GitHub repository link  
- Or a deployed version (Vercel, Netlify — optional)

---

## 🚀 Good luck!

This challenge is meant to evaluate your ability to work with APIs, combine datasets, compute analytics, and present results cleanly using React.
