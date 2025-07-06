# Weather Data Engineering Project

This project was developed as part of my MSc in Data Analytics at Dublin Business School. 
It demonstrates end-to-end data engineering skills by scraping weather data from the OpenWeather 
API,performing feature engineering, classifying weather conditions, handling missing values, and 
storing cleaned data in MongoDB. In addition, it includes a component for scraping visa decision 
data from the Irish Immigration website using BeautifulSoup.

## 📌 Features

- Weather data scraping from OpenWeather API (hourly and daily)
- Data normalization and cleaning with pandas
- Feature engineering and classification of weather conditions
- Handling missing data with custom logic (mean/mode imputation)
- Every two day automatic data updation to MongoDB with automatic null or error data handling
- Storage in MongoDB using PyMongo
- HTML table scraping with BeautifulSoup (visa decisions)
- Visualization of feature distributions with seaborn and matplotlib
- Modular code structure with functions for daily and hourly updates

## 📂 Project Structure
weather-data-engineering/
│
├── ca1_delvin_vallooran_jose_20039903.py
└── README.md


## ⚙️ Requirements

- Python 3.x
- pandas
- numpy
- requests
- pymongo
- matplotlib
- seaborn
- beautifulsoup4

You can install them with:

```bash
pip install pandas numpy requests pymongo matplotlib seaborn beautifulsoup4


🚀 How to Run
Clone this repository:

bash
Copy code
git clone https://github.com/Delvinvjose/weather-data-engineering.git
Navigate into the folder:

bash
Copy code
cd weather-data-engineering
Edit the MongoDB connection string in the script if needed.

Run the Python file:

nginx
Copy code
python ca1_delvin_vallooran_jose_20039903.py
(or use Jupyter Notebook if you prefer to test in cells)

✨ Highlights
Shows real-world data engineering skills

Demonstrates cleaning, classification, and storage of time series data

Applies practical visualization with boxplots

Uses modular coding style for maintainability

Integrates with a cloud MongoDB Atlas database

📞 Contact
Delvin Jose
LinkedIn 
Email: delvinjosevallooran@gmail.com
