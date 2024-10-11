# Summarize Text From Website

This project is a Streamlit application designed to summarize text content from a given website URL using a language model API called Groq. The application fetches the content from the specified webpage and generates a concise summary using a language model.

## Features

- **URL Validation**: Ensures that the user inputs a valid URL.
- **Web Scraping**: Retrieves webpage content using `requests` and `BeautifulSoup`.
- **Language Model Integration**: Utilizes the Groq API with the Gemma-7b-It model for text summarization.
- **User-Friendly Interface**: Built with Streamlit for easy interaction.
- **Error Handling**: Provides feedback and error messages for invalid URLs or failed content retrieval.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/yourproject.git
   cd yourproject```

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

5. Usage
    i. Run the Streamlit app:
        ```streamlit run app.py```
    ii. Enter a URL:
        Input the URL of the webpage you want to summarize in the text input field.
    iii. Summarize:
        Click the "Summarize the Content from Website" button to generate a summary.
