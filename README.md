# Website Text Summarization

This Streamlit application generates concise summaries of webpage content from a given URL, using the **Groq** language model (Gemma-7b-It).

## Features

- **URL Validation**: Ensures valid URLs are entered.
- **Web Scraping**: Fetches webpage content via `requests` and `BeautifulSoup`.
- **AI-Powered Summarization**: Uses the Groq API (Gemma-7b-It model) for generating summaries.
- **Intuitive Interface**: Built with Streamlit for easy use.
- **Error Handling**: Provides clear feedback on invalid URLs or content retrieval failures.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/shrchrds/Website-Text-Summarization.git
   cd Website-Text-Summarization


2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate```  # On Windows use `venv\Scripts\activate`

3. Install the required packages:
    ```bash
    pip install -r requirements.txt

4. Set up environment variables:
    - Create a .env file in the root directory.
    - Add your Groq API key:
    ```GROQ_API_KEY=your_groq_api_key_here```

# Usage
1. Run the Streamlit app:
        ```streamlit run app.py```
2. Enter a URL:
    Input the URL of the webpage you want to summarize in the text input field.
3. Summarize:
    Click the "Summarize the Content from Website" button to generate a summary.
