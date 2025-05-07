# Full-Stack-AI-Voice-Assistant

# Full-Stack AI Voice Assistant

A full-stack web application enabling voice interactions with AI, integrating speech recognition, text-to-speech, and generative AI (Gemini/OpenAI).

##  Features

### AI Pipeline
- **Speech-to-Text (STT)**  
  - Real-time transcription via Web Speech API or Whisper  
- **Text-to-Speech (TTS)**  
  - Configurable engines (Web Speech API, ElevenLabs)  
  - Dynamic prosody adjustments  
- **LLM Integration**  
  - Multi-provider support (Gemini, OpenAI)  
  - Context-aware response generation  

### Interface
- Real-time chat UI with Websockets  
- Session persistence for multi-turn conversations  
- Interactive transcript logging  

##  Tech Stack

**Frontend** : React, Vite, TailwindCSS, Web Speech API 
**Backend** : Django REST Framework, Celery, PostgreSQL
**AI Services** : Gemini API, OpenAI API, Hugging Face API
**Deployment** : Docker, NGINX

## Installation

###  Backend (Django)
1. Clone the repository:
   ```
   git clone https://github.com/topcoder0309/ai-voice-assistant.git
   cd ai-voice-assistant
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install backend dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Add your API key in a `.env` file:
   ```
   GEMINI_API_KEY=your_api_key_here
   OPENAI_API_KEY=your_api_key_here
   ```

5. Run migrations and start the server:
   ```
   python manage.py migrate
   python manage.py runserver
   ```

---

###  Frontend (React)
1. Navigate to the frontend folder:
   ```
   cd frontend
   ```

2. Install frontend dependencies:
   ```
   npm install
   ```

3. Start the React development server:
   ```
   npm run dev
   ```

---