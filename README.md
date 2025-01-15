# 🕸️ Web Scraper for Company Brochures

This project is a **Python-based web scraper** that extracts relevant company information from a website and generates a **brochure-style summary** using OpenAI's GPT-4o-mini model. The tool fetches links from a company's webpage, identifies relevant sections (e.g., About, Careers), and presents a **structured markdown document** suitable for **prospective customers, investors, and job seekers**.

---

## 🚀 Features
✅ **Web Scraping** – Uses `requests` and `BeautifulSoup` to extract webpage content.  
✅ **Intelligent Link Filtering** – Identifies relevant company pages for inclusion.  
✅ **AI-Powered Content Generation** – Uses OpenAI API to generate brochure text.  
✅ **Markdown Formatting** – Outputs structured markdown content.  
✅ **Streamed AI Response** – Displays AI-generated content dynamically.  

---

## 📌 Prerequisites
Before running the project, ensure you have the following installed:

- **Python 3.8+**
- **An OpenAI API Key**
- Required Python libraries (install using `pip install -r requirements.txt`)

---

## 📥 Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
pip install -r requirements.txt
