# 🛍️ Customer Shopping Behavior Analysis | Python + MySQL + Power BI

## 📌 Project Overview

This project presents an end-to-end **Customer Shopping Behavior Analysis** developed using **Python, MySQL, and Power BI**.

The objective was to transform raw customer purchase data into actionable insights about **customer spending, product preferences, subscription behaviour, demographics, ratings, discounts, and shipping choices**.

Python was used for data cleaning and exploratory analysis, MySQL for answering business questions through SQL queries, and Power BI for building an interactive customer analytics dashboard.

The project demonstrates a complete analytics workflow:

**Raw Data → Python → MySQL → Power BI → Business Insights → Recommendations**

---

## 🎯 Business Problem

Retail businesses collect large amounts of customer transaction data, but raw purchase records alone do not explain customer behaviour.

Management needs to understand:

- Which customer segments generate the most revenue?
- Which product categories perform best?
- How much does an average customer spend?
- Which age groups contribute most to sales?
- How many customers subscribe to the business?
- Do subscribers and non-subscribers behave differently?
- How do discounts influence purchasing behaviour?
- Which products receive the strongest customer ratings?
- Do shipping preferences influence customer spending?
- Where are the opportunities for customer retention, cross-selling, and personalization?

This project was designed to answer these questions through data analysis and interactive visualization.

---

# 🎯 Project Objectives

- Analyze overall customer purchasing behaviour.
- Measure average customer spending.
- Analyze customer satisfaction through review ratings.
- Evaluate subscription adoption.
- Compare subscribers and non-subscribers.
- Analyze revenue across product categories.
- Identify high-performing product categories.
- Compare customer behaviour across age groups.
- Analyze discount usage.
- Compare different shipping preferences.
- Identify highly rated products.
- Build an interactive customer analytics dashboard.
- Translate analytical findings into actionable business recommendations.

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| 🐍 **Python** | Data cleaning, preprocessing & exploratory analysis |
| 🐼 **Pandas** | Data manipulation & transformation |
| 🔢 **NumPy** | Numerical operations |
| 🗄️ **MySQL** | Business queries & customer analysis |
| 📊 **Power BI** | Interactive dashboard development |
| 📐 **DAX** | KPI measures & analytical calculations |
| 🔄 **Power Query** | Data transformation & preparation |

---

# 🔄 End-to-End Analytics Workflow

```text
Raw Customer Data
        ↓
Data Understanding
        ↓
Python Data Cleaning
        ↓
Data Transformation
        ↓
Exploratory Data Analysis
        ↓
MySQL Database
        ↓
SQL Business Questions
        ↓
Power BI Data Modeling
        ↓
DAX Measures
        ↓
Interactive Dashboard
        ↓
Customer Insights
        ↓
Business Recommendations
```

---

# 📊 Executive KPI Summary

The dashboard provides a high-level view of overall customer behaviour.

| KPI | Result |
|---|---:|
| 👥 **Number of Customers** | **3.9K** |
| 💰 **Average Purchase Amount** | **$59.76** |
| ⭐ **Average Review Rating** | **3.75 / 5** |
| 🔔 **Subscribed Customers** | **27%** |
| 👤 **Non-Subscribed Customers** | **73%** |

These KPIs provide an overview of the size of the customer base, purchasing behaviour, customer satisfaction, and subscription adoption.

---

# 📊 Dashboard Analysis

The Power BI dashboard analyzes customer behaviour across multiple dimensions.

### 👥 Customer Overview

Provides an overall view of:

- Number of customers
- Average purchase amount
- Average review rating
- Subscription status

### 🛍️ Product Category Analysis

Analyzes both:

- Revenue by category
- Sales volume by category

across:

- Clothing
- Accessories
- Footwear
- Outerwear

### 👤 Age Group Analysis

Compares revenue and sales across:

- Young Adults
- Middle-aged Customers
- Adults
- Seniors

### 🚚 Shipping Analysis

Interactive filters allow customer behaviour to be analyzed across:

- 2-Day Shipping
- Express
- Free Shipping
- Next Day Air
- Standard
- Store Pickup

### ♀️♂️ Gender Analysis

The dashboard can be filtered by gender to investigate differences in customer behaviour.

### 🔔 Subscription Analysis

Customers can be compared based on whether they have an active subscription.

---

# 🔍 Key Business Insights

## 1️⃣ Customer Base Reaches Approximately 3.9K

The dataset contains approximately **3,900 customers**, providing a meaningful base for analyzing purchasing behaviour across customer segments.

### 💡 Business Interpretation

Rather than treating all customers identically, the business can use demographic, product, subscription, and purchasing characteristics to develop more targeted customer strategies.

---

## 2️⃣ Average Customer Purchase Amount Is $59.76

The average purchase amount across customers is approximately:

### **$59.76**

### 💡 Business Interpretation

This KPI provides a useful benchmark for evaluating customer spending.

Customers spending significantly above this level can be investigated as potentially higher-value customers, while strategies such as product bundling and cross-selling can be tested to increase purchase value.

