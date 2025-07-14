# 📚 Publication Summary Generator for Faculty Profiles

An AI-powered system developed by **Utkarsh Singh** that automates the extraction, enrichment, and visualization of publication records for faculty profiles. This tool scrapes data from Google Scholar and other academic databases like Scopus and CrossRef, providing customizable outputs in Excel/CSV format along with citation analysis and indexing status.

---

## 🚀 Features

### 👤 Faculty Profile Support
- Scrapes and fetches publication data using author profile URLs (Google Scholar, Scopus).
- Extracts metadata including title, authors, journal, year, citations, and indexing.
- Detects journal/conference indexing (e.g., Scopus) and alerts if data is missing.
- H-index calculation and customizable filtering (by year, index, author, etc.)

### 📊 Data Analysis & Export
- Provides citation distribution analysis via interactive visualizations.
- Generates downloadable Excel/CSV reports with selected columns.
- Built-in citation count and year-wise trends.

### 🔐 User Access & Security
- Includes login/permission system for secure access.
- Role-based user dashboard for faculty and admin.

---

## 🛠️ Technologies Used

| Layer       | Technology                                        |
|-------------|---------------------------------------------------|
| Frontend    | HTML5, CSS3, JavaScript (Bootstrap)              |
| Backend     | Python, Django                                    |
| Database    | SQLite / PostgreSQL                               |
| Web Scraping| Scholarly, Selenium, BeautifulSoup, CrossRef API, Scopus API |
| Visualization | Matplotlib, Seaborn                          |
| Others      | Pandas, NumPy, OpenPyXL                           |

---

## 📥 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/Anoymous786/-Publication-Summary-Generator.git
cd Publication-Summary-Generator

# Create virtual environment
python -m venv venv
# Activate it
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the server
python manage.py runserver
```

Visit: [http://localhost:8000](http://localhost:8000)

---

## ✍️ Author

**Utkarsh Singh**  
GitHub: [Anoymous786](https://github.com/Anoymous786)  
Email: [utsi22ise@cmrit.ac.in](mailto:utsi22ise@cmrit.ac.in)  
LinkedIn: [linkedin.com/in/utkarsh746](https://www.linkedin.com/in/utkarsh746)

---

## 📄 License

MIT License

---

> ✅ This project is authored and maintained by Utkarsh Singh and is aligned with backend-focused job roles. It demonstrates proficiency in Python, Django, web scraping, secure role-based access, and academic data automation.
