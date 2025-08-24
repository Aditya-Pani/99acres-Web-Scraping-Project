# 🏠 99acres Web Scraping – Chennai Real Estate Data

This project focuses on scraping real estate listings from **99acres.com** to collect property data for **Chennai**. The data is cleaned, structured, and exported as a CSV file for analysis.  

---

## 📊 Key Features

### 🔍 Web Scraping
- Extracted property listings directly from **99acres.com**.
- Captured the following fields:
  - `name` – Property name/project name  
  - `location` – Locality within Chennai  
  - `price_in_lakhs` – Property price converted into lakhs  
  - `area_in_sqft` – Area of the property in square feet  
  - `bhk` – Number of bedrooms  
  - `has_rating` – Indicator if a property has ratings (1 = Yes, 0 = No)  

### 🗂️ Data Cleaning
- Converted prices into a **consistent lakh unit**.  
- Cleaned property names and standardized columns.  
- Removed missing or incomplete rows.  

---

## 📁 Project Files
- **`99acres Web Scraping Project.ipynb`** – Jupyter Notebook containing scraping and cleaning code.  
- **`chennai_properties-99acres.csv`** – Final cleaned dataset.  
- **`README.md`** – Documentation file.  

---

## 📈 Sample Dataset Snapshot
| name             | location   | price_in_lakhs | area_in_sqft | bhk | has_rating |
|------------------|-----------|----------------|--------------|-----|------------|
| happy homes      | kolathur  | 85.83          | 1162         | 3   | 0          |
| snd sai swaraj   | velachery | 105            | 1400         | 3   | 0          |
| prince courtyard | egmore    | 443            | 2110         | 3   | 0          |

---

## 📊 Insights Possible
- **Price distribution** of properties across Chennai.  
- **Location-wise comparison** of property prices.  
- **Area vs. Price analysis** (cost per sq.ft).  
- Identification of **affordable vs. premium zones**.  

---

## 🛠 Tools & Libraries Used
- **Python**  
  - `BeautifulSoup` (web scraping)  
  - `Requests` (HTTP requests)  
  - `Pandas` (data cleaning & storage)  
- **Jupyter Notebook** for implementation  
- **CSV** for storing structured dataset  

---

## ⭐ Future Enhancements
- Scrape multiple cities beyond Chennai.  
- Automate daily/weekly scraping with scheduling.  
- Add **Power BI / Tableau dashboards** for visual insights.  
- Build a **web app** (Flask/Django) for property search.  

---

## 📢 Note
- This project is built for **educational and research purposes only**.  
- Always review a website’s **robots.txt** and **terms of service** before scraping.  

---

⭐ If you find this project useful, don’t forget to **star the repository** on GitHub!
