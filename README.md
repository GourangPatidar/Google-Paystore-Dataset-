
---

# Google Play Store Data Analysis

This repository contains an in-depth analysis of the Google Play Store dataset. The dataset consists of 10,000 rows and 14 columns, analyzed to extract meaningful insights and create intuitive visualizations. The analysis was conducted using Jupyter Notebook, and a comprehensive Power BI dashboard was created for dynamic data exploration.

## Overview

The primary objective of this project is to analyze the Google Play Store dataset to uncover patterns and trends. This analysis was performed in a Jupyter notebook using various data science libraries. Additionally, a Power BI dashboard was created to visualize the data effectively.

## Features

### 1. Dataset Analysis
- **Description**: This feature involves the analysis of a dataset with 10,000 rows and 14 columns.
- **Technology**: Utilizes Jupyter Notebook with libraries such as NumPy, Pandas, Seaborn, and Matplotlib.
- **Steps**:
  - **Data Cleaning**: Handled missing values, outliers, and formatted the data for analysis.
    - **Missing Values**: Imputed missing values using mean/mode or dropped rows with extensive missing data.
    - **Outliers**: Identified and handled outliers to prevent skewing the analysis.
    - **Data Formatting**: Converted data types and normalized values where necessary.
  - **Exploratory Data Analysis (EDA)**: Conducted EDA to identify patterns and relationships within the data.
    - **Descriptive Statistics**: Calculated mean, median, mode, and standard deviation for numerical columns.
    - **Distribution Analysis**: Analyzed the distribution of numerical features using histograms and box plots.
    - **Correlation Analysis**: Used heatmaps to identify correlations between features.

### 2. Insights Extraction
- **Description**: Identified approximately 22 key insights from the dataset.
- **Benefits**: Provides valuable information about app categories, ratings, reviews, and more, helping stakeholders make informed decisions.
- **Techniques**:
  - **Statistical Analysis**: Performed statistical analysis to derive meaningful insights.
    - **Category Analysis**: Analyzed the distribution of apps across different categories.
    - **Rating Analysis**: Examined the average ratings for apps in various categories.
    - **Review Analysis**: Analyzed the relationship between the number of reviews and app ratings.
  - **Visualization**: Created visualizations using Seaborn and Matplotlib to represent data trends and patterns.
    - **Bar Plots**: Visualized the number of apps per category.
    - **Scatter Plots**: Plotted relationships between price, rating, and number of reviews.
    - **Box Plots**: Showed the spread of ratings across different app categories.

### 3. Power BI Dashboard
- **Description**: Developed an interactive Power BI dashboard to present the data intuitively.
- **Benefits**: Allows users to explore the data dynamically and gain insights at a glance.
- **Components**:
  - **Charts and Graphs**: Included various charts and graphs to visualize key metrics.
    - **Category Distribution**: Pie charts showing the proportion of apps in each category.
    - **Rating Trends**: Line charts illustrating the trend of average ratings over time.
    - **Review Insights**: Bar charts showing the distribution of reviews across different ratings.
  - **Filters and Slicers**: Enabled users to filter and slice the data for detailed analysis.
    - **Category Filter**: Allows users to view data for selected app categories.
    - **Rating Filter**: Enables filtering of apps based on their ratings.
    - **Price Range Filter**: Allows users to explore apps within a specific price range.

## Repository Structure

```plaintext
.
├── Architecture.pdf                       # System architecture document
├── Detailed Project Report.pdf            # Comprehensive project report
├── Google Play Store Apps Data Analysis 2 Final.pdf # Final analysis report
├── HLD Google app store.pdf               # High-Level Design document
├── LLD Google app store.pdf               # Low-Level Design document
├── Power BI Report Google Play Store Data Analysis Final.pbix # Power BI report
├── cleaned_data.csv                       # Cleaned dataset used for analysis
├── googleplaystore.csv                    # Original dataset
├── wireframe google app store.pdf         # Wireframe document
└── README.md                              # Project documentation (this file)
```

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook
- Power BI (for viewing the dashboard)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/GourangPatidar/Google-Paystore-Dataset-.git
   cd Google-Paystore-Dataset-
   ```

2. **Install the dependencies**
   ```bash
   pip install numpy pandas seaborn matplotlib
   ```

### Running the Analysis

1. **Open the Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

2. **Navigate to the analysis notebook**
   - Google Play Store Apps Data Analysis 2 Final.ipynb

3. **Run the cells**
   - Execute the cells in the notebook to perform the analysis and generate visualizations.

### Viewing the Power BI Dashboard

- Open the Power BI Report file (`Power BI Report Google Play Store Data Analysis Final.pbix`) in Power BI Desktop to interact with the dashboard.

## Insights

Here are some of the key insights derived from the analysis:

- **App Categories**: Distribution of apps across various categories.
  - **Top Categories**: Identified the top app categories by the number of apps.
  - **Least Popular Categories**: Highlighted categories with the fewest apps.
- **Ratings and Reviews**: Analysis of app ratings and user reviews.
  - **Average Ratings**: Calculated the average ratings for different app categories.
  - **Review Count**: Examined the distribution of the number of reviews across apps.
- **Price and Downloads**: Relationship between app prices and the number of downloads.
  - **Free vs. Paid Apps**: Compared the download counts for free and paid apps.
  - **Price Distribution**: Analyzed the price range of paid apps.
- **Content Rating**: Distribution of apps based on content ratings.
  - **Content Categories**: Examined the distribution of content ratings (e.g., Everyone, Teen, Mature).

## Contributing

We welcome contributions to enhance this project. Please follow the steps below to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Create a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The open-source community for their invaluable contributions.
- Data providers for making the Google Play Store dataset available.

---

