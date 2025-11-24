# MIT Certificate Projects

This repository contains projects completed as part of the **Data Science and Machine Learning: Making Data-Driven Decisions** course from MIT IDSS. The projects demonstrate hands-on skills in data wrangling, exploratory analysis, predictive modeling, recommendation systems, customer segmentation, and machine learning workflows using Python, Jupyter Notebooks, SQL, and scikit-learn.

---

## Projects Overview

### 1. Amazon Product Recommendation System

**Objective:**  
Build a recommendation system to suggest products to customers based on their previous ratings.

**Context:**  
With the exponential growth of information and products online, consumers face too many choices. Recommendation systems help provide personalized suggestions to users. E-commerce companies like Amazon use advanced algorithms to predict shopping preferences and deliver relevant product recommendations. This project focuses on building a recommendation model using Amazon’s electronic product ratings dataset.

**Dataset:**  
- `userId` – Unique identifier for each user  
- `productId` – Unique identifier for each product  
- `Rating` – User rating for the product  
- `timestamp` – Time of rating (not used in this project)  

**Tech Stack:**  
- Python, Pandas, NumPy  
- Jupyter Notebook  
- Recommendation system algorithms (collaborative filtering)  

**Highlights:**  
- Built an end-to-end recommendation system pipeline  
- Implemented collaborative filtering for personalized recommendations  
- Analyzed user-product interactions to extract meaningful insights  

**Folder:** `Amazon_Reccomendation_System`  
**Notebook:** `Recommendation_Systems_Learner_Notebook.ipynb`

---

### 2. ExtraaLearn Customer Conversion Prediction

**Objective:**  
Build a machine learning model to identify which leads are most likely to convert to paid customers and understand the key factors driving conversion. This helps the company allocate resources effectively and target high-potential leads.

**Context:**  
The EdTech industry has grown rapidly, especially during the Covid-19 pandemic, attracting numerous leads through digital marketing, social media, websites, and apps. ExtraaLearn is a startup offering programs in cutting-edge technologies and needs to prioritize which leads to engage based on their likelihood to convert.

**Dataset:**  
The dataset contains attributes of leads and their interactions with ExtraaLearn:

- `ID` – Unique lead identifier  
- `age` – Lead's age  
- `current_occupation` – 'Professional', 'Unemployed', or 'Student'  
- `first_interaction` – Lead's first interaction channel ('Website', 'Mobile App')  
- `profile_completed` – Percentage of profile completed (Low, Medium, High)  
- `website_visits`, `time_spent_on_website`, `page_views_per_visit` – Web interaction metrics  
- `last_activity` – Most recent interaction with ExtraaLearn  
- `Email Activity`, `Phone Activity`, `Website Activity` – Interaction type flags  
- `print_media_type1`, `print_media_type2` – Seen ads in Newspaper or Magazine  
- `digital_media`, `educational_channels`, `referral` – Lead source indicators  
- `status` – Whether the lead converted to a paid customer  

**Tech Stack:**  
- Python, Pandas, NumPy, scikit-learn  
- Jupyter Notebook  
- Classification algorithms for lead conversion prediction  

**Highlights:**  
- Cleaned and preprocessed multi-source lead interaction data  
- Built predictive models to identify leads with high conversion probability  
- Analyzed feature importance to profile high-value leads  

**Folder:** `Customer_Personality_Segmentation`  
**Notebook:** Included within the folder

---

### 3. Customer Personality and Behavior Segmentation

**Objective:**  
Analyze customer data to identify distinct segments based on demographics, personality traits, and purchasing behavior. The goal is to enable personalized marketing campaigns, improve retention strategies, and optimize resource allocation.

**Business Context:**  
Understanding customer personality and behavior is pivotal for businesses to enhance customer satisfaction and revenue. A leading retail company seeks deeper insights into customer profiles to tailor marketing campaigns, identify high-value groups, and create loyalty programs. Segmentation allows the company to move from generic strategies to personalized approaches, gaining a competitive edge in the retail space.

**Dataset:**  
The dataset contains historical data on customer demographics, personality traits, purchasing behaviors, and interactions with marketing campaigns. Key attributes include:

1. **Customer Information:** ID, Year_Birth, Education, Marital_Status, Income, Kidhome, Teenhome, Dt_Customer, Recency, Complain  
2. **Spending Information (Last 2 Years):** MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds  
3. **Purchase and Campaign Interaction:** NumDealsPurchases, AcceptedCmp1–5, Response  
4. **Shopping Behavior:** NumWebPurchases, NumCatalogPurchases, NumStorePurchases, NumWebVisitsMonth  

**Tech Stack:**  
- Python, Pandas, NumPy, scikit-learn  
- Jupyter Notebook  
- Clustering algorithms (e.g., K-Means, Hierarchical Clustering)  
- Data visualization for segment analysis  

**Highlights:**  
- Preprocessed customer demographics and transactional data  
- Applied clustering techniques to identify distinct customer segments  
- Provided actionable insights on segment characteristics, enabling personalized marketing strategies  

**Folder:** `Potential_Customer_Prediction`  
**Notebook:** Included within the folder

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/spennyfinn/MIT_Certificate_Projects.git
