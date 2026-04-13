# E-commerce Data Analysis & A/B Testing

## 📌 1. Project Overview
This project analyzes user behavior in an e-commerce platform and evaluates the effectiveness of a new website version (Version B) using A/B testing.

The goal is to determine whether Version B improves conversion rate and to provide data-driven recommendations for business decisions.
## 🎯 2. Business Problem
The company launched a new website interface (Version B) and wants to evaluate whether it performs better than the current version (Version A) in terms of conversion rate.

### Key question:
Should the company roll out Version B to all users?.
## 📊 3. Dataset
- Simulated A/B testing dataset (10,000 users)
- Features:
  - user_id
  - group (A/B)
  - device (mobile/desktop)
  - day
  - converted (0/1)
## 🛠 4. Tools & Technologies
- SQL (SQLite): Data extraction & aggregation
- Python (Pandas, Statsmodels): Data analysis & statistical testing
- Power BI: Dashboard visualization
## 🔄 5. Workflow
### 5.1 Load raw CSV data into a SQLite database
### 5.2 Use SQL to extract key metrics (conversion rate, segmentation, trend)
### 5.3 Perform statistical analysis in Python:
- Z-test
- Confidence interval
- Effect size (Lift)
- Power analysis
### 5.4 Visualization in Power BI
- Conversion rate comparison
- Segmentation by device
- Daily trend
## 📈 6.Key Metrics
- Conversion Rate A: ~10.4%
- Conversion Rate B: ~12.0%
- Lift: +15.9%
- P-value: 0.00902028021 (statistically significant)
- Power: 0.13 (~13%) (very low)
## 🧠 7.Key Insights
- Version B shows a higher conversion rate than Version A
- The difference is statistically significant (p < 0.05)
- The observed lift (~15.9%) suggests meaningful business potential
- However, statistical power is very low (~13%), indicating insufficient sample size
## ⚠️ 8. Important Consideration
Although the results are statistically significant, the low statistical power suggests that:
- The experiment may not be sensitive enough
- The observed effect may not be stable
- There is a risk that the result is not reproducible

Therefore, the findings should be interpreted with caution.
## 💡 9. Business Recommendations
🚫 Do NOT:
- Immediately roll out Version B to all users
- Treat the result as fully conclusive

✅ Recommended Actions:
 1. Continue the experiment: Extend the experiment duration to collect more data and improve statistical power.
 2. Increase sample size: Ensure sufficient sample size to validate the observed effect reliably.
 3. Controlled rollout (optional):
    
    If there is business urgency:
      - Deploy Version B to a small percentage of users
      - Monitor performance closely
## 📊 10. Dashboard
An interactive dashboard was built in Power BI to visualize:
- Conversion rate comparison (A vs B)
- User segmentation by device
- Conversion trends over time

## 🚀11. Project Impact
- Demonstrates end-to-end data analysis workflow
- Applies statistical testing in real-world scenarios
- Shows ability to balance data insights with business risk
## 📬 12. Contact
- Name: Nhat Anh Dinh
- Email: nhatanhd96@gmail.com
- GitHub: https://github.com/DinhNhatAnh
