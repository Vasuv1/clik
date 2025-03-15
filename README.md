# Admin Clik

A mobile app built with Capacitor for managing e-commerce operations.

## Features

- User Authentication
- Product Management
- Order Management
- Cart System
- Favorites System
- Shipping Management
- Promotions Management

## Tech Stack

- Frontend: React + Vite + TypeScript
- Backend: Node.js + Express
- Database: MongoDB
- Mobile: Capacitor
- State Management: React Query

## Setup

1. Install dependencies:
   ```bash
   npm install
   cd full && npm install
   ```

2. Set up environment variables:
   Create `.env` file in root and add:
   ```
   PORT=3001
   MONGODB_URI=your_mongodb_uri
   NODE_ENV=development
   ```

   Create `.env` file in `full/client` and add:
   ```
   VITE_API_BASE_URL=http://localhost:3001
   ```

3. Run development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

5. Build mobile app:
   ```bash
   npx cap sync
   npx cap open android
   ```

## Deployment

The app is deployed on Render.com:
- Backend: https://admin-clik-backend.onrender.com
- Frontend: https://admin-clik-frontend.onrender.com

## License

MIT 