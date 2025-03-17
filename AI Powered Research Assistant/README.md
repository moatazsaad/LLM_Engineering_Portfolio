# AI-Powered Research Assistant

This project is an **AI-powered research assistant** that extracts and summarizes key insights from websites and PDFs using **OpenAI's GPT model**. It provides **fact-based summaries, credibility analysis, and trend identification**. The project also includes a **Gradio interface** for easy user interaction.

## Features
- Extracts text from **webpages** and **PDFs**.
- Generates **summaries, key insights, and credibility indicators**.
- Accepts **user queries** for specific insights.
- Uses **OpenAI's GPT model** for natural language processing.
- **Gradio UI** for user-friendly interaction.

## Tech Stack
- **Python**
- **BeautifulSoup** (for web scraping)
- **PyMuPDF** (for PDF text extraction)
- **OpenAI API** (GPT-4o-mini)
- **Gradio** (for the web interface)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/moatazsaad/ai-research-assistant.git
   cd ai-research-assistant
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file and add your OpenAI API key:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

## How to Run
### In Jupyter Notebook
1. Open Jupyter Notebook and run the cells sequentially.
2. To analyze a webpage, use:
   ```python
   display_research("https://www.nytimes.com/")
   ```
3. To analyze a PDF, upload the file and use:
   ```python
   display_research(pdf_path="sample.pdf")
   ```

### Running the Gradio App
If running inside Jupyter Notebook, launch Gradio using:
```python
interface.launch()
```

If running in a script, execute:
```python
python app.py
```

## Example Output
### Website Summary Example
```
## Summary of The New York Times
- Covers U.S. and world news, business, and lifestyle.
- Features opinion articles and multimedia content.
- Recognized for its investigative journalism and credibility.
```

### Gradio Interface Example
The **Gradio interface** allows users to enter a **URL or upload a PDF** and get **instant insights**:
![Gradio UI](screenshot.png)

## Future Improvements
- Add **multi-document summarization**.
- Improve **fact-checking capabilities**.
- Support **more file formats**.
