# Code Snippet Search Engine

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Elasticsearch](https://img.shields.io/badge/elasticsearch-8.x-005571)
![License](https://img.shields.io/badge/license-MIT-green)

## Project Overview
Code Snippet Search Engine is a powerful tool for searching, storing, and managing code snippets with syntax highlighting, language detection, and semantic search capabilities powered by Elasticsearch and NLP.

## Tech Stack
- **Frontend**: React.js, TypeScript, Monaco Editor
- **Backend**: Node.js, Express.js, Python
- **Search Engine**: Elasticsearch, Apache Solr
- **Database**: MongoDB, Redis
- **NLP**: spaCy, sentence-transformers
- **Syntax Highlighting**: Prism.js, Highlight.js
- **Testing**: Jest, Cypress, pytest

## Features
- ✅ Semantic code search
- ✅ Syntax highlighting for 100+ languages
- ✅ Automatic language detection
- ✅ Code snippet storage and organization
- ✅ Tags and categories
- ✅ Code similarity detection
- ✅ Advanced search filters
- ✅ Favorites and collections
- ✅ User authentication
- ✅ API for integration
- ✅ Code formatting
- ✅ Export snippets

## Setup Instructions

### Prerequisites
- Node.js 16.x or higher
- Python 3.9+
- Elasticsearch 8.x
- MongoDB
- Redis

### Installation

```bash
# Clone the repository
git clone https://github.com/shithel9360/code-snippet-search-engine.git
cd code-snippet-search-engine

# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install

# Install NLP service dependencies
cd ../nlp-service
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your configurations

# Start Elasticsearch
# Make sure Elasticsearch is running

# Start services
# Terminal 1: Backend
cd backend && npm run dev

# Terminal 2: NLP Service
cd nlp-service && python app.py

# Terminal 3: Frontend
cd frontend && npm start
```

### Running Tests

```bash
# Frontend tests
cd frontend && npm test

# Backend tests
cd backend && npm test

# NLP service tests
cd nlp-service && pytest

# E2E tests
npm run test:e2e
```

## Demo

![Demo GIF Placeholder](https://via.placeholder.com/800x400.png?text=Code+Search+Demo)

## API Documentation

API documentation at `/api/docs`

## Contributing

Contributions welcome! See CONTRIBUTING.md.

## License

MIT License - see LICENSE file for details

## Contact

Shithel - [@shithel9360](https://github.com/shithel9360)
