# **Personal Loan Data Analysis Project**

### Project Overview

The objective of this project is to analyze personal loan data for Universal Bank to identify potential target customers for future loan campaigns. By exploring the demographics, product usage, and customer behavior, the analysis aims to provide actionable insights to enhance the effectiveness of targeted marketing campaigns.

**Problem Statement**:

Universal Bank wants to increase the customer base for its personal loans by designing a focused marketing strategy based on insights from past campaigns.

Datasource-[Download Here](https://docs.google.com/spreadsheets/d/1b71bS0rthpDq0WqF4JbUYgOZrt4I111D/edit?usp=drive_link&ouid=105485232698880748717&rtpof=true&sd=true)

View Dashboard file-[Download Here](https://docs.google.com/spreadsheets/d/1X_Gp2-blk_kzZ8FA1bO35KLYpv_VlA5J/edit?usp=drive_link&ouid=105485232698880748717&rtpof=true&sd=true)

![BANK PROJECT-EXCEL DASHBOARD](https://github.com/user-attachments/assets/5f633ca7-0ac2-4af2-83d3-60ba9685f292)



### **Data Cleaning Steps Added**

### **1. Correcting Negative Values in Experience**

- Issue: Negative values were found in the `Experience` field, which is logically incorrect.
- Resolution: Replaced all negative values with the **median experience** of 20 years, as it represents the central tendency of the dataset.

### **2. Correcting ZIP Code Errors**

- Issue: A missing digit was identified in some `ZIP Code` entries (e.g., `9307` instead of `93070`).
- Resolution: Corrected `9307` to `93070` by computing and verifying with known ZIP Code patterns in the dataset's geographic area.

### **Impact of These Steps on Data Quality**

- **Improved Consistency:** Ensured all values in `Experience` are realistic and reflect actual years of professional experience.
- **Enhanced Accuracy:** Corrected ZIP Code formatting improves location-based segmentation and regional analysis.
- **Reliability:** These corrections make the data ready for generating actionable insights without errors impacting results.



### **Data Description**

The dataset contains information on 5000 customers, including:

- **Demographics**: Age, income, ZIP code, education, family size, and work experience.
- **Bank Relationship**: TD account ownership, securities account, CD account, credit card usage, and online banking.
- **Campaign Response**: Whether the customer accepted the personal loan in the last campaign.

Of the 5000 customers, only **480 (9.6%)** accepted the personal loan offer in the previous campaign.



### **Descriptive Statistics on Data**

Key descriptive insights from the dataset include:

- **Median Income**: Customers with loans have a higher median income compared to those without loans.
- **Family Size**: Families with 3–4 members are more likely to take loans compared to smaller families.
- **Work Experience**: Loan adoption rates are highest for customers with 0–10 years of work experience.
- **Education Levels**: Loan adoption is more common among Graduate and Professional customers than Undergraduates.
- **TD Account Ownership**: Customers with TD accounts are significantly more likely to take loans.



### **Key Analyses and Insights**

### **1. Income Analysis**

- Customers with personal loans have a **significantly higher median income** compared to those without loans.
- Loan adoption rates are highest among customers earning **$100K+ per year**, with a **36.14% adoption rate**, compared to the aggregate **9.6% rate**.

**Actionable Insight**:

Focus marketing efforts on high-income customers for better success rates.



### **2. Age and Income Analysis**

- Middle-aged customers (31–50 years) earning **$100K+ per year** show the highest loan adoption rates:
    - **31–40 years**: 59.7% adoption rate.
    - **41–50 years**: 51.9% adoption rate.

**Actionable Insight**:

Target middle-aged high-income earners for loan campaigns.



### **3. ZIP Code Analysis**

- Customers in ZIP Code **94720** have the highest loan adoption rate (**11.24%**), followed by **94305** and **95616**.
- These ZIP codes also have a large customer base.

**Actionable Insight**:

Implement referral programs in these ZIP codes, incentivizing current customers to refer neighbors.



### **4. Work Experience Analysis**

- Loan adoption is highest among customers with **0–10 years of work experience** (10.83%), indicating that younger professionals may be more inclined to take loans.

**Actionable Insight**:

Tailor loan products for younger professionals to align with their financial needs.


### **5. Education and Family Size Analysis**

- **Education**: Loan adoption is higher among Graduate (12.97%) and Professional customers (13.66%) compared to Undergraduates (4.44%).
- **Family Size**: Families with **3 or 4 members** show higher loan adoption rates compared to smaller families.

**Actionable Insight**:

- Design campaigns targeting Graduate and Professional customers.
- Customize loan offers for larger families (3–4 members) as they may have greater financial needs.



### **6. TD Account and Income Category Analysis**

- **TD Account Holders**: Customers with a term deposit have a **46.36% adoption rate**, much higher than the overall rate of **9.6%**.
- **Income Interaction**:
    - Customers with **$100K+ income and a TD account** have the highest adoption rates (**79.87%**).
    - Customers with **$100K+ income and no TD account** also show high adoption (**29.53%**).

**Actionable Insight**:

Focus campaigns on:

1. Customers with **$100K+ income and a TD account**.
2. Customers with **$100K+ income and no TD account**.
3. Customers with **$51K–100K income and a TD account**.



### **Additional Business Insights**

### **Cross-Selling Opportunities**

Customers with existing bank products such as TD accounts, securities accounts, or credit cards are slightly  more likely to respond to cross-selling efforts due to their established relationship with the bank.

**Recommendation**:

Cross-sell personal loans to these customers by highlighting complementary benefits.

### **Analyze Further**

Most customers with **securities accounts** (88.51%) still do not opt for personal loans.

**Recommendation**:

Investigate potential barriers, such as customer awareness, product fit, or eligibility criteria, to improve conversion rates in this segment.


### **Final Recommendation**

Focus the next marketing campaign on **1284 targeted customers** from the following categories:

- **$100K+ income with a TD account**.
- **$100K+ income without a TD account**.
- **$51K–100K income with a TD account**.

These categories represent only **25.68% of the total customer base (1284 out of 5000)**, yet they account for **94% of loan adopters (451 out of 480)**.

By narrowing the focus, the bank can optimize campaign costs and maximize the likelihood of success, assuming the remaining 833 customers in this group are more likely to accept based on observed patterns.


### **Conclusion**

While 451 customers have already accepted the offer, the strategy focuses on identifying similar profiles among the non-accepting customers (833), aiming for a higher likelihood of conversion compared to the broader population.

The analysis identifies **income**, **TD accounts**, and **customer demographics** as key drivers of loan adoption. By targeting high-potential customer groups and addressing barriers for certain segments (e.g., securities account holders), the bank can improve its ROI on marketing campaigns. This focused strategy ensures resources are utilized effectively while maximizing customer conversions.
