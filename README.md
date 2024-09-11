# Chat with PDF Documents

This project allows users to upload PDF files, extract text from them, split the text into chunks, and create a searchable vector store. Users can then ask questions about the content of the PDF files, and the system will provide answers based on the extracted information.

## Inspiration

This project was inspired by Krish Naik's tutorial on text processing and question answering using document embeddings. His work provided valuable insights into leveraging AI models and vector stores for building intelligent applications.

## Features

- Upload multiple PDF files.
- Process and extract text from PDF files.
- Create a vector store for fast text search.
- Ask questions and get detailed answers based on the content of the PDF files.

## Requirements

- Python 3.10 or above
- Streamlit
- PyPDF2
- LangChain
- Google Generative AI
- FAISS
- `python-dotenv`

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/JenishRevaldo/Chat-with-Document.git
    cd Chat-with-Document
    ```

2. **Create a Virtual Environment (Optional but recommended)**

    ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
    ```

3. **Install the Required Packages**

    ```bash
    pip install -r requirements.txt
    ```


4. **Set Up Environment Variables**

    Create a `.env` file in the root directory of the project with the following content:

    ```plaintext
    GOOGLE_API_KEY=your_google_api_key
    ```

    Replace `your_google_api_key` with your actual Google API key.

## Usage

1. **Run the Streamlit App**

    ```bash
    streamlit run app.py
    ```

    This will open a new tab in your web browser with the Streamlit interface.

2. **Upload PDF Files**

    - Go to the sidebar on the left and use the file uploader to upload your PDF files.
    - Click on "Submit & Process" to extract text and create a vector store.

3. **Ask Questions**

    - Enter your question in the text input field and submit it.
    - The system will return a detailed answer based on the content of the uploaded PDF files.

## Project Structure

- `app.py`: Main script that runs the Streamlit application.
- `requirements.txt`: List of Python dependencies.
- `.env`: Environment variables for API keys.


## Contact

For any questions or feedback, please contact me.
