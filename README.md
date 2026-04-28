# frontend
 AI-First CRM HCP Module – Log {
  "name": "hcp-crm-frontend",
  "version": "1.0.0",
  "private": true,
  "type": "module",
  "scripts": {
    "dev":     "vite",
    "build":   "vite build",
    "preview": "vite preview"
  },
  "dependencies": {
    "react":     "^18.3.1",
    "react-dom": "^18.3.1"
  },
  "devDependencies": {
    "@vitejs/plugin-react": "^4.3.1",
    "vite": "^5.4.1"
  }
}Interaction Screen

backend

{
  "name": "hcp-crm-backend",
  "version": "1.0.0",
  "description": "MedPulse CRM – HCP Module API",
  "main": "server.js",
  "type": "commonjs",
  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js"
  },
  "dependencies": {
    "better-sqlite3": "^9.4.3",
    "cors": "^2.8.5",
    "express": "^4.18.3",
    "express-validator": "^7.0.1"
  },
  "devDependencies": {
    "nodemon": "^3.1.0"
  }
}
