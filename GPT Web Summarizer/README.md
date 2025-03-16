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
   display_summary('https://www.nytimes.com/', 'Detailed')  
   ```  

---

## 🛠 Technologies Used  
- **Python**  
- **OpenAI GPT**  
- **BeautifulSoup** (for web scraping)  
- **Requests** (for fetching web pages)  
- **Dotenv** (for API key management)
- **Gradio** (for web-based UI)  

---

## 📌 Example Output  
For the URL `https://www.nytimes.com/` with the **Detailed** style:

### **Summary of The New York Times Website**
#### **Overview**
The New York Times (NYT) is an established American newspaper that provides comprehensive coverage of national and international news, as well as various other categories including politics, business, arts, lifestyle, opinion, and more. The website is known for its in-depth reporting, analyses, and inspirational storytelling.

#### **Key Sections of the Website**
- **U.S. News**: Covers local news, politics, education, health, and sports.
- **World News**: Reports on global issues, including international relations, crises, and culture in various regions.
- **Business**: Focuses on economics, finance, and technological advancements with sub-sections like DealBook and Your Money.
- **Arts**: Features reviews and articles related to books, music, movies, and pop culture.
- **Lifestyle**: Offers content on health, travel, food, and personal finance, including cooking tips and real estate advice.
- **Opinion**: Includes editorials, guest essays, and columns from notable journalists and thought leaders.
- **Podcasts**: Offers a range of audio content covering news analysis, cultural discussions, and storytelling.
- **Games**: Provides interactive content such as crosswords, word puzzles, and logic games.
- **Cooking**: Features recipes, cooking advice, and meal planning ideas from culinary experts.

#### **Notable Features**
- **Newsletters**: The NYT offers various newsletters to cater to specific interests, including daily news briefings and thematic content.
- **Podcasts**: Prominent programs like *The Daily* provide concise analyses of current events, while others focus on specific topics like technology and literature.
- **Wirecutter**: A product review service that focuses on consumer electronics and other household products.
- **The Athletic**: A sports coverage service providing personalized content about specific leagues and teams.

#### **Current Highlights**
##### **Top Stories**
- **Trade War Impact**: The analysis shows that Trump voters could be significantly affected by new tariffs imposed by other nations.
- **Labor Abuse Investigation**: An in-depth piece investigates the conditions faced by East African maids in Saudi Arabia, highlighting systemic exploitation.
- **Geopolitical Tensions**: Coverage on tensions between Israel and Lebanon and the implications for military recruitments within Israel.
- **Cultural Features**: Articles discussing art, literature, and personal narratives that resonate with audiences.

##### **Recent Headlines**
- **Marco Rubio's statement** on deportations following legal actions.
- **A spotlight on the reactions** to Black Lives Matter mural removal in Washington D.C.
- **Severe weather updates** and their impacts across regions.

#### **Conclusion**
The New York Times serves as a reliable resource for anyone seeking reliable and varied news coverage. Its diverse sections ensure that there is content available for nearly every reader's interest, and its commitment to quality journalism is reflected throughout its extensive offerings.

