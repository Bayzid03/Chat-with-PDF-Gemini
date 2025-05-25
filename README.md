# Chat with PDF using Gemini

This Streamlit app allows you to upload PDF files and interactively ask questions about their content using Google's Gemini model and LangChain.

## Features

- Upload multiple PDF files
- Extracts and chunks PDF text
- Embeds and indexes content using FAISS and Google Generative AI Embeddings
- Conversational Q&A with Gemini LLM
- Simple Streamlit UI

## Setup

1. **Clone the repository**

   <https://github.com/Bayzid03/Chat-with-PDF-Gemini>

2. **Install dependencies**

   ```sh
   pip install -r requirements.txt
   ```

3. **Set up your environment variables**

   - Create a `.env` file in the project root with your Google API key:

     ```
     GOOGLE_API_KEY=your_google_api_key_here
     ```

4. **Run the app**

   ```sh
   streamlit run app.py
   ```

## Usage

- Upload one or more PDF files using the sidebar.
- Click "Submit & Process" to index the documents.
- Ask questions in the main input box.

## Requirements

See [requirements.txt](requirements.txt).

## Notes

- Your Google API key is required for embedding and LLM features.

---

## License

MIT License
