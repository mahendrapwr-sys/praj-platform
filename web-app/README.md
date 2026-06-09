# PRAJ Platform - React Web App

A modern React TypeScript web application built with Vite and Tailwind CSS.

## Features

✅ React 18 with TypeScript
✅ Vite for fast development
✅ Tailwind CSS for styling
✅ React Router for navigation
✅ Zustand for state management
✅ Axios for API calls
✅ React Hot Toast for notifications
✅ Responsive design

## Quick Start

```bash
cd web-app

# Install dependencies
npm install

# Start development server
npm run dev

# Expected: Open http://localhost:5173
```

## Available Scripts

```bash
# Development server
npm run dev

# Build for production
npm run build

# Preview production build
npm preview

# Type checking
npm run type-check

# Linting
npm run lint
```

## Project Structure

```
web-app/
├── src/
│   ├── pages/
│   │   ├── SplashScreen.tsx
│   │   ├── HomePage.tsx
│   │   ├── ProfilePage.tsx
│   │   └── auth/
│   │       ├── LoginPage.tsx
│   │       └── RegisterPage.tsx
│   ├── components/
│   │   └── Layout.tsx
│   ├── services/
│   │   └── api.ts
│   ├── store/
│   │   └── authStore.ts
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
├── public/
├── package.json
├── vite.config.ts
├── tsconfig.json
├── tailwind.config.js
└── postcss.config.js
```

## API Integration

The app connects to the NestJS backend at `http://localhost:3000`

Update `src/services/api.ts` if your backend URL is different:

```typescript
const API_BASE_URL = 'http://your-backend-url:3000';
```

## Building for Production

```bash
npm run build

# Output will be in dist/
```

## License

MIT
