# Marketing Mix Model Analysis Dashboard

## Live Dashboard
[View Interactive Dashboard](link-to-your-dashboard)

## Overview
I built this dashboard to analyze how different advertising channels affect sales. The goal was to figure out which marketing channels give the best return on investment and how to allocate budget more effectively.

## Data Source
This analysis uses advertising and sales data sourced from [Kaggle - Advertisement and Sales Data for Analysis](https://www.kaggle.com/datasets/ankitkr60/advertisement-and-sales-data-for-analysis), which includes:
- TV advertising spend and performance metrics
- Radio advertising expenditure and reach data  
- Digital marketing spend across various online channels
- Print advertising costs and circulation data
- Corresponding sales figures across multiple time periods

The dataset provides a comprehensive view of multi-channel marketing performance, making it ideal for marketing mix modeling and attribution analysis.

## The Analysis
I looked at advertising spend across TV, radio, digital, and print channels to see their impact on sales. The model helps identify which channels are driving the most revenue and where we might be over or under-investing.

## Files
* `Advertising and Sales Analysis Dashboard.html` - The main dashboard with all the charts and analysis
* `Marketing Mix Modelling.ipynb` - The Python notebook where I did the data work and built the model

## Key Findings
The dashboard shows performance metrics for each channel, attribution analysis, and ROI calculations. You can see which channels are performing well and get recommendations for budget reallocation.

## Technical Notes
Built the dashboard using HTML/CSS/JavaScript with Chart.js for the visualizations. The underlying analysis was done in Python using standard data science libraries including:
- pandas for data manipulation
- scikit-learn for modeling
- matplotlib/seaborn for analysis visualizations
- numpy for numerical computations

## Getting Started
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/ankitkr60/advertisement-and-sales-data-for-analysis)
2. Place the CSV file in your project directory
3. Open `Marketing Mix Modelling.ipynb` in Jupyter Notebook
4. Run all cells to reproduce the analysis

## Usage
Click the dashboard link above to explore the interactive charts. The notebook has all the code and methodology if you want to see how I built the model.

## Repository Structure
```
├── Advertising and Sales Analysis Dashboard.html
├── Marketing Mix Modelling.ipynb
├── data/
│   └── [Kaggle advertising and sales dataset]
└── README.md
```