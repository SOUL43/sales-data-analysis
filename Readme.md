# Sales Data Analysis

**AI Academia Internship | Gaurav Chauhan | October 2026**

## About

This project analyses retail sales data using Python to identify sales trends, top-performing products, category-wise revenue, city-wise performance, and monthly sales patterns. It also applies machine learning techniques to explore monthly sales forecasting and classify transactions into Low Sale and High Sale categories.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

## Dataset

The project uses a retail sales dataset containing transaction information, product details, customer attributes, sales values, and order dates.

- **File:** `sales_data.csv`
- **Time period:** January 2024 – June 2026 *(verify against your actual dataset)*
- **Rows and columns:** Run the notebook's data-loading cell to confirm the exact dimensions.

## Key Findings

1. **Category performance:** Electronics generated approximately ₹17,51,037 in sales, representing about 50.83% of total sales. Maintaining stock availability and monitoring margins in this category may help protect revenue.
2. **Monthly patterns:** May had average transaction sales of approximately ₹71.70 in the earlier analysis. Reviewing demand before this month may help improve inventory planning.
3. **Top-performing product:** Headphones generated approximately ₹3,33,411 in recorded sales. Stock availability and profitability should be monitored.
4. **Lower-performing product:** Monitors generated approximately ₹22,613 in recorded sales. Pricing, margins, stock availability, and demand should be reviewed before making inventory decisions.
5. **Machine learning:** The monthly Linear Regression model showed weak test performance, with a previously reported negative R-squared score. More historical data and better features are needed before relying on its forecasts.

*Note: Verify these figures against the final notebook outputs before publishing. They should reflect the exact dataset and final model results.*

## How to Run

1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy
   ```

3. Download or clone this repository.
4. Keep the notebook and dataset in the same folder.
5. Open `Sales_Analysis_Final.ipynb` in Jupyter Notebook or VS Code.
6. Restart the kernel and run all cells from top to bottom.

## Project Files

- `Sales_Analysis_Final.ipynb` — notebook containing data analysis, visualisations, and machine learning.
- `sales_data.csv` — retail sales dataset.
- PNG files — generated charts and model evaluation visualisations.

## Author

**Gaurav Chauhan**  
AI Academia — Python with Data Science Internship