---

## 3️⃣ Average Customer Rating Is 3.75 / 5

The dashboard reports an average customer review rating of:

### ⭐ **3.75 out of 5**

### 💡 Business Interpretation

Customer satisfaction appears reasonably positive, but the rating also indicates room for improvement.

Products with consistently lower ratings should be investigated to understand whether issues relate to product quality, customer expectations, delivery, or other factors.

---

## 4️⃣ Subscription Adoption Is Relatively Low

Subscription analysis shows:

| Subscription Status | Customer Share |
|---|---:|
| ❌ **Not Subscribed** | **73%** |
| ✅ **Subscribed** | **27%** |

Nearly three-quarters of customers are currently non-subscribers.

### 💡 Business Interpretation

The large non-subscriber population represents an opportunity for subscription growth.

However, rather than targeting every non-subscriber, the business should identify customers with stronger purchase frequency or spending behaviour who may be more likely to benefit from subscription membership.

---

## 5️⃣ Clothing Is the Leading Product Category

The category analysis shows **Clothing** as the strongest category for both:

- 💰 Revenue
- 🛒 Sales volume

Accessories ranks second, followed by Footwear and Outerwear.

### 💡 Business Interpretation

Clothing represents a core commercial category and should receive particular attention in:

- Inventory planning
- Product availability
- Marketing campaigns
- Cross-selling
- Customer recommendations

---

## 6️⃣ Accessories Represent the Second-Strongest Category

Accessories rank behind Clothing in both revenue and sales volume.

### 💡 Business Interpretation

Accessories may provide strong cross-selling opportunities because they can be paired with Clothing purchases.

For example:

**Clothing + Accessories**

could be tested through bundles or personalized recommendations.

---

## 7️⃣ Young Adults Are the Strongest Age Segment

The age-group analysis shows **Young Adults** generating the highest:

- Revenue
- Sales volume

Middle-aged customers follow closely behind.

### 💡 Business Interpretation

Young Adults represent an important customer segment for the business.

Marketing campaigns, product recommendations, and promotional strategies can be designed around their observed purchasing preferences.

---

## 8️⃣ Revenue Is Relatively Distributed Across Age Groups

Although Young Adults lead revenue, the dashboard shows meaningful contribution from Middle-aged, Adult, and Senior customer groups as well.

### 💡 Business Interpretation

The business should avoid relying on a single age group.

Segment-specific campaigns may be more effective than applying the same marketing strategy across the entire customer base.

---

# 🗄️ SQL Business Analysis

MySQL was used to answer practical customer and retail business questions.

The analysis includes:

### 1. Revenue by Gender

Analyzed revenue contribution across male and female customers.

### 2. Discount Users Above Average Spend

Identified customers who used discounts while spending above the overall average purchase amount.

### 3. Top Products by Customer Rating

Identified the **Top 5 products based on average review rating**.

### 4. Standard vs Express Shipping

Compared average purchase amounts between customers using Standard and Express shipping.

### 5. Subscriber vs Non-Subscriber Spending

Compared customer spending behaviour based on subscription status.

### 6. Discount Usage Rate

Calculated the percentage of purchases where a discount was applied.

These queries help connect SQL analysis with practical business questions rather than using SQL only for technical demonstrations.

---

# 💡 Business Recommendations

## 1. 🎯 Develop a Subscriber Conversion Strategy

With only **27% of customers subscribed**, subscription adoption represents an important opportunity.

Instead of targeting all non-subscribers equally, the business could prioritize:

- Frequent purchasers
- Above-average spenders
- Highly engaged customers
- Customers responding positively to promotions

Personalized subscription benefits may improve conversion.

---

## 2. 🛍️ Protect the Clothing Category

Since Clothing leads both revenue and sales volume, management should prioritize:

- Product availability
- Inventory planning
- New product launches
- Category-specific campaigns

Stock shortages in this category could have a larger business impact than shortages in weaker categories.

---

## 3. 🔗 Cross-Sell Accessories With Clothing

Because Clothing and Accessories are the two strongest categories, the business could test complementary recommendations.

Examples:

```text
Clothing → Accessories
Footwear → Accessories
Outerwear → Clothing
```

This strategy could help increase the current **$59.76 average purchase amount**.

---

## 4. 👥 Target Young Adults With Personalized Campaigns

Young Adults represent the strongest age segment in both revenue and sales.

Campaigns for this group could focus on:

- Personalized recommendations
- New arrivals
- Category-based offers
- Loyalty rewards
- Product bundles

---

## 5. ⭐ Investigate Customer Satisfaction Opportunities

The current average rating is **3.75 / 5**.

Products or categories receiving consistently below-average ratings should be investigated.

The business should identify whether lower ratings are associated with:

- Particular products
- Categories
- Shipping methods
- Customer groups

This can help prioritize customer experience improvements.

---

## 6. 🚚 Optimize Shipping Strategy

