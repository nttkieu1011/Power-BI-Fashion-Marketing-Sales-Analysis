# Power BI-Fashion Marketing and Sales Analysis

## What I learned from this project:
- **Working with a non-standard data model:** Understanding how to analyze and build a Power BI solution when the dataset does not follow a traditional star or snowflake schema.
- **Applying Design Thinking to data analysis:** Translating business problems into analytical questions and structuring the analysis around stakeholder needs.
- **Storytelling with data:** Designing a logical flow from high-level performance to campaign and product-level analysis.
- **Turning insights into actions:** Using analytical findings to develop actionable marketing recommendations rather than stopping at descriptive insights.
- **Understanding Marketing Analytics:** Exploring key concepts such as advertising spend, Ads Sales, ROAS, budget utilization, campaign performance, and product-level marketing efficiency.

## I. Introduction
### 1. Introduction to Dataset
- Dataset: Fashion Market & Sales in 5/2024.
- Consists of 4 data tables
    - Table 1: mkt_camp_by_sku_cost
    - Table 2: mkt_camp_cost
    - Table 3: orders
    - Table 4: danh sach san pham
### 2. Data Dictationary
<img width="856" height="470" alt="image" src="https://github.com/user-attachments/assets/8b1e952a-1905-413d-b837-e7f934f2fecd" />

### 3. Business Question
**Question 1:** Is advertising spending generating sufficient revenue for the business?

**Question 2:** Which campaigns are using the marketing budget effectively, and where is budget utilization or performance falling short?

**Question 3:** Does a high-performing campaign necessarily mean that all products within the campaign are performing effectively?

## II. Design thinking Method
Here are four stages of design thinking:

**Stage 1 - Empathize:** Understand the perspective and information needs of a Marketing Manager who needs to evaluate whether the marketing budget is being used effectively.

<img width="766" height="250" alt="image" src="https://github.com/user-attachments/assets/ddf5637f-d509-4ef1-bca7-12b9460f931a" />

<img width="765" height="397" alt="image" src="https://github.com/user-attachments/assets/6fe38c5c-f300-43b1-9821-853852a457c4" />

**Stage 2 - Define Point of View:** Define the core analytical problem: Marketing performance is not only about generating revenue, but also about allocating and utilizing the advertising budget effectively.

<img width="889" height="358" alt="image" src="https://github.com/user-attachments/assets/ab6ac5c0-bed2-4f82-bb7b-53e0f0c66b0f" />

**Stage 3 - Ideate:** Translate the business problem into analytical questions around overall marketing performance, campaign efficiency, and product-level effectiveness.

<img width="698" height="307" alt="image" src="https://github.com/user-attachments/assets/fefde7dd-03bd-49bf-960a-2b2c17ec9a8a" />

**Stage 4 - Prototype & Review:** Develop a Power BI dashboard with four analytical pages: Overview, Campaign, Product, and Recommendation. And review the dashboard to improve clarity and usability.

<img width="697" height="102" alt="image" src="https://github.com/user-attachments/assets/d21470fb-488c-4315-950c-4364106ce4e2" />

## III. Visualization

**Overview**

<img width="961" height="533" alt="image" src="https://github.com/user-attachments/assets/37ab3107-b043-4f54-ad1f-0c0abe332206" />

**Campaign**

<img width="958" height="537" alt="image" src="https://github.com/user-attachments/assets/ec677811-c696-4542-a1ad-d3a1a0879123" />

**Product**

<img width="957" height="534" alt="image" src="https://github.com/user-attachments/assets/db67d9e7-c5fc-45f8-853c-5ab1696b9891" />

**Recommendation**

<img width="963" height="533" alt="image" src="https://github.com/user-attachments/assets/e8a70c53-d114-4157-87a6-007ea63c8fcb" />

## IV. Insights & Recommendation.
**Key 1:** During May, the business spent approximately **VND 394 million** on advertising and generated **VND 3.02 billion in Ads Sales**, resulting in an overall **ROAS of 7.67**. Marketing efficiency also improved over time, with ROAS increasing from **5.72 in the first week to 9.05 in the final week —>** advertising generated strong returns overall, with efficiency improving toward the end of the month.

**Key 2:** Ads Sales contributed more than **50% of total sales over time** and represented the majority of sales in **5 out of 8 categories**. However, marketing effectiveness was not consistent across campaign types, with differences in both **ROAS and revenue contribution —>** a strong overall marketing result does not necessarily imply that all campaign types are equally effective.

**Key 3:** The business utilized approximately **82.75% of its allocated advertising budget**. Campaign-level budget utilization was left-skewed, with a relatively large number of campaigns spending below **80% of their allocated budget** —> budget allocation and utilization are not evenly distributed across campaigns, creating an opportunity to identify campaigns that should be scaled, monitored, or optimized.

Based on two measures — **ROAS** and **budget utilization** — that were classified into five actionable groups:

<img width="768" height="257" alt="image" src="https://github.com/user-attachments/assets/2e8b35fb-982a-4a90-91ef-45e93090b072" />


