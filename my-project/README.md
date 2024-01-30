# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

---

---

---

---

******\******* Folder Structure ************\*\*************

student-registration-app/
│
├── public/
│ └── index.html
│
├── src/
│ ├── components/
│ │ ├── common/ # Shared components like buttons, inputs, etc.
│ │ ├── layout/ # Layout components like header, footer, etc.
│ │ └── registration/ # Components specific to student registration
│ │
│ ├── pages/ # Different pages of the application
│ │ ├── HomePage.js
│ │ ├── RegistrationPage.js
│ │ └── ...
│ │
│ ├── utils/ # Utility functions and helpers
│ │
│ ├── api/ # API related functions
│ │
│ ├── context/ # Context API (if using for state management)
│ │
│ ├── assets/ # Static files like images, stylesheets, etc.
│ │ ├── css/
│ │ ├── images/
│ │ └── ...
│ │
│ ├── App.js # Main app component
│ ├── index.js # Entry point for React rendering
│ └── ...
│
├── package.json
└── ...
