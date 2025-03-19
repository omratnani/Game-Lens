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

# Game Popularity over time
![image](https://github.com/user-attachments/assets/0734a663-430f-40d7-8a0a-190597d573b1)

## Dashboards
# Genral 
![image](https://github.com/user-attachments/assets/1ddf6215-36d9-4e19-9b17-df0be3793604)

# Game Popularity by Genre 
![image](https://github.com/user-attachments/assets/6b514d79-d8f2-42fd-844a-27465b0df174)
![image](https://github.com/user-attachments/assets/5a093001-3af4-4757-b312-c19f86e5e143)

# Overall Game Popularity
![image](https://github.com/user-attachments/assets/9d244c74-09a9-4356-a84e-4d7e629a9a6a)

# Pricing
![image](https://github.com/user-attachments/assets/8009cdae-6257-4661-ac23-f73c177bf93a)

# AI Models
# Personalized Game Recommendation Model
![image](https://github.com/user-attachments/assets/e3476557-ee66-4e75-bd87-6438ba374368)

# Game Success Predictor
![image](https://github.com/user-attachments/assets/610665a3-4d53-4cf2-a82c-935f110b719b)
![image](https://github.com/user-attachments/assets/6a6051c9-64c7-4886-b354-c7ddc4cac92f)







## 📌 Findings
- **Action** is the most popular genre.
- **Windows** dominates PC gaming (67% of Steam games support it).
- **Average game price**: ~$11.
- **Best price for an indie action game**: ~$6.

## 📌 Contributors
- **Om Kirshana** 
- **Mohammed Ali Khowaja** 
- **Muhammad Hamza Javed** 
- **Manoj Kumar** 
- **Asfund Ali Amjad** 

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🚀 Future Enhancements
- Incorporate **collaborative filtering** for better game recommendations.
- Add **user review sentiment analysis** to enrich insights.

---
_This project was developed as part of a final-year data science project._

