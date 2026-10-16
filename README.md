# HarvestHackers
Repo for team 25 project

folder sturcture proposal 
main-app
├── client/                  # Frontend Application (React, Vue, Vite, etc.)
│   ├── public/              # Static assets exposed directly to the web
│   └── src/
│       ├── assets/          # Images, logos, global CSS
│       ├── components/      # Reusable UI elements (Buttons, Inputs, Modals)
│       ├── hooks/           # Custom React/Vue hooks (e.g., useAuth)
│       ├── pages/           # View components mapped to page routes
│       ├── services/        # API request configurations (Axios/Fetch wrappers)
│       ├── store/           # Global state management (Redux, Zustand, Pinia)
│       ├── utils/           # Shared helper functions (formatters, validators)
│       ├── App.jsx          # Main application entry component
│       └── main.jsx         # DOM mounting file
│   ├── .env.development     # Client-side environment variables
│   └── package.json         # Frontend dependencies
│
├── server/                  # Backend Application (Node.js, Express, Python, etc.)
│   └── src/
│       ├── config/          # Database, CORS, and mailer setups
│       ├── controllers/     # Route logic handlers (processes requests & sends responses)
│       ├── middlewares/     # Auth guards, error handlers, data validators
│       ├── models/          # Database schemas / ORM models (Mongoose, Prisma, SQL)
│       ├── routes/          # REST/GraphQL endpoint declarations (e.g., /api/users)
│       ├── services/        # Core business logic / Third-party API integrations
│       └── app.js           # Server initialization code
│   ├── .env                 # Server-side secrets (DB URI, Private Keys)
│   └── package.json         # Backend dependencies
│
└── README.md                # Global documentation for local setup