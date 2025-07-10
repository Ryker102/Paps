social-audit-app/
│
├── client/                      # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── LoginButton.jsx
│   │   │   ├── Dashboard.jsx
│   │   │   └── SuspiciousPostCard.jsx
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   └── Analysis.jsx
│   │   ├── App.js
│   │   └── index.js
│   ├── .env                    # For frontend env vars (e.g., API URL)
│   └── package.json
│
├── server/                     # Backend (Node.js or Python)
│   ├── controllers/
│   │   └── analyzeController.js
│   ├── routes/
│   │   └── api.js
│   ├── services/
│   │   ├── twitterService.js
│   │   └── analysisService.js
│   ├── utils/
│   │   └── nlpUtils.js
│   ├── app.js
│   ├── config.js
│   ├── .env                    # Twitter API keys, server config
│   └── package.json
│
├── models/                     # ML Models (optional if Python-based)
│   └── propagandaModel.pkl
│
├── data/                       # Temp data storage or samples
│   └── sample_tweets.json
│
├── README.md
└── LICENSE
