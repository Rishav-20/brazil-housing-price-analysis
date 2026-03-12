# Cost Driver & Regional Price Analysis Using Python | Brazil Housing Market
This project analyzes 22,000+ real estate listings from Brazil to examine how property size and geographic location influence housing prices.
The analysis includes data cleaning, exploratory data analysis, regional housing market comparison, and correlation analysis to understand pricing patterns in the Brazilian real estate market.

---

## Project Objective
The objective of this project is to explore factors that influence housing prices in Brazil.
Key goals include:
* Preparing and cleaning housing datasets
* Exploring price distributions
* Comparing housing prices across regions
* Analyzing the relationship between property size and price
* Evaluating regional differences in housing markets

---

## Dataset
The dataset contains residential property listings collected from the Properati real estate platform.
The analysis combines two datasets which are cleaned and merged before performing exploratory analysis.

| Feature | Description |
|--------|-------------|
| price_usd | Property price in USD |
| area_m2 | Property size in square meters |
| lat | Latitude coordinate |
| lon | Longitude coordinate |
| state | Brazilian state |
| region | Geographic region of Brazil |

The final dataset contains 22,844 property listings

---

## Technologies Used
Python
Pandas
Matplotlib
Plotly
Jupyter Notebook

---

## Project Workflow
The analysis follows a structured data analysis pipeline:
Import required Python libraries
* Load and clean Dataset 1
* Load and clean Dataset 2
* Merge both datasets
* Perform exploratory data analysis
* Analyze regional housing prices
* Explore relationship between property size and price
* Calculate correlation between size and price in southern states

---

## Project Architecture
The project follows a typical data analytics workflow:

Dataset 1 → Data Cleaning → Dataset 2 → Data Cleaning → Merge Datasets → Exploratory Data Analysis → Regional Price Analysis → Correlation Analysis → Key Insights

---

## Key Insights
* Housing prices vary significantly across Brazilian regions
* The Southeast region shows the highest average housing prices
* Property size has a moderate positive relationship with housing price
* Geographic location appears to influence housing prices more strongly than property size

---

## Repository Structure
```
brazil-housing-price-analysis/
│
├── data/
│   ├── brasil-real-estate-1.csv
│   └── brasil-real-estate-2.csv
│
├── notebooks/
│   └── housing_pricing_in_brazil.ipynb
│
├── requirements.txt
└── README.md
```
## How to Run the Project
1. Clone the repository: git clone https://github.com/Rishav-20/brazil-housing-price-analysis.git
2. Navigate to the project folder
3. Install dependencies: pip install -r requirements.txt
4.Open the Jupyter Notebook in the notebooks folder and run the analysis

---

## Future Improvements

* Building a machine learning model for price predictio
* Adding interactive dashboards
* Incorporating additional housing features such as property type or amenities

---

## Author

Rishav Sharma
