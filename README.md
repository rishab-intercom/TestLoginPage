# Login Page Testing Application

A minimal React TypeScript Vite application built for testing login functionality with LambdaTest.

## Features

- 🌑 Dark mode UI
- 🔐 Simple email/password authentication
- 📝 Hardcoded user credentials in JSON
- 🎯 Minimal design focused on testing
- ⚡ Built with Vite for fast development

## Test Credentials

The application includes three hardcoded test users:

- **Email:** test@example.com | **Password:** password123
- **Email:** admin@test.com | **Password:** admin123
- **Email:** user@demo.com | **Password:** demo123

## Getting Started

### Install Dependencies

```bash
npm install
```

### Run Development Server

```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
src/
├── Login.tsx          # Login page component
├── Login.css          # Login page styles
├── Dashboard.tsx      # Post-login dashboard
├── Dashboard.css      # Dashboard styles
├── users.json         # Hardcoded user credentials
├── App.tsx            # Router configuration
├── main.tsx           # Application entry point
└── index.css          # Global styles
```

## Testing with LambdaTest

This application is designed to be tested with LambdaTest for:

- Cross-browser login functionality
- Form validation
- Navigation after successful/failed login
- UI consistency across different browsers and devices

## Technologies Used

- React 18
- TypeScript
- Vite
- React Router DOM
