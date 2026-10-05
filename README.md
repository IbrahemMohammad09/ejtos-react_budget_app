# Budget Allocation App

A React learning project for managing a company's departmental budget. It demonstrates shared application state with React Context and a reducer, alongside components for budgets, expenses, and allocation controls.

> **Project status:** The repository contains the state model and reusable UI components, while `src/App.js` still has placeholder sections. The full dashboard flow is not yet assembled.

## Tech stack
- React 18
- Create React App (`react-scripts`)
- React Context and `useReducer`
- Bootstrap 5

## Getting started
```bash
git clone https://github.com/IbrahemMohammad09/ejtos-react_budget_app.git
cd ejtos-react_budget_app
npm install
npm start
```

The development server opens at [http://localhost:3000](http://localhost:3000).

## Available scripts
- `npm start` — start the development server.
- `npm test` — run the test suite in watch mode.
- `npm run build` — create an optimized production build.
- `npm run eject` — expose the Create React App configuration (one-way).

## Source layout
- `src/components/` — budget, expense, and allocation UI.
- `src/context/AppContext.js` — initial budget data and reducer actions.

## License
This project includes a LICENSE file; see [LICENSE](LICENSE) for its terms.
