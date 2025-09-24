# Sustainable E-commerce Platform

An AI-powered sustainable shopping platform that helps users make eco-friendly purchasing decisions through machine learning and conversational AI.

## Features

- **Product Catalog**: Browse products with eco-friendly ratings
- **AI Chat Assistant**: Get sustainability advice and product recommendations
- **ML Predictions**: Automatic eco-friendliness classification
- **Smart Recommendations**: Find sustainable alternatives
- **Responsive Design**: Works on all devices

## Tech Stack

- **Frontend**: React + TypeScript + Vite + Tailwind CSS
- **Backend**: Flask + Python + Pandas + Scikit-learn
- **AI**: Groq LLM + NLTK + TF-IDF + Logistic Regression
- **Data**: CSV-based product database

## Quick Start

### 1. Frontend (Port 5173)
```bash
cd frontend
npm install
npm run dev
```

### 2. Backend (Port 5001)
```bash
cd backend
pip install -r requirements.txt
python app.py
```

### 3. AI Assistant (Port 5002)
```bash
cd assistant_service
pip install -r requirements.txt
python app.py
```

## Project Structure

```
├── frontend/          # React TypeScript app
├── backend/           # Flask API server
├── assistant_service/ # AI chat service
├── ml_models/         # Machine learning models
└── README.md
```

## API Endpoints

- `GET /api/health` - Health check
- `GET /api/products` - Get all products
- `POST /api/predict` - Predict eco-friendliness
- `POST /api/recommend` - Get recommendations
- `POST /api/ai/chat` - AI chat interface

## Environment Setup

Create `.env` file in `assistant_service/`:
```
GROQ_API_KEY=your_groq_api_key_here
```

## License

MIT License# Eco_market
