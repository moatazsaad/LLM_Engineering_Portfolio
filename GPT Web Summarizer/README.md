# 🌐 Website Summarizer  

## 📌 Overview  
**Website Summarizer** is a tool that extracts and summarizes web page content using **OpenAI's GPT models**. It supports multiple summary formats, making it ideal for quickly understanding website content.  

### ✨ Features  
- ✅ **Extracts website content** while removing unnecessary elements like scripts and images.  
- ✅ **Utilizes OpenAI's GPT model** for intelligent text summarization.  
- ✅ **Three summary styles**:  
  - **Key Points**: Bullet-point summary.  
  - **Detailed**: In-depth explanation.  
  - **Q&A**: Conversational format.  
- ✅ **Works in Jupyter Notebook** for easy interaction.  

---

## 🚀 Installation  

### Prerequisites  
Ensure you have the following installed:  
- Python 3.x  
- pip  

### Setup  
1. **Clone the repository:**  
   ```sh
   git clone https://github.com/moatazsaad/website-summarizer.git  
   cd website-summarizer  
   ```  
2. **Install dependencies:**  
   ```sh
   pip install -r requirements.txt  
   ```  
3. **Set up OpenAI API key:**  
   - Create a `.env` file in the project directory.  
   - Add the following:  
     ```sh
     OPENAI_API_KEY=your_openai_api_key_here  
     ```  

---

## 🎯 Usage  

### 🔹 Running in Jupyter Notebook  
1. Open the Jupyter Notebook:  
   ```sh
   jupyter notebook "GPT Web Summarizer.ipynb"  
   ```  
2. Run the notebook cells in order to initialize the summarization tool.  
3. Use the function:  
   ```python
   display_summary('https://www.nytimes.com/', 'Key Points')  
   ```  

---

## 🛠 Technologies Used  
- **Python**  
- **OpenAI GPT**  
- **BeautifulSoup** (for web scraping)  
- **Requests** (for fetching web pages)  
- **Dotenv** (for API key management)  

---

## 📌 Example Output  
For the URL `https://www.nytimes.com/` with the **Detailed** style:

### **Detailed Summary of The New York Times Website**  

The **New York Times (NYT)** serves as a comprehensive source of news and information, covering topics such as U.S. and international news, politics, business, technology, arts, and lifestyle.  

#### Main Sections:  
- **U.S. News:** Coverage on politics, education, health, and climate.  
- **World News:** Updates from Africa, the Americas, Asia, and Europe.  
- **Business:** Stock market trends, technology impacts, and finance.  
- **Arts & Lifestyle:** Literature, music, food, and travel.  

#### Newsletter & Podcast Offerings:  
- **The Morning:** A daily news briefing.  
- **The Interpreter:** Weekly analysis of global events.  

#### Multimedia & Special Reports:  
- **Video content & Interactive articles** for engaging storytelling.  
- **Investigative journalism** uncovering social and political issues.  

#### Opinion & Culture:  
- **Columns and guest essays** on major global topics.  
- **Cultural critiques, book reviews, and lifestyle recommendations.**  

#### Subscription Model:  
NYT operates on a **subscription-based model**, offering exclusive articles, podcasts, and multimedia content.  
