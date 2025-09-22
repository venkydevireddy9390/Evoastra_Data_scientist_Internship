# 🚗 Cars24 Used Honda Cars Scraper

## 📌 Project Overview
This project focuses on **web scraping used Honda car listings** from the Cars24 platform.  
We extracted, cleaned, and analyzed car listings across **major Indian cities (Delhi-NCR, Bengaluru, and Mumbai)** to generate a structured dataset.  
The dataset was then used to derive **insights about pricing, car age, transmission types, and city-level market trends**. 
<img width="910" height="478" alt="image" src="https://github.com/user-attachments/assets/d76e72bf-11db-4a2a-8203-b70332cd66bf" />


---

## 🎯 Objectives
- Build a **robust scraping pipeline** for dynamic websites.  
- Extract used Honda car listings across multiple cities.  
- Collect key details: **Car Name, Model, Price, Year, KM Driven, Fuel Type, Transmission, Location**.  
- Generate a **final cleaned CSV dataset** for analysis.  
- Perform **exploratory insights** on used car availability and pricing trends.  

---

## 🛠️ Tools & Libraries
- **Python 3.12**  
- **Selenium WebDriver** → Automating browsing, handling dynamic JavaScript content.  
- **BeautifulSoup** → Parsing and extracting HTML content.  
- **Pandas** → Data cleaning, structuring, and exporting to CSV.
- <img width="777" height="398" alt="image" src="https://github.com/user-attachments/assets/580af9f7-4232-4870-a55e-85b6e67e2f9a" />


---

## 🔄 Workflow
1. **Setup** → Launch headless Chrome browser with Selenium.  
2. **Scraping** → Load Cars24 city URLs, scroll to load listings dynamically.  
3. **Extraction** → Parse car details (Year, Price, KM Driven, etc.) using BeautifulSoup.  
4. **Cleaning** → Normalize data (remove ₹, convert to integers, handle inconsistent formats).  
5. **Export** → Save final dataset as CSV for analysis.  
6. **Analysis** → Generate insights on pricing trends, car age, fuel type preferences, etc.
7. <img width="894" height="582" alt="image" src="https://github.com/user-attachments/assets/be4fc110-65dc-4c56-b72c-e035f2d10fc5" />
 

---

## ⚡ Challenges & Solutions
- **Dynamic content loading** → Solved using Selenium with scroll + delay.  
- **Inconsistent data formats** → Custom regex and parsing logic.  
- **Slow rendering** → Implemented `time.sleep()` strategically.  

---

## 📊 Key Insights
- A typical used **Honda City** is **7.5 years old** and costs around **₹5.6 Lakhs**.  
- **Petrol & Manual cars dominate** (≈ 89% petrol, majority manual).  
- **Delhi-NCR** → Largest supply of listings.  
- **Bengaluru** → Highest average prices (~₹6.4 Lakhs).  
- **Mumbai** → More budget-friendly options.
- <img width="796" height="383" alt="image" src="https://github.com/user-attachments/assets/c4194b00-db76-4f58-8404-44697ea446bb" />
<img width="763" height="375" alt="image" src="https://github.com/user-attachments/assets/6f4a63fd-2cf8-4cc0-a1da-2f1a11178ea0" />
<img width="683" height="520" alt="image" src="https://github.com/user-attachments/assets/fbeddea1-5048-422f-9831-7e516de27d67" />




