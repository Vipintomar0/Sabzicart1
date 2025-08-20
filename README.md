Let me help you create a requirements list and setup instructions for the GST Invoice & Inventory Management App.

Requirements List
Core Dependencies
Node.js (v16 or higher)
NPM (v8 or higher)
MongoDB (v5 or higher)
Frontend Dependencies
{
  "dependencies": {
    "@reduxjs/toolkit": "^1.9.5",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-router-dom": "^6.14.0",
    "axios": "^1.4.0",
    "formik": "^2.4.2",
    "yup": "^1.2.0",
    "dexie": "^3.2.4",
    "chart.js": "^4.3.0",
    "react-chartjs-2": "^5.2.0",
    "@heroicons/react": "^2.0.18",
    "@tailwindcss/forms": "^0.5.3"
  },
  "devDependencies": {
    "tailwindcss": "^3.3.2",
    "postcss": "^8.4.24",
    "autoprefixer": "^10.4.14",
    "typescript": "^5.0.4",
    "@types/react": "^18.2.14",
    "@types/react-dom": "^18.2.6",
    "vite": "^4.4.0"
  }
}
Project Structure
gst-invoice-app/
├── src/
│   ├── components/          # Reusable components
│   ├── pages/              # Page components
│   ├── services/           # API services
│   ├── store/              # Redux store
│   ├── types/              # TypeScript types
│   ├── utils/              # Utility functions
│   ├── App.tsx            # Main app component
│   └── main.tsx           # Entry point
├── public/                 # Static assets
├── .env                    # Environment variables
├── index.html             # HTML template
├── package.json           # Dependencies
├── tailwind.config.js     # Tailwind configuration
├── tsconfig.json          # TypeScript configuration
└── vite.config.ts         # Vite configuration



Features Implementation Checklist
 User Authentication
 Product Management
 Add/Edit/Delete Products
 Stock Management
 Categories
 Customer Management
 Add/Edit/Delete Customers
 Customer History
 Invoice Generation
 GST Calculations
 PDF Export
 Print Support
 Reports
 Sales Reports
 Stock Reports
 GST Reports
 Offline Support
 Data Sync
 Local Storage
# Create production build
npm run build

# Preview production build
npm run preview

 Linting and Formatting

# Webpack & Extensions

This is an extension that uses [https://webpack.js.org]() to bundle and minify its sources. Using webpack will help to reduce the install- and startup-time of large extensions because instead of hundreds of files, a single file is produced.

## Configuration

Webpack is configured in the [`webpack.config.js`](./webpack.config.js)-file. Find annotation inside the file itself or refer to the excellent webpack documentation: [https://webpack.js.org/configuration/](). In short, the config-files defines the entry point of the extension, to use TypeScript, to produce a commonjs-module, and what modules not to bundle.

## Scripts

The `scripts`-section of the [`package.json`](./package.json)-file has entries for webpack. Those compile TypeScript and produce the bundle as well as producing a minified production build. Note, that there is no dedicated TypeScript-script as webpack takes care of that.


