# Website Summarizer

## Overview
This project is a **Website Summarizer** that extracts and summarizes content from web pages using **OpenAI's GPT models**. It provides different summarization styles such as:
- **Key Points**: A concise bullet-point summary.
- **Detailed**: A more in-depth summary.
- **Q&A**: A question-answer format.

The summarization process is powered by OpenAI's API and is accessible via a **Gradio web interface**.

## Features
- **Extracts text content** from web pages, removing unnecessary elements like scripts and images.
- **Utilizes OpenAI's GPT model** to generate structured summaries.
- **Supports multiple summary styles** for different user preferences.
- **Gradio-based UI** for easy interaction.
- **Markdown formatted output** for better readability.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- pip

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/moatazsaad/website-summarizer.git
   cd website-summarizer
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Set up your OpenAI API key:
   - Create a `.env` file in the project directory.
   - Add the following line:
     ```sh
     OPENAI_API_KEY=your_openai_api_key_here
     ```

## Usage
### Running in Jupyter Notebook
You can use the `display_summary()` function directly in a Jupyter Notebook:
```python
from summarizer import display_summary

display_summary('https://www.nytimes.com/', 'Key Points')
```

### Running the Gradio Web App
Start the web interface by running:
```sh
python app.py
```
This will launch a local server. Open the provided URL in a browser to use the summarization tool.

## Technologies Used
- **Python**
- **OpenAI GPT**
- **Gradio** (for UI)
- **BeautifulSoup** (for web scraping)
- **Requests** (for fetching web pages)
- **Dotenv** (for API key management)

## Example Output
For the URL `https://www.nytimes.com/` with the **Key Points** style:

### Key Points
- **U.S. News**: Covers politics, health, climate, and sports.
- **World News**: International updates across multiple regions.
- **Business & Tech**: Financial and technological developments.
- **Opinion & Lifestyle**: Editorials, travel, arts, and entertainment.

