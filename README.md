# Restaurant-Order-Analytics
Restaurant Order Analytics uses Power BI and Python to visualize trends from 500+ food orders. Key insights include top dishes, peak meal times, customer ratings, and payment methods. Cleaned using Pandas, analyzed with DAX, the dashboard helps restaurants optimize performance and planning.
# Restaurant Order Analytics Dashboard

Welcome to the Restaurant Order Analytics project!  
This dashboard provides a visual summary of restaurant order trends using a dataset of 500+ transactions. It was built to help restaurant managers understand key business metrics like peak order times, top-performing dishes, customer preferences, and payment behaviors.

---

**Project Highlights**

- **Goal:** Analyze restaurant orders to identify top dishes, peak hours, and customer satisfaction trends.
- **Tools Used:**  
  - Power BI – for interactive dashboards  
  - Excel – for basic data viewing  
  - Python (Pandas) – for data cleaning and transformation  
  - DAX – for calculated columns and slicers in Power BI

---

**Dataset & ETL Process**

- **Source Files:**  
  - `Orders.xlsx`  
  - `Restaurants.xlsx`  

- **ETL Steps:**  
  1. Extracted and combined raw order and restaurant details  
  2. Cleaned column names, formatted date fields  
  3. Calculated `Meal Time` using DAX (Breakfast, Lunch, Dinner)  
  4. Unpivoted customer ratings to compare Food vs Delivery experience  
  5. Exported clean data as `Cleaned_Restaurant_Orders.csv`  
  6. Loaded into Power BI for visualization

---

**Visualizations Included**

1. **Top 10 Restaurants by Orders** – Bar Chart highlighting restaurants with the most orders  
2. **Customer Ratings (Food vs Delivery)** – Clustered Column Chart comparing customer satisfaction  
3. **Payment Method Analysis** – Pie Chart showing preferred payment options  
4. **Revenue by Meal Time** – Column Chart showing meal-wise revenue contribution  
5. **Filters:** Month, Category, Cuisine Type, Zone, and Meal Time

---

**KPIs Tracked**

- Total Orders: 500  
- Total Revenue: ₹299K  
- Total Unique Customers: 21  
- Average Food Rating: 3.36  
- Average Delivery Rating: 2.99  
- Average Delivery Time: 30.54 mins

---

**Key Insights**

- Lunch time drives the most revenue, even though dinner has more orders  
- Credit cards are the most popular payment method  
- Delivery service consistently receives lower ratings than food  
- South Indian cuisine dominates in Zone D

---

**Future Scope**

- Add monthly trend analysis  
- Use machine learning to predict peak times  
- Geo-map delivery zones using Power BI maps  
- Enable real-time data updates using Power Automate

---

**Author**

**Sundram Kumar**  
Email: [sundramnld@gmail.com](mailto:sundramnld@gmail.com)  
LinkedIn: [www.linkedin.com/in/imsundram](https://www.linkedin.com/in/imsundram)

---

Feel free to explore the project, suggest improvements, or fork it for your own use.  
Thank you for visiting!
