# Online customer behavior analysis

### Abstract:
This project studies a public dataset collected for the article "Shopper intent prediction from clickstream e-commerce data with minimal browsing information," available under an attribution agreement in the GitHub repository "Awesome Public Datasets": (https://github.com/awesomedata/awesome-public-datasets). The dataset, which contains nearly 5.5 million data points, provides information on the actions of visitors to an online footwear store: day and time of the session, specific click actions (adding items, purchasing, viewing details, etc.), and the SKU of the products interacted with. The goal is to find relevant information that helps determine what factors contribute to a customer abandoning a shopping cart and, based on this information, propose business solutions and/or action steps to neutralize this behavior and reduce the abandonment rate.

The **churn rate** was calculated at **6.16441%**. Exploratory data analysis (EDA) yielded some relevant insights, such as the days with the highest number of churns and the time periods that concentrated the majority of these events. Recurring patterns of behavior were discovered among users who discarded purchases, allowing for the formulation of preliminary hypotheses that could be validated or discarded with the application of machine learning (ML) models.

Random Forest, Logistic Regression, and LightGBM models were applied to classify sessions that did or did not end in a purchase, and to discover which factors best predicted how each session would end. Based on the analysis, marketing and business intelligence strategies are proposed to address insights and increase the number of sessions that end in a purchase.

---------------------------------------------------

* **Data origin:** https://www.nature.com/articles/s41598-020-73622-y.epdf?sharing_token=tydJezcxTZvP8cNEDsAKn9RgN0jAjWel9jnR3ZoTv0NoB1nwg3Wgf_mP0ktAdV_HGxUxXaNdBCErP1Zck0ibhFGwRrt0xq-Uy2wNz5DkwbFN44Mxzwb3WdN593RbqBFNucB9hEgd3EFvTZaqO9reUDDlh-mybSw5d1-G04RfdBQ%3D
* **Credits:** 
Requena, B., Cassani, G., Tagliabue, J., Greco, C., & Lacasa, L. (2020). _Shopper intent prediction from clickstream e-commerce data with minimal browsing information_. Scientific Reports, 10(1). https://doi.org/10.1038/s41598-020-73622-y
