## Identification of Potential Customers from Website Visitors
### Project Overview
- This Project was built to help Companies identify potential Customers who will actually buy their product apart from people just visiting their website.
- A large number of Categorical columns with high variance was present in the dataset, which was handled using appropriate Reduction Techniques and **One-Hot Encoding**.
- Automated Feature Selection was done using **sklearn's RFE**.
- The final model was built using **Logistic Regressor** which was able to assign a score from **0 to 100** to every person visiting the website, based on their potential to turn into a Customer. The Company can then use this score to concentrate more on potential Customers.
- The model built was able to identify 81% of the Potential Customers accurately.

## EDA:
![customer](/images/eda.jpg)
![heatmap](/images/heatmap.jpg)
## Insights:
**`The features positively contributing to Conversion of Leads are:`**
- Total Time Spent on Website
- Lead Origin_Add Forms/Imports
- What is your current occupation_Working Professional
- Last Activity_SMS Sent
- TotalVisits
- Lead Source_Welingak Website
- Lead Source_Olark Chat

#### When leads spend more time on the website, or their origin is from Add forms/ imports, or the last activity is a SMS sent, or the source of the lead is Olark Chat/ Welingak Website , or their total visits to the website is high, they are more likely to get converted to customers.

**`The features inversely contributing to Conversion of Leads are:`**
- Lead Source_Facebook
- Last Activity_Email Bounced
- Last Notable Activity_Modified
- Last Activity_Olark Chat Conversation


#### When lead source is from Facebook or leads' last activity is Email Bounced/ Olark Chat Conversation or the last notable activity is modified, then there are less likely chances that they would get converted to customers.
