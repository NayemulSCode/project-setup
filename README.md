my-vite-app/
│
├── public/               # Static assets (like in Next.js public folder)
│     ├── images/
│     └── favicon.ico
│
├── src/                  # Source files
│   ├── pages/            # Like Next.js pages folder
│   │     ├── index.jsx   # Home page ("/")
│   │     ├── about.jsx   # About page ("/about")
│   │     └── contact.jsx # Contact page ("/contact")
│   │
│   ├── components/       # Reusable UI components
│   │     ├── Navbar.jsx
│   │     ├── Footer.jsx
│   │     └── Button.jsx
│   │
│   ├── layouts/          # Shared page layouts (optional, like _app in Next.js)
│   │     ├── MainLayout.jsx
│   │     └── AuthLayout.jsx
│   │
│   ├── hooks/            # Custom React hooks
│   │     └── useAuth.js
│   │
│   ├── utils/            # Helper functions and constants
│   │     └── api.js
│   │
│   ├── router/           # React Router setup (similar to Next.js file routing)
│   │     └── index.jsx
│   │
│   ├── assets/           # Images, fonts, CSS files (if not in public)
│   │     └── logo.png
│   │
│   ├── App.jsx           # Main App component
│   ├── main.jsx          # Entry point (Vite-specific)
│   └── index.css         # Global styles
│
├── .gitignore
├── index.html
├── package.json
├── vite.config.js
└── README.md

<!-- git command -->
git clone remote_url
git init
git add .
git commit -m"message"
git pull origin "branch_name"
git push -u origin master or main
git stash