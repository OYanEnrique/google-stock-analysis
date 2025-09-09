[Read in Portuguese](README.md) 

# The Saga of Google's Stock (GOOG): A Data Journey from 2005 to 2023

![Dashboard of Google Stock Analysis](./assets/google.png)

## ❯ The Beginning of the Journey: Unveiling the Story Behind the Numbers

On the volatile stage of the stock market, one protagonist stands out: Google's stock (GOOG). For almost two decades, its trajectory has been a saga of impressive peaks, valleys, and turns. But how can we decipher the story contained within millions of raw data points?

This project embarks on an *end-to-end* expedition to do just that: transform the chaos of numbers into a cohesive visual narrative. The goal is not just to analyze, but to reveal the secrets, trends, and risks that have shaped the historical performance of a technology giant.

## 📈 The Conflict: The Hidden Plot in the Data

Raw stock data is like a book written in an ancient language—full of potential but unintelligible to most. The real conflict is not the lack of information, but the absence of a clear story.

The mission was to forge a path from data collection to the creation of a visual oracle: a dashboard that would not only display charts but also tell the saga of Google, allowing anyone to understand the past to make more informed decisions about the future.

### Forging the Data: Where the Magic Happens

Every great journey requires preparation. Ours began in the Jupyter Notebook environment, where the tools of data explorers (**Python**, **Pandas**, **Matplotlib**, and **Seaborn**) were wielded to shape the data.

#### • Step 1: Purification (ETL) and the First Obstacle

The first step was to purify the raw ore—the `GOOG.csv` file. Dates were converted to the `datetime` format, data types were adjusted, and the ground was prepared.

Along the way, a challenge arose. **Looker Studio**, our final destination, spoke a different date dialect (`YYYYMMDD`). It was necessary to act as a translator, converting our date format to ensure seamless communication between the code and the BI platform. A small technical step, but a crucial obstacle that was overcome to ensure the integrity of our story.

#### • Step 2: Enchanting the Data (Feature Engineering)

With the data cleaned, it was time to infuse it with power. New metrics were calculated to give us a vision beyond the ordinary, turning simple data into powerful insights:

* **Simple Moving Averages (SMA 50 & 200):** Two magical lenses to observe short and long-term trends, revealing potential buy and sell signals.
* **Daily Return:** The pulse of the market, measuring the victory or defeat of each day in percentage terms.
* **Volatility (50 days):** A storm meter, quantifying the risk and uncertainty of the journey.

## 💡 The Climax: The Looker Studio Oracle

The journey culminates here. Where there were once only lines of code and tables, there is now an interactive and dynamic portal. The dashboard in **Looker Studio** is our treasure map revealed, where each chart comes together to tell the complete story.

**🔗 Explore the Saga Yourself: [Access the Interactive Dashboard](https://lookerstudio.google.com/reporting/8f839b22-f0f4-4a22-88e2-38b560468476)**

The panel reveals:
* **The Great Feats:** KPIs for Maximum Price, Minimum Price, and Average Volume.
* **The Saga's Timeline:** The evolution of the closing price over time.
* **The Market Currents:** The dance of the 50 and 200-day Moving Averages, indicating the tides of the trend.
* **The Roar of the Battle:** The volume of shares traded, showing the days of greatest interest and activity.
* **The Risk of the Adventure:** Historical volatility, mapping periods of calm and turbulence.

## 🎓 The Lessons of the Saga: Key Learnings

This expedition left us with three major lessons:

1.  **The Tower of Babel of Data:** I learned that every tool has its own "language." The need to convert dates to `YYYYMMDD` showed that preparing data for BI is an act of translation, ensuring that the story is not lost between different systems.

2.  **The Alchemist's Code:** The biggest challenge was not just calculating the Moving Averages, but translating their crossovers (like the famous "Golden Cross") into a clear visual insight on the dashboard. It was like turning the lead of code into the gold of business analysis.

3.  **The Art of the Storyteller:** I structured the dashboard to tell a narrative, positioning the price, volume, and volatility charts to reveal their correlations. This solidified my ability to transform raw data into a cohesive and easily understandable visual story.

---

## 🛠️ The Adventurer's Arsenal: Tools and Technologies

* **Programming Language:** Python 3
* **Analysis Libraries:** Pandas, Matplotlib, Seaborn
* **Development Environment:** Jupyter Notebook
* **BI and Visualization Tool:** Google Looker Studio
* **Data Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/henryshan/google-stock-price) | CSV Format

---

## 📂 The Treasure Map: Repository Structure

```
├── GOOGLE_limpo.xlsx                # The final map: cleaned dataset ready for BI
├── google_stock_prices.ipynb       # The logbook: notebook with the entire analysis journey
├── README.md                       # The scroll that narrates the saga (this file)
└── assets/
    └── google.png                  # The portrait of our discovery: dashboard image
```
---

## 🚀 Recreate the Journey: How to Run the Project

To replicate this analysis and uncover the data for yourself, follow the steps below:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/OYanEnrique/google-stock-analysis.git
    ```
2.  **Navigate to the directory:**
    ```bash
    cd google-stock-analysis
    ```
3.  **Install the dependencies:**
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```
4.  **Open the logbook:**
    ```bash
    jupyter notebook google_stock_prices.ipynb
    ```

---

## 👨‍💻 The Architect of the Analysis

* **Yan Enrique**
* **LinkedIn:** [https://www.linkedin.com/in/yanenrique/](https://www.linkedin.com/in/yanenrique/)
* **GitHub:** [https://github.com/OYanEnrique](https://github.com/OYanEnrique)
* **Landing page:** [https://yanenrique.carrd.co](https://yanenrique.carrd.co)
