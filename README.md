# Vocabulary Learning App

A comprehensive vocabulary learning application that helps users improve their English vocabulary through intelligent word detection, flashcards, and spaced repetition.

## Features

- Vocabulary size testing
- Document parsing (HTML/EPUB/PDF)
- Smart word detection
- Interactive flashcards
- Spaced repetition system
- Learning statistics and analytics

## Tech Stack

- Frontend: React.js, Next.js, TailwindCSS
- Backend: Node.js/Express.js, Python
- Database: MongoDB
- Cache: Redis

## Project Structure

```
vocabulary-app/
├── client/                # Frontend React application
├── server/               # Backend Node.js/Express application
├── python_services/      # Python services for document processing
└── docker-compose.yml    # Docker compose configuration
```

## Getting Started

### Prerequisites

- Node.js >= 16
- Python >= 3.8
- MongoDB
- Redis

### Installation

1. Clone the repository
```bash
git clone https://github.com/[your-username]/vocabulary-app.git
cd vocabulary-app
```

2. Install dependencies
```bash
# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install

# Install Python dependencies
cd ../python_services
pip install -r requirements.txt
```

## Development

```bash
# Start frontend development server
cd client
npm run dev

# Start backend server
cd ../server
npm run dev

# Start Python services
cd ../python_services
python -m uvicorn main:app --reload
```

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
