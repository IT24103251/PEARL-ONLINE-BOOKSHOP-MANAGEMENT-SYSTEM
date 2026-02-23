# src/

This folder contains the entire React frontend source code (Vite + React).

Rules:
- Feature-specific logic goes in `features/`
- Shared UI components go in `components/`
- Backend API calls go in `features/<feature>/services/`
- Global HTTP config goes in `services/`
- Env variables must start with `VITE_`


src/
├─ app/
│  ├─ App.jsx
│  ├─ routes.jsx
│  └─ providers.jsx
│
├─ features/
│  ├─ auth/
│  │  ├─ components/
│  │  ├─ services/
│  │  └─ AuthPage.jsx
│  └─ users/
│     ├─ components/
│     ├─ services/
│     └─ UsersPage.jsx
│
├─ components/
│  ├─ Button.jsx
│  └─ Modal.jsx
│
├─ services/
│  └─ apiClient.js
│
├─ hooks/
│  └─ useDebounce.js
│
├─ lib/
│  └─ constants.js
│
├─ styles/
│  └─ globals.css
│
├─ assets/
│
├─ main.jsx
└─ index.css
