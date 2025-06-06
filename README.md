# uuugit checkout develop
git pull origin develop
git checkout feature/frontend
git merge develop
crm-lite/
├── client/               # Frontend (React)
│   ├── App.jsx
│   ├── Dashboard.jsx
│   ├── CustomerList.jsx
│   ├── FormCustomer.jsx
│   └── styles/
├── server/               # Backend (Luis)
├── db/                   # Base de datos (Camila)
├── auth/                 # Seguridad (Pedro)
├── integrations/         # Automatización (Sofía)
├── README.md
└── .gitignore
