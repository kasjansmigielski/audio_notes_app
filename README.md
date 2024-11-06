### Application description:
The goal of the project was to create the AI-powered application, used to record voice notes, transcribe them into text and finally enable saving notes in the QDrant vector database and their semantic search. To do this, I used two LLM models from OpenAI: `whisper-1` (speech -> text) and `text-embeddings-3-large` (text -> embeddings).

### Main functionalities:
* recording and listening to voice notes,
* transcription of voices into text using AI,
* ability to collect notes in the QDrant database,
* semantic data search, using the text processing algorithm on embeddings and finding similarities based on Cosinus Similarity.

### Dependencies:
* openai,
* python-dotenv,
* streamlit-audiorecorder,
* streamlit,
* qdrant-client,
* pydub.

### Result:
The application is publicly deployed at the link: https://audio-notes.streamlit.app/<br>
To use it, an OpenAI API key is required.
