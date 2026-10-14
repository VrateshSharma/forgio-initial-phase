# forgio-initial-phase


forge-backend/
├── prisma/
│   ├── schema.prisma
│   ├── migrations/
│   └── seed.js
├── src/
│   ├── app.js
│   ├── server.js
│   ├── config/
│   │   ├── env.js
│   │   ├── database.js
│   │   └── oauth.js
│   ├── middleware/
│   │   ├── authenticate.js
│   │   ├── authorize.js
│   │   ├── validate.js
│   │   ├── errorHandler.js
│   │   └── rateLimiter.js
│   ├── modules/
│   │   ├── auth/
│   │   │   ├── auth.routes.js
│   │   │   ├── auth.controller.js
│   │   │   ├── auth.service.js
│   │   │   └── auth.schema.js
│   │   ├── users/
│   │   ├── profiles/
│   │   ├── competitions/
│   │   ├── saved-competitions/
│   │   ├── teams/
│   │   ├── team-members/
│   │   ├── team-requests/
│   │   ├── invitations/
│   │   ├── chat/
│   │   ├── achievements/
│   │   ├── recommendations/
│   │   └── admin/
│   ├── routes/
│   │   └── index.js
│   ├── utils/
│   │   ├── apiError.js
│   │   ├── pagination.js
│   │   └── logger.js
│   └── tests/
│       ├── unit/
│       ├── integration/
│       └── fixtures/
├── .env.example
├── .gitignore
├── .nvmrc
├── package.json
├── package-lock.json
└── README.md
