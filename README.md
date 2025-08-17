# YouTube Sentiment Analysis 📊💬

This project performs sentiment analysis on YouTube comments and analyzes video data to understand viewer sentiment, identify popular tags, and explore relationships between video views, likes, and dislikes. It provides insights into the emotional undercurrents of comments and helps identify trends and patterns in viewer emotions, assisting content creators in crafting content that resonates with their audience.

## 🚀 Key Features

- **Data Loading and Preprocessing:** Loads YouTube comment and video data from CSV files (`GBcomments.csv` and `USvideos.csv`). Handles missing values in the comment data.
- **Sentiment Analysis:** Calculates the sentiment polarity of each comment using TextBlob. The polarity score ranges from -1 (negative) to 1 (positive).
- **Sentiment-Based Analysis:** Separates comments into positive and negative categories based on their polarity scores.
- **Word Cloud Visualization:** Generates word clouds for positive and negative comments to visualize the most frequent words associated with each sentiment. Also generates a word cloud for video tags.
- **Regression Analysis:** Creates regression plots to explore the relationship between video views and likes/dislikes.
- **Correlation Analysis:** Creates a correlation heatmap to visualize the correlation between different features in the dataframe.
- **Dependency Management:** Uses `requirements.txt` to manage project dependencies, ensuring consistent setup across different environments.

## 🛠️ Tech Stack

- **Data Analysis & Manipulation:**
    - `pandas`: For data manipulation and analysis.
    - `numpy`: For numerical operations.
- **Visualization:**
    - `matplotlib.pyplot`: For creating plots and visualizations.
    - `seaborn`: For creating statistical graphics.
    - `plotly.express`: For creating interactive plots.
    - `wordcloud`: For generating word clouds.
- **Sentiment Analysis:**
    - `textblob`: For sentiment analysis.
- **Other:**
    - `re`: For regular expression operations (used for cleaning tags).
- **Environment Management:**
    - `pip`: For installing dependencies from `requirements.txt`.

## 📦 Getting Started

### Prerequisites

- Python 3.6+
- `pip` (Python package installer)

### Installation

1.  Clone the repository:

    ```bash
    git clone <repository_url>
    cd youtube_sentiment_analysis
    ```

2.  Install the required packages using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

### Running Locally

1.  Ensure you have the `GBcomments.csv` and `USvideos.csv` files in the same directory as the Jupyter Notebook.
2.  Open the `Project_code.ipynb` Jupyter Notebook:

    ```bash
    jupyter notebook Project_code.ipynb
    ```

3.  Run the notebook cells sequentially to perform the sentiment analysis and generate visualizations.

## 📂 Project Structure

```
youtube_sentiment_analysis/
├── Project_code.ipynb      # Jupyter Notebook containing the code
├── GBcomments.csv          # CSV file containing YouTube comments (Great Britain)
├── USvideos.csv            # CSV file containing YouTube video data (USA)
├── requirements.txt        # List of Python dependencies
└── README.md               # Project documentation
```

## 💻 Usage

The `Project_code.ipynb` notebook contains the complete workflow for loading data, performing sentiment analysis, and generating visualizations. Simply run the notebook cells in order to reproduce the analysis. The notebook outputs word clouds, regression plots, and correlation heatmaps that provide insights into YouTube viewer sentiment and video data trends.



## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive commit messages.
4.  Submit a pull request.

## 📝 License

This project is licensed under the [MIT License](LICENSE).

## 📬 Contact

If you have any questions or suggestions, feel free to contact me at [your_email@example.com](mailto:your_email@example.com).

## 💖 Thanks

Thanks for checking out this project! I hope you find it useful.

