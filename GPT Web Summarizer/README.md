# Website Summarizer

## Overview
This project is a **Website Summarizer** that extracts and summarizes content from web pages using **OpenAI's GPT models**. It provides different summarization styles such as:
- **Key Points**: A concise bullet-point summary.
- **Detailed**: A more in-depth summary.
- **Q&A**: A question-answer format.

The summarization process is powered by OpenAI's API and is accessible via a **Jupyter Notebook** interface.

## Features
- **Extracts text content** from web pages, removing unnecessary elements like scripts and images.
- **Utilizes OpenAI's GPT model** to generate structured summaries.
- **Supports multiple summary styles** for different user preferences.
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
1. Open the Jupyter Notebook:
   ```sh
   jupyter notebook "GPT Web Summarizer.ipynb"
   ```
2. Run the notebook cells in order to initialize the summarization tool.
3. Use the `display_summary()` function in a code cell:
   ```python
   display_summary('https://www.nytimes.com/', 'Key Points')
   ```

## Technologies Used
- **Python**
- **OpenAI GPT**
- **BeautifulSoup** (for web scraping)
- **Requests** (for fetching web pages)
- **Dotenv** (for API key management)

## Example Output
For the URL `https://www.nytimes.com/` with the **Detailed** style:

## Detailed Summary of The New York Times Website  

The New York Times (NYT) serves as a comprehensive source of news and information, covering topics such as U.S. and international news, politics, business, technology, arts, and lifestyle.  

### 📰 Main Sections:  
- **U.S. News:** Coverage on politics, education, health, and climate.  
- **World News:** Updates from Africa, the Americas, Asia, and Europe.  
- **Business:** Stock market trends, technology impacts, and finance.  
- **Arts & Lifestyle:** Literature, music, food, and travel.  

### 🎙️ Newsletter & Podcast Offerings:  
- **The Morning:** A daily news briefing.  
- **The Interpreter:** Weekly analysis of global events.  

### 🎥 Multimedia & Special Reports:  
- **Video content & Interactive articles** for engaging storytelling.  
- **Investigative journalism** uncovering social and political issues.  

### 🎭 Opinion & Culture:  
- **Columns and guest essays** on major global topics.  
- **Cultural critiques, book reviews, and lifestyle recommendations.**  

### 💡 Subscription Model:  
NYT operates on a **subscription-based model**, offering exclusive articles, podcasts, and multimedia content.  

**Conclusion:**  
The New York Times remains a leading source for reliable journalism, in-depth reports, and diverse content offerings.  
