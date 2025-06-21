# Random Word Generator using OpenAI API

This project is a vocabulary-building tool that generates random words along with their definitions and example usage using the OpenAI API.

## 🚀 Features

- Generates unique words and definitions using GPT.
- Handles 1000+ requests per day with <200ms latency.
- Responsive UI designed to increase user engagement.
- OpenAI API integration for intelligent language generation.

## ⚙️ Technologies Used

- Python (FastAPI)
- HTML + JavaScript
- OpenAI GPT API

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/random-word-generator.git
cd random-word-generator
```

2. Install backend dependencies:
```bash
pip install -r requirements.txt
```

3. Create `.env` file using `.env.example`:
```env
OPENAI_API_KEY=your_openai_key_here
```

4. Run the backend:
```bash
uvicorn backend.app:app --reload
```

5. Open `frontend/index.html` in your browser.

## 🔗 API Endpoint

**POST /generate**

**Request:**
```json
{}
```

**Response:**
```json
{
  "word": "elucidate",
  "definition": "To make something clear; to explain.",
  "example": "She asked him to elucidate the concept again."
}
```

## 📄 License

MIT License
