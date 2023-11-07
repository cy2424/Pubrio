# Pubrio Assessment: Company Information Extractor

This Python script automatically extracts company names and domains from text content. It is specifically designed to process text content, such as HTML that has been scraped from TechCrunch articles. The script utilizes OpenAI's GPT model to identify related companies mentioned within the article and extracts the main topic of the article as well.

## Features

- Extracts company names and domains from pre-scraped text content.
- Identifies the main topic of the article.
- Outputs the extracted information in a structured JSON format.

## Requirements

- Python 3.6 or later
- `streamlit` for creating the web application interface
- `openai` for accessing the OpenAI GPT API
- An OpenAI API key


## Usage

Before running the application, you will need to replace the placeholder in the application code with your actual OpenAI API key.

To run the Streamlit application:

```bash
streamlit run "path name\Pubrio.py"
```

Open your web browser and go to `localhost:8501` to interact with the application.

## Configuration

To use the script, you will need an API key from OpenAI. Replace `'your-api-key'` in the code with your actual OpenAI API key.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.

