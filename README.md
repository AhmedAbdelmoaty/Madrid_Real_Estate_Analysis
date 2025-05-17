# 🏠 Madrid Real Estate Analysis

This is a simple data analysis project using real estate data from Madrid, Spain. I used Python and Jupyter Notebook to clean the data and explore housing prices and patterns.

## 📁 Project Structure

- `Madrid_Analysis.ipynb`: Main notebook
- `Data/`
  - `houses_Madrid.csv`: Raw dataset from Kaggle
  - `houses_Madrid_cleaned.csv`: Cleaned dataset after preprocessing
- `Images/`: Visualizations from the analysis

## 🧹 Data Cleaning

- Removed duplicate rows
- Filled some missing values using the (mode), not all missing values were deleted
- Focused on the most important columns:
  - `sq_mt_built`, `n_rooms`, `n_bathrooms`, `buy_price`, `buy_price_by_area`


## 📊 Data Analysis
I did three types of analysis:
- **Univariate**: Looked at distributions using histograms and boxplots  
- **Bivariate**: Used pairplot, heatmap, and regression plots  
- **Multivariate**: Scatter plot with color and size to represent extra variables

### 🔍 Key Insights
- Bigger houses usually cost more  
- Price per square meter is more useful for comparing expensive areas  
- Some districts have small homes but very high price per m²

## 🖼️ Visualizations

- ![Histogram](images/Histogram.png)
- ![Boxplot](images/Boxplot.png)
- ![Pairplot](images/Pairplot.png)
- ![Heatmap](images/Heatmap.png)
- ![Scatterplot](images/Scatterplot.png)

## 🛠️ Tools Used
- Python
- Pandas
- Seaborn
- Plotly
- Jupyter Notebook


- 📧 aabdelmoaty133@gmail.com  
- 💼 [LinkedIn](https://www.linkedin.com/in/ahmed-abdelmoaty-2b6860357)

