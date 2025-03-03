# Youtube-Data-Analysis
Data analysis and visualization of the Youtube content of a specific search query
## 📌 Project Overview
This project analyzes YouTube video data to gain insights into trends, performance, and engagement metrics. It involves data collection, preprocessing and  visualization to understand the factors influencing video popularity.

## 🚀 Features
- **Data Collection**: Extracts video metadata (title, views, likes, comments, duration, etc.) using YouTube API or web scraping.
- **Data Preprocessing**: Cleans and formats the dataset by handling missing values and converting data types.
- **Exploratory Data Analysis (EDA)**: Generates visualizations to analyze trends in video performance.
- **Statistical Insights**: Identifies correlations between video attributes and engagement metrics.

## 🛠️ Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, Matplotlib, Requests, Time, Nltk
- **Data Sources**: Web Scraping (BeautifulSoup, Selenium)
- **Version Control**: Git, GitHub

## 📂 Project Structure
```
YouTube-Data-Analysis/
│── Youtube_Videos.xlsx    # Raw dataset
│── Youtube_Video.ipynb    # Jupyter notebooks for analysis
│── README.md              # Project documentation
│── requirements.txt       # Dependencies
```

## 🔧 Installation & Usage
1. **Clone the Repository**
   ```bash
   git clone https://github.com/tharikashree/Youtube-Data-Analysis.git
   cd Youtube-Data-Analysis
   ```

2. **Create a Virtual Environment** (Optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate   # On macOS/Linux
   venv\Scripts\activate      # On Windows
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Analysis**
   - Open Jupyter Notebook and explore `Youtube_Video.ipynb`
   - Run Python scripts for analysis

## 📊 Sample Visualizations
- Views vs. Duration scatter plots
- Most popular categories
- Trends in video engagement

## 🔗 References
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

## 💡 Future Enhancements
- Automate data collection using APIs
- Build a recommendation model
- Deploy a web dashboard for real-time analysis

## 🤝 Contributing
Feel free to fork the repository and submit pull requests for improvements!

## 📜 License
This project is licensed under the MIT License.

