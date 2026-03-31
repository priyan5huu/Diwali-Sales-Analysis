# Diwali Sales Analysis 🎆

A comprehensive data analysis project examining consumer purchasing patterns during the Diwali festival season across India. This project performs exploratory data analysis (EDA) on e-commerce transactions to uncover key insights about customer demographics, regional performance, and product preferences.

## 📊 Project Overview

This analysis examines **11,252 sales transactions** across multiple dimensions including:
- **Customer Demographics**: Gender, age groups, marital status, occupation
- **Geographic Distribution**: Sales across Indian states and zones
- **Product Performance**: Category-wise and product-wise sales trends
- **Purchase Behavior**: Order frequency and average transaction values

## 📁 Project Structure

```
Diwali Sales Analysis/
├── README.md                          # Project documentation
├── Diwali Sale Analysis.ipynb        # Main Jupyter notebook with analysis
├── Diwali Sales Data.csv             # Dataset (11,252 records)
└── LICENSE                           # (Optional: Add license)
```

## 🎯 Key Findings

### 1. **Gender-Based Insights**
- Female customers dominate Diwali purchases (significant contribution to total sales)
- Sales distribution shows distinct gender preferences in product categories

### 2. **Age Demographics**
- **26-35 age group** drives the highest sales volume
- Younger demographics (18-25) show high engagement with specific categories
- Middle-aged customers (36-45) contribute consistently to revenue

### 3. **Geographic Performance**
- **Top performing states**: Andhra Pradesh, Uttar Pradesh, Maharashtra, Karnataka
- **Regional zones**: Distinct performance variation across Northern, Southern, Central, Eastern, Western zones
- Opportunity for targeted regional marketing strategies

### 4. **Occupation-Based Patterns**
- IT Sector professionals lead in purchase frequency and amount
- Healthcare and Aviation sectors show strong buying power
- Govt and Banking employees demonstrate steady purchasing patterns

### 5. **Product Categories**
- **Auto** category dominates sales volume
- **Hand & Power Tools** shows emerging demand
- Product concentration indicates market opportunities in underperforming categories

### 6. **Purchasing Behavior**
- Average order value indicates premium customer segment
- Repeat purchase patterns visible across demographic groups

## 📈 Dataset Schema

| Column | Description | Data Type |
|--------|-------------|-----------|
| User_ID | Unique customer identifier | Integer |
| Cust_name | Customer name | String |
| Product_ID | Unique product code | String |
| Gender | Customer gender (M/F) | String |
| Age Group | Categorized age brackets (0-17, 18-25, 26-35, etc.) | String |
| Age | Actual age in years | Integer |
| Marital_Status | Marital status (0: Single, 1: Married) | Integer |
| State | Indian state | String |
| Zone | Geographic zone (North/South/East/West/Central) | String |
| Occupation | Customer's profession | String |
| Product_Category | Product type | String |
| Orders | Number of orders placed | Integer |
| Amount | Transaction amount in INR | Float |

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and cleaning
- **NumPy** - Numerical computations
- **Matplotlib** - Static visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive analysis environment

## 📋 Analysis Performed

### Data Cleaning
- Removed irrelevant columns (`Status`, `unnamed1`)
- Handled missing values (9,659 rows with null data removed)
- Data type conversion (`Amount` to integer)

### Exploratory Data Analysis
1. **Gender Analysis** - Count distribution and sales by gender
2. **Age Analysis** - Age group segmentation with gender cross-tabulation
3. **Geographic Analysis** - Top 10 states by orders and sales amount
4. **Marital Status Analysis** - Consumer segmentation by marital status
5. **Occupation Analysis** - Professional category analysis
6. **Product Category Analysis** - Category-wise performance
7. **Top Products** - Identification of best-selling products (Top 10)

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.7+
Jupyter Notebook
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/diwali-sales-analysis.git
cd diwali-sales-analysis
```

2. **Create a virtual environment** (Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. **Launch Jupyter Notebook**
```bash
jupyter notebook
```

5. **Open and run the analysis**
- Navigate to `Diwali Sale Analysis.ipynb`
- Run cells sequentially to execute the analysis

## 📊 Key Visualizations

The notebook includes the following visualizations:
- **Gender Distribution** - Count plot with bar labels
- **Sales by Gender** - Bar chart of total amount
- **Age Group Analysis** - Grouped bar chart with gender comparison
- **Top 10 States** - Order volume and sales amount
- **Occupation Performance** - Sales by professional category
- **Product Category Performance** - Revenue distribution
- **Top 10 Products** - Best-selling products by order count

## 💡 Business Recommendations

### For E-Commerce Teams:
1. **Target female customers** aged 26-35 with premium product offerings
2. **Expand in high-performing states** (AP, UP, MH) with region-specific campaigns
3. **Focus on IT professionals** - highest spending segment
4. **Develop Auto category** bundling with complementary products
5. **Create location-based promotions** leveraging geographic insights

### For Product Teams:
1. **Optimize Auto category** inventory - highest demand
2. **Investigate underperforming categories** for improvement
3. **Develop occupation-specific product lines** for professionals

### For Marketing Teams:
1. **Segment campaigns** by age, occupation, and geography
2. **Create Diwali offers** targeted at high-value customer segments
3. **Leverage marital status** for relevant product recommendations

## 📊 Data Quality Notes

- **Data Cleaning**: 9,659 records removed due to missing values in critical fields
- **Final Dataset**: 1,593 clean records after processing
- **Encoding Issues**: Minor data quality issues in state names (requires attention for production systems)

## 🔍 Areas for Future Analysis

1. **Time-series Analysis** - Temporal patterns within Diwali season
2. **Customer Segmentation** - RFM analysis and clustering
3. **Predictive Modeling** - Sales forecasting and customer lifetime value prediction
4. **Basket Analysis** - Product association rules
5. **Cohort Analysis** - Retention and repeat purchase patterns
6. **Statistical Testing** - Hypothesis testing on key relationships

## 🤝 Contributing

This is an educational project. Feel free to fork and enhance with:
- Additional statistical analysis
- Predictive models
- Interactive dashboards
- Data visualizations
- Documentation improvements

## 📝 License

This project is licensed under the MIT License - see LICENSE file for details.

## 👨‍💼 Author

**Priyanshu Pandey**
- GitHub: [Your GitHub Profile]
- LinkedIn: [Your LinkedIn Profile]

## 📞 Contact & Feedback

For questions, suggestions, or collaboration opportunities, feel free to reach out!

---

## ✨ Quick Start Commands

```bash
# Clone repository
git clone https://github.com/yourusername/diwali-sales-analysis.git

# Set up environment
cd diwali-sales-analysis
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

# Run analysis
jupyter notebook
```

## 📚 Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Seaborn Visualization Gallery](https://seaborn.pydata.org/examples.html)
- [Jupyter Notebook Guide](https://jupyter.org/documentation)

---

**Last Updated**: March 2026  
**Dataset Size**: 11,252 transactions  
**Analysis Type**: Exploratory Data Analysis (EDA)
