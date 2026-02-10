# Setup Guide

This guide will help you set up the Meme-Based Concept Explainer project on your local machine.

## Prerequisites

- Node.js (v14 or higher)
- Python (v3.8 or higher)
- Git

## Installation Steps

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/meme-based-concept-explainer.git
cd meme-based-concept-explainer
```

### 2. Set Up Git (If initializing a new repository)

If you're starting fresh with this project:

```bash
git remote add origin https://github.com/YOUR_USERNAME/meme-based-concept-explainer.git
git branch -M main
git push -u origin main
```

### 3. Install Dependencies

#### Frontend Dependencies
```bash
cd frontend
npm install
```

#### Backend Dependencies
```bash
cd ../backend
pip install -r requirements.txt
```

### 4. Environment Configuration

Create a `.env` file in both frontend and backend directories:

**Frontend `.env`:**
```
REACT_APP_API_URL=http://localhost:5000
```

**Backend `.env`:**
```
DATABASE_URL=your_database_url
SECRET_KEY=your_secret_key
```

### 5. Run the Application

#### Start Backend
```bash
cd backend
python app.py
```

#### Start Frontend (in a new terminal)
```bash
cd frontend
npm start
```

The application should now be running at:
- Frontend: http://localhost:3000
- Backend: http://localhost:5000

## Next Steps

- Read [CONTRIBUTING.md](CONTRIBUTING.md) to learn how to contribute
- Check the [README.md](README.md) for project overview
- Start building features!

## Troubleshooting

If you encounter any issues during setup:
1. Ensure all prerequisites are installed correctly
2. Check that all dependencies are installed
3. Verify your `.env` files are configured correctly
4. Check the [Issues](https://github.com/Athithyathirugnanam/meme-based-concept-explainer/issues) page for known problems
