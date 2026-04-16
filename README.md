# USER-AUTHENTICATION-SYSTEM


src/
│
├── config/
│   └── db.js                # Database connection
│   └── env.js               # Env Variables
├── controllers/
│   └── auth.controller.js  # Handles request/response
│
├── services/
│   └── auth.service.js     # Business logic
│
├── models/
│   └── user.model.js       # User schema/table
│
├── routes/
│   └── auth.routes.js      # API endpoints
│
├── middlewares/
│   ├── auth.middleware.js  # JWT verification
│   └── role.middleware.js  # Admin/user check
│
├── validators/
│   └── auth.validator.js   # Input validation
│
├── utils/
│   ├── generateToken.js    # JWT creation
│   └── hashPassword.js     # bcrypt helper
│
├── app.js
└── server.js