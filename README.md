# Game Lens: Steam Games Data Analysis

## 📌 Project Overview
Game Lens is a data science project that analyzes Steam game data collected from multiple sources (SteamDB, SteamCharts, SteamSpy, and the Steam API). The project aims to uncover gaming trends, player preferences, and market insights through data visualization, machine learning models, and dashboards.

## 📂 Dataset Description
The dataset consists of 20,000 game entries with the following attributes:
- **Game Metadata:** `appid`, `name`, `developer`, `publisher`, `release_date`
- **Market & Sales:** `owners`, `price`, `initialprice`, `discount`
- **Platform Support:** `windows`, `mac`, `linux`
- **Game Features:** `categories`, `genres`, `DLC_count`
- **Popularity Metrics:** `all_time_peak_ccu`, `user_scores (positive & negative)`

## 📊 Key Features
### 🔍 Data Scraping & Cleaning
- Data sourced from SteamDB, SteamCharts, SteamSpy, and the Steam API.
- Scraped using **Cheerio, Axios, Puppeteer**.
- Cleaned using **Pandas, Power BI DAX Queries**.

### 📈 Data Visualization
- **Python (Matplotlib, Seaborn)**: Genre frequency, trends over time.
- **Power BI Dashboards**: Market trends, game popularity by genre & platform.

### 🤖 Machine Learning Models
1. **Best Genre & Pricing Recommendation Model**
   - Recommends ideal genre, platform, and price for launching a new game.
   - Uses **normalized scoring** of genre popularity, pricing, and concurrent users.
2. **Personalized Game Recommendation System**
   - Uses **Cosine Similarity** for suggesting similar games based on user preferences.
   - Features considered: genre, price, developer, and publisher.
3. **Game Success Predictor**
   - Uses **Random Forest Classifier** to predict game success based on peak CCU and ownership.

## 📊 Power BI Dashboard Preview
# Game trends over time
![image](https://github.com/user-attachments/assets/f55a9bcf-9123-4b66-9eb0-1914bd7ffaec)

# Frequency of Genres across all games
![image](https://github.com/user-attachments/assets/aa9a336f-4a04-4fa9-bd52-5e5dbde461ce)





## 📌 Findings
- **Action** is the most popular genre.
- **Windows** dominates PC gaming (67% of Steam games support it).
- **Average game price**: ~$11.
- **Best price for an indie action game**: ~$6.

## 📌 Contributors
- **Mohammed Ali Khowaja** (2112150)
- **Muhammad Hamza Javed** (2112153)
- **Om Kirshana** (2112283)
- **Manoj Kumar** (2112147)
- **Asfund Ali Amjad** (2112341)

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🚀 Future Enhancements
- Incorporate **collaborative filtering** for better game recommendations.
- Add **user review sentiment analysis** to enrich insights.

---
_This project was developed as part of a final-year data science project._

