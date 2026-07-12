# 📱 Flipkart 5G Mobile Web Scraping Pipeline

## 📌 Overview

This project automates the extraction of **5G mobile phone listings under ₹50,000** from Flipkart using Python.

The scraper collects product information across multiple pages and exports the cleaned dataset into a CSV file for further analysis.

---

# 🎯 Business Problem

An e-commerce analytics company wants to monitor competitor pricing, product specifications, and customer reviews to better understand market trends and improve business decisions.

---

# 🚀 Features

- Multi-page web scraping
- Automated HTTP requests
- HTML parsing using BeautifulSoup
- Product information extraction
- Data cleaning with Pandas
- CSV export

---

# 🛠 Technologies Used

- Python
- Requests
- BeautifulSoup
- lxml
- Pandas

---

# 📊 Extracted Data

- Product Name
- Price
- Technical Specifications
- Customer Reviews

---

# 🔄 Workflow

```
Flipkart Website
        │
        ▼
HTTP Requests
        │
        ▼
BeautifulSoup Parser
        │
        ▼
Extract Product Details
        │
        ▼
Pandas DataFrame
        │
        ▼
CSV Export
```

---

# 📁 Folder Structure

```
01_Flipkart_Web_Scraping/
│
├── README.md
├── flipkart_scraper.py
├── Flipkart_Pipeline_Business_Problem.pdf
├── Flipkart_5G_Mobile_Under_50000.csv
├── requirements.txt
└── images/
```

---

# ▶️ Installation

```bash
pip install -r requirements.txt
```

Run the scraper:

```bash
python flipkart_scraper.py
```

---

# 📂 Output

The scraper generates:

```
Flipkart_5G_Mobile_Under_50000.csv
```

containing product information collected from multiple Flipkart search result pages.

---

# 📈 Skills Demonstrated

- Web Scraping
- Data Collection
- HTML Parsing
- Data Cleaning
- Data Processing
- CSV Export
- Python Automation

---

# 🚀 Future Improvements

- Retry mechanism
- Exception handling
- Logging
- Database integration
- Automated scheduling