Shipping preferences should be analyzed together with purchase value and customer behaviour.

If customers using faster shipping methods demonstrate higher purchase value or engagement, shipping benefits could potentially be incorporated into subscription or loyalty programs.

---

## 7. 💸 Evaluate Discount Effectiveness

Discounts should not be evaluated only by the number of customers using them.

The business should compare:

**Discount Usage → Purchase Amount → Purchase Frequency → Customer Value**

This helps determine whether discounts are encouraging valuable purchasing behaviour or simply reducing revenue per transaction.

---

## 8. 📈 Increase Average Purchase Value

With an average purchase amount of **$59.76**, the business can test strategies designed to increase basket size.

Potential strategies include:

- Product bundles
- Complementary recommendations
- Threshold-based promotions
- Personalized cross-selling
- Loyalty incentives

---

# 💼 Business Impact

This project demonstrates how customer transaction data can be transformed into an interactive **customer analytics decision-support solution**.

The analysis can help a retail business:

- 👥 Understand customer segments
- 💰 Monitor purchasing behaviour
- 🛍️ Identify high-performing categories
- 🔔 Analyze subscription adoption
- ⭐ Monitor customer satisfaction
- 🚚 Evaluate shipping preferences
- 💸 Understand discount behaviour
- 🎯 Support targeted marketing
- 🔗 Identify cross-selling opportunities
- 📈 Develop strategies to increase customer value

Rather than simply displaying sales metrics, the project connects **customer behaviour with actionable retail decisions**.

---

# 🧠 Skills Demonstrated

## 🐍 Python

- Data cleaning
- Data preprocessing
- Exploratory Data Analysis
- Pandas
- NumPy
- Data transformation

## 🗄️ MySQL

- Data querying
- Aggregations
- `GROUP BY`
- `ORDER BY`
- Conditional analysis
- Customer segmentation
- Average calculations
- Business-oriented SQL queries

## 📊 Power BI

- Data modeling
- DAX measures
- KPI cards
- Interactive dashboard
- Customer segmentation
- Slicers & filters
- Category analysis
- Demographic analysis
- Dashboard design

## 🔄 Power Query

- Data cleaning
- Data transformation
- Data type management
- Preparing data for reporting

## 🧠 Business Analytics

- Customer behaviour analysis
- Customer segmentation
- Revenue analysis
- Product performance analysis
- Subscription analysis
- Customer satisfaction analysis
- Business storytelling
- Insight generation
- Business recommendations

---

# 📁 Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── 📂 Data/
│   └── customer_shopping_behavior.csv
│
├── 🐍 Python/
│   └── Customer_Shopping_Analysis.ipynb
│
├── 🗄️ SQL/
│   └── Customer_Shopping_Queries.sql
│
├── 📊 PowerBI/
│   └── Customer_Behavior_Dashboard.pbix
│
├── 🖼️ Dashboard/
│   └── Customer_Behavior_Dashboard.png
│
└── 📖 README.md
```

> Adjust the filenames if your actual GitHub files use different names.

---

# 🖼️ Dashboard Preview

```markdown
![Customer Behavior Dashboard](Dashboard/Customer_Behavior_Dashboard.png)
```

---

# 🎯 Key Takeaway

This project demonstrates a complete customer analytics workflow:

### **Python → MySQL → Power BI → Customer Insights → Business Recommendations**

The project demonstrates the ability to:

- Clean and transform customer data
- Translate business questions into SQL queries
- Develop meaningful customer KPIs
- Analyze customer segments
- Build an interactive Power BI dashboard
- Identify purchasing patterns
- Communicate business insights
- Recommend data-driven actions

The focus is not only on **what customers purchased**, but also on understanding **who the customers are, how they behave, and how those insights can support better retail decisions**.

---

# 🚀 Future Improvements

Potential future enhancements include:

- 🔮 Customer purchase prediction
- 📊 RFM customer segmentation
- 💰 Customer Lifetime Value (CLV) analysis
- 🛒 Market basket analysis
- 📉 Customer churn analysis
- 🎯 Recommendation system
- 🧪 A/B testing of promotional strategies
- 🔄 Automated Power BI refresh
- ☁️ Power BI Service deployment

---

# 👩‍💻 Author

**Kanishka Agarwal**

**Aspiring Data Analyst**

`Python` • `MySQL` • `Power BI` • `SQL` • `Excel` • `DAX` • `Power Query` • `Machine Learning`

⭐ If you found this project useful, feel free to explore the repository.

---

## 🔗 Connect With Me

**Portfolio:** [Kanishka Agarwal](https://kanishka-agarwal-data-analyst-portfolio.ai.studio)

**LinkedIn:** [Kanishka Agarwal](https://www.linkedin.com/in/kanishka-agarwal-485499333/)

**GitHub:** [kashishaggarwal987-gif](https://github.com/kashishaggarwal987-gif)

**Email:** [kashishaggarwal987@gmail.com](mailto:kashishaggarwal987@gmail.com)

---
