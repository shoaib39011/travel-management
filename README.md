# Travel Frontend

A React-based travel application frontend built with Vite and modern web technologies.

## Features

- 🚀 Modern React 19 with Vite
- 🎯 React Router for navigation
- 📱 Responsive design
- 🔐 Login/Signup pages
- 📊 Dashboard interface
- 🚀 Automatic deployment to GitHub Pages

## Getting Started

### Prerequisites

- Node.js 18 or higher
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <your-repo-url>
cd travel-frontend
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

The application will be available at `http://localhost:5173/`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Deployment

This project is configured for automatic deployment to GitHub Pages using GitHub Actions. Every push to the main branch will trigger a build and deployment.

### Manual Deployment

To deploy manually:

```bash
npm run build
```

## Project Structure

```
src/
├── components/     # Reusable components
│   └── Navbar.jsx
├── pages/          # Page components
│   ├── Login.jsx
│   ├── Signup.jsx
│   └── Dashboard.jsx
├── assets/         # Static assets
├── App.jsx         # Main app component
├── main.jsx        # Entry point
└── index.css       # Global styles
```

## Technologies Used

- React 19
- React Router DOM
- Vite
- Axios (for API calls)
- ESLint (for code linting)
