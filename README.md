# EdexLab - AI-Powered Learning Platform

An intelligent, personalized learning platform that adapts to each student's needs and learning style.

## Features

- **Personalized Learning Paths**: AI-driven curriculum adaptation
- **Interactive Learning Modules**: Engaging content for Math, Science, and English
- **Real-time Progress Tracking**: Continuous monitoring and analytics
- **AI Tutoring**: Intelligent doubt clearing and support
- **Parent Dashboard**: Comprehensive progress monitoring
- **Adaptive Assessments**: Dynamic difficulty adjustment

## Project Structure

```
edex-lab/
├── frontend/          # Next.js frontend application
├── backend/           # Node.js/Express API server
├── ai-services/       # Python-based AI/ML services
└── docs/             # Project documentation
```

## Tech Stack

- **Frontend**: Next.js, React, TypeScript
- **Backend**: Node.js, Express, PostgreSQL
- **AI/ML**: Python, TensorFlow/PyTorch
- **Real-time**: WebSocket
- **Authentication**: JWT, OAuth2

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- Python (v3.9 or higher)
- PostgreSQL (v14 or higher)
- Docker (optional)

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   # Frontend
   cd frontend
   npm install

   # Backend
   cd ../backend
   npm install

   # AI Services
   cd ../ai-services
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   ```

4. Start the development servers:
   ```bash
   # Frontend
   cd frontend
   npm run dev

   # Backend
   cd ../backend
   npm run dev

   # AI Services
   cd ../ai-services
   python main.py
   ```

## Contributing

Please read [CONTRIBUTING.md](docs/CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 