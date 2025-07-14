# Heart Disease Risk Profiling for Insurance Pricing – Tableau Dashboard

This project analyzes heart disease risk indicators using California health data to support an insurance company’s pricing and segmentation strategy. The result is a fully interactive Tableau dashboard that visualizes high-risk cohorts and informs data-driven policy decisions.

🔗 **Live Dashboard**: [View on Tableau Public](https://public.tableau.com/app/profile/sai.nithisha.marripelly/viz/HeartDisease_keyindicators/IndicatorsofHeartDisease)

---

## 🧠 Project Objective

To help an insurance client identify customer segments at higher risk of heart disease and develop personalized pricing strategies. We analyzed demographic and clinical attributes to uncover insights and presented them through an interactive visual tool.

---

## 📊 Dataset

- **Source**: California Health Interview Survey / Heart Disease Surveillance Data
- **Format**: Cleaned `.csv` file uploaded for reference
- **Fields Include**:
  - Demographics: Age, Gender, Ethnicity
  - Lifestyle & Health: Smoking, BMI, Stroke History, Comorbidities

---

## 📈 Key Insights

- **Males** make up ~63% of stroke cases
- **Black-only, non-Hispanic** individuals show 5.5% heart disease prevalence
- **California residents** represent 5.45% of total stroke cases
- Insights support segmentation of customers into pricing and policy risk tiers

Dashboard Visualizations and Insights:
Heart Attack Percentage:

Insight: This immediately provides a high-level understanding of heart attack prevalence within the dataset, allowing for quick comparison of two distinct groups (e.g., presence vs. absence of a heart attack, or different populations). It sets the stage for deeper dives into contributing factors.

Heat Map and Risk Analysis:

Insight: These sections give a quick, summarized view of which risk factors are most pronounced or correlated. A heatmap is excellent for spotting patterns across two dimensions, helping to identify high-risk combinations at a glance.

Diseases in Different Age Groups:

Insight: By visualizing the count of diseases across various age categories for both females and males, you can identify age-specific vulnerabilities and gender differences in disease prevalence. This helps in understanding at what life stages certain diseases become more common and if there's a significant disparity between sexes.

Race-Based Analysis of Stroke Prevalence:

Insight: Focusing specifically on 'Stroke' and breaking it down by racial groups (Black, Hispanic, Multiracial, Other, White), this visualization reveals potential disparities or higher prevalence rates within specific racial communities. This is crucial for understanding health inequities and targeting interventions.

Behavioral Risk Assessment: Smoking, Drinking, and Exercise:

Insight: This section highlights the impact of lifestyle choices on health. By showing the prevalence based on smoking, drinking, and exercise habits, it helps to confirm or discover how these behaviors correlate with health outcomes, emphasizing the importance of preventative measures.

Stroke Prevalence Across United States:

Insight: The map visualization provides a geographical perspective on stroke prevalence. This allows you to identify regional hotspots or areas with lower rates, which can inform public health strategies and resource allocation specific to different parts of the country.

---

## 📊 Dashboard Features

- Developed in **Tableau**
- Filters by gender, age, ethnicity, and health indicators
- Dynamic charts for stroke rates, comorbidity risks, and demographic distributions
- Designed for underwriting and pricing strategy teams

🔗 **Live Dashboard**: [Click here to explore](https://public.tableau.com/app/profile/your-dashboard-link-here)

---

## 🛠️ Tools & Technologies

- **Tableau Public** – Interactive dashboarding
- **Excel / CSV** – Data cleaning and formatting
- *(Optional)* Python – For advanced preprocessing (if applicable)

---



Challenges Faced:
During the development of this dashboard, you tackled common challenges associated with visualizing complex datasets containing numerous categorical variables:

Challenge of Category Consolidation for Clarity: You found it essential to strategically combine existing categories (e.g., merging detailed AgeCategory bins into broader age groups or consolidating specific Diabetic sub-types). This was crucial to simplify the visualizations, reduce visual clutter, and ensure that the graphs were not overwhelmed by too many distinct segments, making the core insights more apparent to the viewer.

Challenge of Including Multiple Categorical Columns: A significant hurdle was trying to show the relationships between several different categorical columns simultaneously on a single graph. Such attempts often lead to messy, unreadable charts. You addressed this by opting for a dashboard approach with multiple, simpler visualizations, or by using interactive elements that allow users to explore different relationships one at a time, ensuring that the information remained digestible and clear.

