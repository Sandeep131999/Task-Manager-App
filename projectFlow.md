task-manager-app/
├── config/
│   └── db.js              # Database configuration (MongoDB connection)
├── controllers/
│   ├── authController.js   # Logic for signup, login, logout
│   ├── taskController.js   # Logic for task-related routes
│   └── categoryController.js # Logic for category-related routes
├── middlewares/
│   └── authMiddleware.js   # Middleware for authentication checks
├── models/
│   ├── User.js             # User model schema
│   ├── Task.js             # Task model schema
│   └── Category.js         # Category model schema
├── public/                 # Public assets (CSS, JS, images)
│   └── css/
│       └── styles.css      # Basic styles for the app
├── routes/
│   ├── authRoutes.js       # Routes for signup, login, logout
│   ├── taskRoutes.js       # Routes for task creation, updating, deletion
│   └── categoryRoutes.js   # Routes for category creation, viewing, deletion
├── views/                  # EJS templates (if using EJS for the frontend)
│   ├── signup.ejs          # Signup page
│   ├── login.ejs           # Login page
│   ├── tasks.ejs           # View tasks page
│   └── categories.ejs      # View categories page
├── .gitignore              # Ignoring node_modules, env files, etc.
├── app.js                  # Main app setup with Express
├── package.json            # NPM dependencies and scripts
├── package-lock.json       # Lock file for package versions
└── README.md               # Project overview
