# AI-Powered Data Visualization & Analytics Platform

## Overview
This project is an AI-powered data visualization and analytics platform that enables users to upload data, generate interactive visualizations, and gain AI-driven insights.

## Features
- Upload Excel files or manually input data.
- Generate interactive 2D & 3D graphs.
- AI-powered insights based on the uploaded data.
- User-friendly dashboard with real-time updates.

## Tech Stack
### Frontend
- React.js
- Redux Toolkit
- TailwindCSS
- Chart.js, Three.js

### Backend
- Node.js
- Express.js
- MongoDB (MongoDB Atlas)
- WebSockets (Socket.io)
- JWT/OAuth (Google Login) for authentication

### AI Module
- Python (Flask or FastAPI) for AI-based insights

### Deployment
- Vercel (Frontend)
- AWS/Render (Backend)
- MongoDB Atlas (Database)

## Installation & Setup
### Prerequisites
- Node.js and npm installed
- Python (if running AI module locally)

### Steps
#### 1. Clone the Repository
```sh
 git clone https://github.com/Shivamupadhyay09/AI-powered-data-visualization-analytics.git
 cd AI-powered-data-visualization-analytics
```

#### 2. Install Dependencies
##### Frontend
```sh
 cd frontend
 npm install
 npm run dev
```
##### Backend
```sh
 cd backend
 npm install
 npm start
```
##### AI Module (Optional, if running locally)
```sh
 cd ai_module
 pip install -r requirements.txt
 python main.py
```

## Usage
1. Upload a dataset (Excel or manual entry)
2. Choose visualization type (Bar, Line, Pie, 3D models, etc.)
3. View AI-powered insights and trends
4. Download or share the visualizations

## API Endpoints
- `POST /upload` - Upload dataset
- `GET /visualize` - Fetch visualizations
- `GET /insights` - AI-generated insights

## Contribution
Feel free to fork this repository and contribute via pull requests.

## License
MIT License
