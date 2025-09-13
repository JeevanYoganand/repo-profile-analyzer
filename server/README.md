# Server Directory

This directory contains the backend application for the Repository Profile Analyzer.

## Structure

- `src/` - Main source code directory
- `routes/` - API route definitions
- `models/` - Data models and schemas
- `package.json` - Node.js dependencies and scripts (if using Node.js)
- `requirements.txt` - Python dependencies (if using Python/FastAPI)

## Technology Options

### Option 1: Node.js with Express.js
- Express.js framework
- Node.js runtime
- npm package management

### Option 2: Python with FastAPI
- FastAPI framework
- Python runtime
- pip package management

## Getting Started

### For Node.js/Express:

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

### For Python/FastAPI:

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Start the development server:
   ```bash
   uvicorn main:app --reload
   ```

## Features

- RESTful API endpoints
- GitHub, GitLab, and Bitbucket API integration
- Data processing and analysis
- Report generation
- Export functionality
- Authentication and authorization

## API Endpoints

- `/api/analyze/repository` - Analyze a repository
- `/api/analyze/profile` - Analyze a user profile
- `/api/reports` - Generate and retrieve reports
- `/api/export` - Export analysis data
