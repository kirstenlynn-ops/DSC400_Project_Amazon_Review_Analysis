# 📦 Amazon Reviews Analysis & Dashboard (2026)
- Prepared by: Kirsten Livingston

|Project Deliverables & Repository Access                                                                |
|--------------------------------------------------------------------------------------------------------|
|GitHub Repo: https://github.com/kirstenlynn-ops/DSC400_Project_Amazon_Review_Analysis                   |
|(Contains notebooks, data work cycle, datasets throughout cleaning and feature engineering              |
|Final Static Dashboard: https://kirstenlynn-ops.github.io/DSC400_Project_Amazon_Review_Analysis/
Amazon_Reviews_Static_Dashboard.html                                                                    |
|(Final visuals and Key Insights)                                                                        |
|Project Page: https://kirstenlynn-ops.github.io/DSC400_Project_Amazon_Review_Analysis/                  | 
|(More about this project)                                                                               |


## Introduction
This report presents a comprehensive analysis of Amazon Customer Reviews, designed to extract insights from Amazon_dataset 2026 (~123 GB) created by Sahitya Sahu on Kaggle. The dataset contains millions of customer reviews, ratings, product metadata, and timestamps, many of which often contain unstructured text, missing values, and class imbalances, which complicate predictive modeling. By leveraging NLTK for text preprocessing, feature engineering, and fine-tuning DistilBERT for sentiment classification, the pipeline achieved an 82.6% accuracy on review sentiment prediction. This project’s primary goal is to demonstrate a scalable framework for converting raw review data into actionable insights. 

## 🎯 Project Goals
- Analyze customer review patterns and sentiment across product categories
- Predict product ratings from features and review text
- Identify top reviewers, products, and temporal trends in review activity
- Create a final static dashboard with clear visuals for easy review
- Demonstrate ethical handling of public dataset

## 🔍 Reserach Q & A
- **Research Question 1:**
How does review sentiment correlate with star ratings?

Answer 1:
Yes. Reviews that use more positive language usually have higher star ratings. This shows that the words people use in their reviews generally match the number of stars they give. 


- **Research Question 2:**
Do low-star reviews tend to be longer complaints? 

Answer 2:
Generally, yes. Reviews with fewer stars often include more detailed explanations or complaints, making them longer than higher-rated reviews.


- **Research Question 3:**
Are some products consistently rated higher than others? 

Answer 3:
Not exclusively, the top products all tend to be positive reviews, there is not strong enough evidence that suggest some products are rated significantly higher than others. Differences in rating apply more about the individual and sentiment than the product itself. 

- **Research Question 4:**
Do the most reviewed products receive significantly different average ratings? 

Answer 4:
No. Products with many reviews usually maintain similarity positive ratings as the other popular products. This implies that the number of reviews does not strongly affect the overall rating. 

- **Research Question 5:**
Do verified purchase reviews differ in rating compared to non-verified reviews? 

Answer 4:
Yes. Verified purchases tend to have slightly different rating patterns compared to non-verified ones. This ensures that we are focusing on authentic experiences.  

- NOTE: More Modeling Q & A was conducted. See more in the [Final Write Up](xx).
---
## 🛠 Project Workflow
|Stage (Notebook)   | Description|
|-------------------|---------------------------------------------------------     |
| NB 1              | Data ingestion & Cleaning                                    |
| NB 2              | Exploratory Data Analysis (EDA & Feature Engineering (FE)    |
| NB 3              | Visualization                                                |
| NB 3b             | Dashboard                                                    |
| NB 4              | Statistical Analysis                                         |
| NB 5              | Modeling/ Prediction & Natural Language Processing (NLP)     |                       
|Dashboard          |Summary and visual exploration                                |
|Final Write-Up     | Amazon Review Setiment & Rating Prediction                   |

## 📊 Data Source
- Dataset:
- Subset Used For Modeling:

## 🔏 Ethical Considerations $ Privacy
- This dataset is publically available, no personal or private data was used
- Reviewers were treated as behavorial data points, no sentistive information like emails or addresses were included
- Safeguards:
  - Prevent model bias against low-volumn reviewers or products
  - Avoid over-representation of frequent reviewers
  - Constant monitoring for deployment
 
## ✅ Insights & Results
- Positive correlation between review text sentiment and star ratings
- Top reviewers dominate a small portion of total reviews
- Class imbalance is significant (5-star reviews cover ~66% of the data)
- Hierarchical models improved mid-range rating prediction

## 📍 Deliverables

| Task                  | Link |
|-----------------------|------|
| Jupyter Notebooks     | [Data ingestion & Cleaning](https://github.com/kirstenlynn-ops/DSC400_Project_Amazon_Review_Analysis/tree/main/notebooks) |
| Final Report          | [EDA & Feature Engineering (FE)](#) |
| Presentation          | [Canva Presentation](#) |
| OTHER                 |                     |
| GitHub Project Page   | [More About the Project](https://kirstenlynn-ops.github.io/DSC400_Project_Amazon_Review_Analysis/) |
| Dashboard             | [Clear Visuals to show insights](https://kirstenlynn-ops.github.io/DSC400_Project_Amazon_Review_Analysis/Amazon_Reviews_Static_Dashboard.html) |                       
| Plotly Dashboard      | [Interactive visuals that display insights from the data](https://d6ecc19c-fbb6-4979-a90e-17c19e5062af.plotly.app) |

- NOTE: Plotly Dashboard may be inactive due to Plotly's free plan to create Interactive Dashboards. The Static Dashboard was created to minic the visuals and findings from the Plotly Dashboard.
