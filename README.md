Step 1: Install Dependencies
# Install frontend dependencies
cd front
npm install

# Install backend dependencies
cd ../backend
npm install

Step 2: Setup at the Root Level
# Go to root folder (if not already)
cd ..

# Install dev dependency to run both frontend and backend concurrently
npm install concurrently --save-dev

Step 3: Start the Project
npm start

What Happens
When you run npm start in root folder it will:

 Start the Backend Server from backend/server.js

 Start the Frontend (Vite) from the front folder
