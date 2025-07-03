# Projects
🎯 **Project Overview**

This project analyzes Zomato restaurant data to understand dining patterns, service preferences, and pricing trends. The analysis focuses on extracting actionable insights about online vs offline services, restaurant type preferences, and couple dining price ranges.
___________________________________________________________________________________________________________________________________________________________________________________

**Business Impact:** These insights can help restaurant owners optimize their service offerings and pricing strategies to better serve their target customers.
_____________________________________________________________________________________________________________________________________________________________ 

📊 **Dataset**

Source: Zomato Restaurant Dataset
Size: 148 rows, 7 columns

**Features:**

Restaurant names and ratings

Online ordering and table booking availability

Cost for two people

Restaurant types (Cafes, Dining, Buffet, etc.)

Customer votes and ratings


**Data Quality**

Missing Values: Handled through imputation and removal

Data Types: Cleaned and standardized (ratings, costs, categories)

Duplicates: Removed for accurate analysis
________________________________________________________________________________________________________________________________________________________________


❓ **Key Questions**

1. Do more restaurants provide online delivery compared to offline services?

2. Which types of restaurants are most favored by the general public?

3. What price range do couples prefer for dining out?
_________________________________________________________________________________________________________________________________________________________________

🛠️ **Technologies Used**

**Python 3.8+:** Core programming language

**Pandas:** Data manipulation and analysis

**NumPy:** Numerical computing

**Matplotlib:** Data visualization

**Seaborn:** Statistical data visualization

**Jupyter Notebook:** Interactive development environment
____________________________________________________________________________________________________________________________________________________________________________

**Step-by-Step Analysis**

**Data Loading:** Load and explore the Zomato dataset using Python.

**Data Cleaning:** Handle missing values, extract numeric data and relabel columns to properly convey information about the data.

**EDA:** Perform exploratory data analysis with the cleaned data.

**Question Analysis:** Answer the three research questions.

**Visualization:** Generate insights through charts and graphs.
_______________________________________________________________________________________________________________________________________________________________________________

🔍 **Key Findings**

**1. Online vs Offline Services**

About 39.19% of restaurants offer online ordering, this shows that majority of the resturants do not offer online services.

Only 5.41% offer table booking services.

Online ordering is significantly more common than table booking.

In terms of preference, only Dinning resturants favor offline orders over online orders.

**2. Most Favored Restaurant Types**

Dining restaurants are  the most popular by votes with 20, 363 total votes, this is more than double the votes of the next closest category.

"Others" come second with strong customer engagement.


**3. Couple Price Preferences**

By total number of votes, the mid-range (301-600) is the most popular price category for couples.

The histogram shows that most of the resturants in our data set tend to keep pricing for couples on the lower side of the price spectrum, between 50 and 300.

