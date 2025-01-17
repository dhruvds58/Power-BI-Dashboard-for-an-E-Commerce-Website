# **The Look E-Commerce Dashboard Analysis**

## **Overview**
This project showcases an interactive Power BI dashboard analyzing the **Look E-Commerce** dataset hosted on Google BigQuery. The dataset simulates real-world e-commerce operations, allowing us to explore customer behavior, sales performance, and financial metrics for actionable insights. This analysis addresses critical challenges faced by the e-commerce platform, including customer retention, revenue growth, and operational inefficiencies.

## **Key Features**
- **Sales Overview**: Analyze sales trends, return rates, and brand performance.
- **Customer Demographics**: Gain insights into customer age, gender, geographic distribution, and purchasing behavior.
- **Financial Metrics**: Evaluate revenue drivers, average order value (AOV), inventory turnover, and overall profitability.

## **Dataset Description**
The dataset consists of several tables structured for a robust analysis:
- **Fact Tables**: 
  - `distribution_centers`
  - `orders`
  - `events`
- **Dimension Tables**:
  - `inventory_items`
  - `order_items`
  - `products`
  - `users`

The synthetic dataset provides a detailed view of customer interactions, order details, product inventory, and logistics operations.

## **Dashboard Structure**
### **1. Sales Overview**
- Filters for **Gender** and **Year**.
- Insights into return rates (10% vs. the industry average of 15.2%).
- Profitability analysis of top brands, e.g., Ray-Ban and Canada Goose.
- Product category analysis with **Intimates** leading overall sales.

![Sales Overview Screenshot](path/to/sales-overview.png)

---

### **2. Customer Demographics**
- Average customer age: 41 years (significantly older than the 18-24 industry norm).
- Key geographic markets: China and the United States.
- Challenges:
  - High average time between orders (382 days).
  - Low repeat purchase rate and overreliance on paid acquisition channels like email marketing and AdWords.

![Customer Demographics Screenshot](path/to/customer-demographics.png)

---

### **3. Financial Metrics**
- Key revenue drivers: Outerwear, coats, and jeans.
- Industry comparison:
  - Average Revenue Per User (ARPU): $9.15 vs. $1,180 industry benchmark.
  - Average Order Value (AOV): $5.85 vs. $120 industry standard.
- Efficient inventory turnover cycle: 7 days vs. 30 days industry average.

![Financial Metrics Screenshot](path/to/financial-metrics.png)

---

## **Key Insights**
- Strong performance in inventory management and return rates.
- Opportunities for improvement in customer retention, acquisition costs, and ARPU.
- High-margin brands like Ray-Ban and Canada Goose drive profitability.
- Challenges with cart abandonment due to gaps in the checkout process.

## **Recommendations**
- **Enhance Customer Retention**: 
  - Introduce loyalty programs, exclusive discounts, and early access for repeat buyers.
- **Target Younger Demographics**:
  - Expand trendy product offerings or launch a sub-brand for younger audiences.
- **Optimize Checkout Process**:
  - Simplify checkout, offer guest options, and make costs transparent.
- **Boost Organic Traffic**:
  - Invest in SEO and content marketing (blogs, videos, and social media campaigns).
- **Diversify Product Portfolio**:
  - Include mid- and low-priced products to attract a broader customer base.
- **Improve Conversion Rates**:
  - Address the gap between items added to carts and purchases.

## **Future Work**
- Apply advanced machine learning techniques for:
  - Customer segmentation and targeted marketing.
  - Predictive inventory management.
  - Sales forecasting and demand anticipation.
- Use **Natural Language Processing (NLP)** to analyze customer feedback and sentiment for improved customer insights.

## **Tools Used**
- **Power BI**: Dashboard creation, data visualization, and DAX calculations.
- **Google BigQuery**: Dataset hosting and query execution.
- **Power Query**: Data cleaning and transformation.

## **Project Outcomes**
This project provides a comprehensive approach to identifying and addressing critical e-commerce challenges, equipping **The Look** with actionable insights to improve customer satisfaction, enhance profitability, and maintain a competitive edge in the market.
