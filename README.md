🎙️ Voice Chatbot using Groq API (Whisper + DeepSeek)
This is a voice chatbot application that integrates Groq API for:
Speech-to-Text (Whisper Large-v3)
AI Responses 
Supports English & Urdu Transcriptions
Record or Upload Audio Files

Setup Instructions

Clone the Repository
git clone https://github.com/your-username/your-repo.git
cd your-repo


Install Dependencies
Backend (Node.js)
cd server
npm install


Frontend (React)
cd client
npm install


API Key Setup
Create a .env file inside the server folder.
Add the following line:

GROQ_API_KEY=your_groq_api_key_here
Don't share your API key! Keep it private.
Running the Application


Start the Backend (Node.js)

cd server
node server.js
This will start the backend at http://localhost:5000/.

Start the Frontend (React)

cd client
npm start


Now, open your browser and go to http://localhost:3000/.

Features:
Record or Upload Audio
Click Record 🎤 to start recording.
Click Stop Recording to transcribe.
OR upload an audio file (mp3, wav, ogg, webm supported).
Choose Language (English or Urdu)
Select English or Urdu before recording.
Get AI Response
Click Send to get an AI response from AI.
❓ Troubleshooting
🔹 API Key Issues?

Check .env file inside server/ folder.
Restart the server after updating the key.
Audio Not Transcribing?
Ensure the file format is supported (mp3, wav, ogg, webm).

Open to contributions! Submit a pull request.
📜 License
This project is MIT Licensed. Feel free to modify and improve it! 🚀
