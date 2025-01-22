# BDR_Automation
To set up an ai agent to receive calls, qualify and set up a meeting. 
# Tools and Libraries Summary (Including Your Decisions)
Vector Database: Pinecone (Chosen for storing and querying vector embeddings).

Speech-to-Text (STT): Google Speech-to-Text (Chosen for real-time transcription accuracy).

Text-to-Speech (TTS): ElevenLabs (Chosen for high-quality, customizable voice synthesis).

AI Framework: LangChain (For conversational flow and integration with vector database) and OpenAI GPT API (For LLM-powered text generation).

Telephony: Twilio (For handling phone calls and audio streaming).

Backend Development: FastAPI (For efficient, lightweight API creation and real-time call processing).

Model Optimization: Hugging Face Transformers (For managing LLMs) and Sentence Transformers (For embedding generation).
ai-bdr-project/
├── backend/               # Backend code (e.g., FastAPI scripts)
├── data/                  # Annotated and processed datasets
├── embeddings/            # Preprocessed embeddings
├── models/                # Model scripts and configurations
├── telephony/             # Twilio integration code
├── tests/                 # Unit and integration tests
├── scripts/               # Helper scripts (e.g., embedding generation)
├── requirements.txt       # Python dependencies
└── README.md              # Project overview
