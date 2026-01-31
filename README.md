🚗 Cars24 Used Car Market Analysis (EDA Project)
📌 Project Overview

The Cars24 Used Car Market Analysis project focuses on extracting meaningful insights from 5,000+ used car listings to understand pricing patterns, customer preferences, and key factors influencing resale value in the Indian automobile market.

By applying Exploratory Data Analysis (EDA) techniques, this project transforms raw data into actionable insights that help buyers make smarter decisions and sellers price vehicles competitively.

🎯 Objective

The main goals of this project are:

Understand the structure and quality of the dataset

Clean and preprocess raw data

Perform Univariate, Bivariate, and Multivariate analysis

Identify the major factors affecting car prices

Validate assumptions using Hypothesis Testing

Provide data-driven recommendations

📊 Dataset Information

Source: Cars24 website (Web Scraping)

Total Records: 5000+ used car listings

Key Features:

Car Name / Brand

Manufacturing Year

Price

Kilometers Driven

Fuel Type

Transmission

Ownership

Location

🛠️ Technologies Used

Python

Pandas – Data cleaning & manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

BeautifulSoup / Requests – Web scraping

Jupyter Notebook – Development environment

🔄 Project Workflow
✅ 1. Web Scraping

Extracted used car listings from the Cars24 website

Converted unstructured website data into a structured dataset

Saved the dataset in CSV format for analysis

✅ 2. Data Cleaning

Performed multiple preprocessing steps:

Identified missing values using isnull()

Imputed missing values with mode for categorical columns

Handled inconsistent data formats

Removed duplicates

Converted data types for proper analysis

👉 Result: A clean and analysis-ready dataset.

✅ 3. Exploratory Data Analysis (EDA)
📌 Univariate Analysis

Analyzed individual variables to understand distribution and trends.

Key Insights:

Most cars fall within the ₹4L – ₹8L price range

Petrol cars dominate the listings

Majority of vehicles are 4–6 years old

Manual transmission is more common than automatic

📌 Bivariate Analysis

Examined relationships between two variables.

Key Insights:

Newer cars → Higher prices

Automatic cars are generally priced higher than manual

Brand significantly impacts resale value

Mileage has less impact compared to manufacturing year

📌 Multivariate Analysis

Studied combined effects of multiple variables.

Key Insight:
👉 The strongest price influencers are:

✅ Manufacturing Year
✅ Transmission Type
✅ Brand

Not Mileage (as commonly believed).

🧪 Hypothesis Testing

Used statistical testing to validate assumptions.

Example Hypothesis:

H₀ (Null Hypothesis): Transmission type does not affect car price.
H₁ (Alternate Hypothesis): Transmission type affects car price.

✅ Result:
Rejected the null hypothesis — Automatic cars are statistically more expensive.

🔥 Key Business Insights

⭐ Manufacturing year impacts price more than small mileage differences.

⭐ Automatic cars command a premium price.

⭐ Maruti and Hyundai have high resale liquidity due to strong demand.

⭐ The best value-for-money segment is cars aged 4–6 years.

⭐ Affordable cars under ₹10 Lakhs dominate the market — reflecting middle-class buying behavior.

💡 Recommendations
For Buyers:

✔ Choose cars that are 4–6 years old for the best balance of price and performance.
✔ Consider automatic vehicles for long-term convenience.

For Sellers:

✔ Price vehicles based on year rather than focusing heavily on mileage.
✔ Highlight transmission and brand in listings.

📈 Project Impact

This project demonstrates how data analysis can simplify decision-making in an otherwise opaque used car market by providing:

Clear pricing patterns

Consumer preference insights

Market demand understanding

🚀 Future Improvements

Build a Machine Learning model to predict car prices

Develop an interactive Power BI / Tableau dashboard

Automate real-time data scraping

Perform location-based price analysis

👩‍💻 Author

Sruthi
Aspiring Data Scientist | Passionate about turning data into insights
