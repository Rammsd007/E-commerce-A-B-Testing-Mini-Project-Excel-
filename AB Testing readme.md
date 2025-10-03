# E-commerce A/B Testing Mini Project (Excel)

## Project Overview
This project demonstrates a **mini A/B test** using an e-commerce dataset to analyze the impact of **discount banners** on website conversions.  

A/B testing is widely used in product, marketing, and analytics to make **data-driven decisions**.

---

## Dataset
The dataset contains 200 simulated users with the following fields:

| Column       | Description |
|--------------|-------------|
| user_id      | Unique identifier for each visitor |
| group        | Group assignment: A = No Discount, B = Discount |
| visited      | 1 if user visited the website |
| purchased    | 1 if user purchased, 0 otherwise |
| amount_spent | Purchase value in ₹ (0 if not purchased) |

---

## Analysis Steps
1. Created a **Pivot Table** in Excel:  
   - Count of visitors per group  
   - Sum of purchases  
   - Sum of amount spent  
   - Calculated **Conversion Rate (CR)**  

2. Visualized insights:  
   - **Bar chart** comparing conversion rates (Group A vs Group B)  
   - **Column chart** comparing total revenue  

3. Business insights:  
   - **Conversion Rate:** 8% → 12% (A vs B)  
   - Discount banners increased conversions by 50%  
   - Total revenue also improved with discounts  

---

## Key Learnings
- How to design and analyze **A/B tests** in Excel  
- Practical use of **Pivot Tables, calculated fields, and charts**  
- Translating data insights into **business decisions**  

---

## Next Steps
- Extend analysis using **Python/Jupyter** for statistical significance testing (z-test / chi-square)  
- Test additional variables like **different discount percentages or banner designs**  

---

**Technologies:** Excel, Pivot Tables, Charts  
