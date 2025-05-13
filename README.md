web application implementing multi-factor authentication (MFA) using:

Username & Password (1st Factor)

OTP Verification (2nd Factor) via Email or Phone
multi-factor-auth/
├── client/                    # React + Vite frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   └── Login.jsx
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── login.css
│   ├── package.json
│   ├── vite.config.js
│   └── .eslintrc.cjs
├── server/                    # Express backend
│   ├── models/
│   │   └── User.js
│   ├── routes/
│   │   └── auth.js
│   ├── utils/
│   │   └── sendOtp.js
│   ├── index.js
│   ├── .env
│   └── package.json
├── README.md
└── .gitignore
