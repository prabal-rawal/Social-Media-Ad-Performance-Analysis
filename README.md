# Social-Media-Ad-Performance-Analysis

**Dataset**
--

# **Social Media Buying Dataset**


## Data Description
This dataset contains information about individuals and their response to a particular advertisement campaign on social media. The dataset includes the following columns:

* **Age:** Age of the individual in years.
* **EstimatedSalary:** Estimated salary of the individual.
* **Purchased:** Binary variable indicating whether the individual made a purchase (1) or not (0) after seeing the advertisement.

## Column Descriptions
i. **Age:**

Data Type: Integer Description: Represents the age of the individual in years.

ii. **EstimatedSalary:**

Data Type: Integer Description: Indicates the estimated salary of the individual.

iii. **Purchased:**

Data Type: Integer (0 or 1) Description: Indicates whether the individual made a purchase (1) or not (0) after seeing the advertisement.

## **Additional Information**
This dataset can be used to analyze the relationship between age, estimated salary, and purchase behavior in response to the advertisement. The dataset appears to be suitable for binary classification tasks, where the goal might be to predict whether an individual will make a purchase based on age and estimated salary. Exploratory data analysis (EDA) techniques can be applied to understand patterns and correlations within the dataset before building predictive models.

------------

**Observations and Insights:**
--

### **Age and Purchase Behavior**:

* The age distribution shows a fairly normal spread, with a wide range of ages represented in the dataset.

* There is no apparent skewness or outliers in the age distribution .

* Older individuals tend to have a stronger correlation with making purchases compared to younger individuals.
* Age can be a significant predictor of purchase behavior based on this correlation.
### **Estimated Salary and Purchase Behavior:**

* The wide range and variability in estimated salaries suggest diverse economic backgrounds among individuals.

* Individuals with higher estimated salaries may have a higher propensity to make purchases,but this relationship needs further analysis.
* Estimated salary shows a weaker correlation with purchase behavior compared to age.
* While higher estimated salaries may be associated with a slightly higher likelihood of making purchases, the relationship is not as strong as age.
----------------
### **Targeting Strategies:**

* Targeting strategies for social media ads could consider personalized approaches based on age and estimated salary segments.
--------------

**Customer Behavior Analysis for Social Media Ads**
--
This notebook delves into an examination of customer behavior related to social media ads, utilizing data encompassing age, estimated salary, and purchase behavior (`Purchased`). Key insights derived from this analysis include:

- The dataset comprises 400 samples, detailing features such as age and estimated salary.
- Notably, age displays a moderately positive correlation 📈 (`0.622454`) with the propensity for making a purchase (`Purchased`), suggesting that older individuals exhibit a higher likelihood of purchasing.
- Additionally, estimated salary shows a positive albeit weaker correlation (`0.362083`) with purchase behavior.

## **Logistic Regression Model**

We applied logistic regression for binary classification 🗠 aimed at predicting purchase behavior (`Purchased`).

The model achieved an accuracy rate of 65% 📊, underscoring its efficacy in forecasting whether a customer will make a purchase based on age and estimated salary.

## **Decision Tree Classifier Model**

We also implemented a Decision Tree Classifier for binary classification 🗠 to forecast purchase behavior (`Purchased`).

This model attained an impressive accuracy rate of 94% 📊, further substantiating its capability in predicting customer purchase decisions using age and estimated salary.
