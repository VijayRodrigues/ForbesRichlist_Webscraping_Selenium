# 💰 Forbes Billionaires Web Scraper  

🚀 A Python-based **web scraping project** that extracts details of the world's billionaires from [Forbes](https://www.forbes.com).  
This project **automates data extraction** using **Selenium** and saves billionaire details such as:  

- **Rank**  
- **Name**  
- **Net Worth**  
- **Age**  
- **Citizenship**  
- **Source of Income**  
- **Industry**  

---

## 📌 Table of Contents  

- [📂 Project Structure](#-project-structure)  
- [🚀 Features](#-features)  
- [🔧 Installation & Setup](#-installation--setup)  
- [🎯 How It Works](#-how-it-works)  
- [📜 Technologies Used](#-technologies-used)  
- [📊 Sample Output](#-sample-output)  
- [🚀 Future Enhancements](#-future-enhancements)  
- [🤝 Contributing](#-contributing)  
- [📜 License](#-license)  

---

## 📂 Project Structure  

![image](https://github.com/user-attachments/assets/e4d64509-347f-4c36-aa88-5241e3fb097e)


---

## 🚀 Features  

- ✅ Extracts real-time billionaire details from Forbes  
- ✅ Selenium-based web automation for navigation & data scraping  
- ✅ Stores data in Pandas DataFrame for easy manipulation  
- ✅ Exports data to CSV for further analysis  
- ✅ Pagination Handling – Automatically scrapes multiple pages  
- ✅ Error Handling – Ensures smooth execution  

---

## 🎯 How It Works  

1️⃣ Opens the **Forbes** website and navigates to the **Billionaires** page  
2️⃣ Extracts details like **Rank, Name, Net Worth, Age, Citizenship, Source, Industry**  
3️⃣ Loops through multiple pages to **collect more data**  
4️⃣ Saves the extracted data into a **Pandas DataFrame**  
5️⃣ Exports the final dataset to a **CSV file**  

---

## 📜 Technologies Used  

- 🐍 **Python**  
- 🌐 **Selenium** – For web automation  
- 📊 **Pandas** – For data manipulation  
- 🔧 **WebDriver Manager** – For managing ChromeDriver  


---

## 📊 Sample Output  

| Rank | Name             | Net Worth | Age | Citizenship | Source          | Industry       |
|------|----------------|-----------|-----|-------------|----------------|---------------|
| 1    | Elon Musk      | $200B     | 52  | USA         | Tesla, SpaceX  | Automotive    |
| 2    | Jeff Bezos     | $180B     | 59  | USA         | Amazon         | E-Commerce    |
| 3    | Bernard Arnault| $175B     | 74  | France      | LVMH           | Fashion       |
| 4    | Bill Gates     | $130B     | 67  | USA         | Microsoft      | Tech          |
| 5    | Mark Zuckerberg| $120B     | 40  | USA         | Meta (Facebook)| Social Media  |

