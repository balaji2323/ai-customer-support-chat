# AI Customer Support Chat

## Project Description

An AI-powered customer support chat application with a React frontend and a Node.js backend. The backend serves the frontend's static files and handles API requests.

## Technologies Used

- React (Frontend)
- Node.js with Express (Backend)
- MongoDB for database
- OpenAI API for AI chat functionality

## Project Structure

project_root/
├── backend/ # Node.js backend + frontend build served here
│ ├── build/ # React production build files
│ ├── controllers/
│ ├── routes/
│ ├── server.js
│ └── package.json
└── frontend/ # React frontend source code
├── src/
└── public/

text

## Installation

### Install backend dependencies

cd backend
npm install

text

### Install frontend dependencies

cd ../frontend
npm install

text

## Running Locally

Start backend:

cd backend
npm run dev

text

Start frontend:

cd ../frontend
npm start

text

## Build Frontend for Production

cd frontend
npm run build

Copy or move the generated `build` folder into the backend directory.

## Deployment

- Backend serves the React static files from the copied `build` folder.
- Deploy the backend folder (which includes React build) to services like Render, Railway, or Heroku.
- Set environment variables for server configuration and API keys.

## Environment Variables

Create a `.env` file inside `backend` folder with:

PORT=5000
MONGODB_URI=your_mongodb_connection_string
OPENAI_API_KEY=your_openai_api_key
JWT_SECRET=your_jwt_secret_key

text

## Usage

Visit the deployed backend URL to use the AI Customer Support Chat app.

## License

MIT License

## Author

Your Name (your.email@example.com)