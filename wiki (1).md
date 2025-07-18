# Project Summary
GraphiTask is a web application designed for freelance graphic designers in French-speaking Africa. It enables users to manage their graphic projects, including tasks related to logos, flyers, and other designs. The app focuses on local storage, allowing users to track clients, pricing in FCFA, deadlines, and project progress without needing an internet connection.

# Project Module Description
GraphiTask comprises several functional modules:
- **Task Management**: Create, edit, and delete tasks with detailed attributes.
- **Dashboard**: Overview of all tasks with filtering and sorting options.
- **Local Storage**: Utilizes local storage for data persistence, ensuring offline functionality.
- **Theme Provider**: Supports light and dark themes for a better user experience.

# Directory Tree
```
shadcn-ui/
├── README.md                 # Project documentation
├── components.json           # Component definitions
├── eslint.config.js          # ESLint configuration
├── index.html                # Main HTML file
├── package.json              # Project metadata and dependencies
├── postcss.config.js         # PostCSS configuration
├── public/                   # Public assets
│   ├── favicon.svg           # Favicon
│   └── robots.txt            # Robots.txt file
├── src/                      # Source code
│   ├── App.css               # Global CSS styles
│   ├── App.tsx               # Main application component
│   ├── components/           # UI components
│   ├── contexts/             # Context providers
│   ├── hooks/                # Custom hooks
│   ├── pages/                # Application pages
│   ├── lib/                  # Utility functions
│   ├── index.css             # Tailwind CSS styles
│   ├── main.tsx              # Application entry point
│   └── vite-env.d.ts         # TypeScript environment definitions
├── tailwind.config.ts        # Tailwind CSS configuration
├── template_config.json      # Template configuration
├── tsconfig.app.json         # TypeScript configuration for app
├── tsconfig.json             # Base TypeScript configuration
└── vite.config.ts            # Vite configuration
```

# File Description Inventory
- **README.md**: Documentation and project overview.
- **components.json**: Definitions of UI components.
- **eslint.config.js**: Configuration file for linting JavaScript files.
- **index.html**: Entry point of the web application.
- **package.json**: Contains project dependencies and scripts.
- **postcss.config.js**: Configuration for PostCSS processing.
- **public/**: Directory for static assets.
- **src/**: Contains all source code, including components, pages, and styles.

# Technology Stack
- **Frontend**: React.js, TypeScript
- **Styling**: Tailwind CSS
- **State Management**: React Context API
- **Build Tool**: Vite
- **Form Validation**: React Hook Form with Zod

# Usage
1. Install dependencies:
   ```
   pnpm install
   ```
2. Build the project:
   ```
   pnpm run build
   ```
3. Run the application:
   ```
   pnpm run dev
   ```
