# SUPER_STORE_ANALYSIS - REPORT

### DASHBOARD LINK : https://app.powerbi.com/groups/me/reports/82786cc2-e357-4261-8d58-1a1fae961bca/419f75cf3e3c1d63d863?experience=power-bi

# Objective of the Project
The objective is to analyze this data and provide actionable, data-driven recommendations to guide Super Store.

### STEPS FOLLOWED :

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.

- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".

- Step 4 : It was observed that in none of the columns errors & empty values were present.

- Step 5 : Checked and corrected the data-types of columns and also corrected the Date Format of Date columns . 

- Step 6 : Now we go to the report view next and select a background to start adding our visuals.

- Step 7 : We add 3 card Visuals to represent produsts sold, products returned and best selling products.

- Step 8 : Two line charts are added to represent the total sales and total profit

- Step 9 : Visual filters (Slicers) were added for four fields named "State", "Year", "Month" & "Quarter".

- Step 10 : Two Donut charts were added to the report design area representing the sales amount by category and the sales amount by segment.

- Step 11 : A bar chart was also added to the report design area representing the total sales by each sub-category

- Step 12 : A ribbon chart was also added to the report design area representing the region wise sales

- Step 13 : And finally we add a shape map to the report design are representing the state wise sales.

- Step 14 : In the report view, under the insert tab, a text boxe was added to the canvas,we added super store sales report to the text box.

- Step 15 : In the report view, under the insert tab, using image option icons were added to the report design area.


- Step 16 : A new calculated table was created through dax expression for a new calendar table which contains all the dates from oldest till latest date present in the records .

**DAX EXPRESSION FOR CREATING NEW CALENDAR TABLE :**

<img width="294" height="55" alt="image" src="https://github.com/user-attachments/assets/a39d02af-fb5b-440f-872d-1e214f4afc0c" />

Snap of new Calendar Table ,

<img width="127" height="527" alt="image" src="https://github.com/user-attachments/assets/5bf7e4a1-f902-4d30-98bb-85e73a59bbaf" />


- Step 15 : A new calculated columns were added to the new calendar table

(a). Year Following DAX expression was written,

<img width="299" height="54" alt="image" src="https://github.com/user-attachments/assets/9324e483-ac52-4354-b820-d44e1d56c728" />

(b). Quarter Following DAX expression was written, 

<img width="435" height="51" alt="image" src="https://github.com/user-attachments/assets/9a247ee5-1bab-42ae-add4-6a72019cfbd5" />

(c). Month Following DAX expression was written,

<img width="388" height="58" alt="image" src="https://github.com/user-attachments/assets/b49716cb-cde6-47ec-9855-b030338b03a2" />

(d). Month Number Following DAX expression was written,

<img width="357" height="55" alt="image" src="https://github.com/user-attachments/assets/558ce2b3-73c2-4846-8faa-9a8143d15f72" />

Snap of all the columns ,

<img width="491" height="560" alt="image" src="https://github.com/user-attachments/assets/b7077ec8-d702-4b60-aa79-6c7af8fe0967" />


- Step 16 : The Following measures were created in a new table named Metrics .

(a) BEST SELLING PRODUCT 
<img width="916" height="48" alt="image" src="https://github.com/user-attachments/assets/2674911a-c7ba-4e20-b2f3-8847a369d93f" />


(b) Total Sales

<img width="293" height="47" alt="image" src="https://github.com/user-attachments/assets/20d98539-562b-4db6-850b-c9a0329ee4cd" />


(c) Total Profit

<img width="309" height="44" alt="image" src="https://github.com/user-attachments/assets/652dddf9-68ea-4940-baa6-94c48e5be970" />


(d) Last Year Sales

<img width="543" height="133" alt="image" src="https://github.com/user-attachments/assets/f72fe11e-3c88-44a1-b59b-3248e26b6a56" />


(e) Last Year Profit

<img width="527" height="128" alt="image" src="https://github.com/user-attachments/assets/93fcfafe-433f-4ae0-bfd1-d6bbca4955d2" />


(f) PRODUCTS SOLD

<img width="319" height="36" alt="image" src="https://github.com/user-attachments/assets/2ec5e2ee-31db-45bb-a1a2-05552a77bd6b" />


(e) PRODUCTS RETURNED

<img width="606" height="93" alt="image" src="https://github.com/user-attachments/assets/91fefb79-ce62-475a-a8fa-33f675444b0b" />


(f) YOY Sales_Growth

<img width="486" height="47" alt="image" src="https://github.com/user-attachments/assets/5f006993-3d67-46a5-bf27-1985b4ab419c" />


(g) YOY Profit_Growth

<img width="581" height="37" alt="image" src="https://github.com/user-attachments/assets/dea1e761-7b99-4382-ad30-af1d19e4c46b" />



(h) Sales Main Title


<img width="467" height="109" alt="image" src="https://github.com/user-attachments/assets/aa60157c-5d49-4e36-a003-5d81e44852f6" />

(i) Sales Sub Title 

<img width="318" height="73" alt="image" src="https://github.com/user-attachments/assets/a0c27985-d929-447f-be42-26bb3e962f5c" />


the previous 2 measures were used to customize our line chart which represents total sales over a perod.


Lets take a look at our customized visual.

<img width="311" height="182" alt="image" src="https://github.com/user-attachments/assets/1e99ada8-735b-432f-9ce4-13bf34867715" />


(j) Profit Main Title

<img width="503" height="108" alt="image" src="https://github.com/user-attachments/assets/81e94555-4624-4fe9-8e4a-5ddb28517cde" />


(k) Profit Sub Title

<img width="321" height="69" alt="image" src="https://github.com/user-attachments/assets/b2650d8b-4e6d-4754-9252-d7befda8c78e" />


Similarly the previous 2 measures were used to customize our line chart which represents total profit over a perod.


Lets take a look at our customized visual,


<img width="312" height="182" alt="image" src="https://github.com/user-attachments/assets/0f1ab2f3-dfbf-4a94-b08e-6ed82bee5439" />


- Step 18 : The report was then published to Power BI Service.


# Publishing to Power-Bi-Service 

<img width="641" height="407" alt="publish status" src="https://github.com/user-attachments/assets/40fef70f-3168-4240-a055-55ba00fdd576" />

# Snapshot of Dashboard (Power BI Service)

<img width="1882" height="900" alt="image" src="https://github.com/user-attachments/assets/2493e521-809f-4c44-b68e-f5ee56522fb8" />



# Report Snapshot (Power BI DESKTOP)

<img width="1467" height="785" alt="pbid" src="https://github.com/user-attachments/assets/cae7ff99-4349-4399-bef9-4063ca1f01aa" />


# Key Points

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

Total Number of Products Sold = 38k

Number of Products Returned = 296

Total sales = 2,297.2k

Total profit = 286.4k


## 1. Focus on High-Performing Products:

### Insight:

Phones and Chairs are currently the top-performing sub-categories, contributing significantly to overall sales. The store should continue to invest in these categories by exploring opportunities to expand their product lines, enhance marketing efforts, and maintain competitive pricing.

### Recommendation:

Consider bundling these top products with related accessories or services to increase the average order value and enhance customer satisfaction.


## 2. Address Underperforming Categories:

### Insight:
Appliances and Bookcases are lagging in sales, indicating potential issues such as low demand, ineffective marketing, or misaligned product offerings.

### Recommendation:
Conduct market research to understand customer preferences and identify the reasons for low sales in these categories. Based on findings, either improve the product offerings or reallocate resources to more profitable categories.


## 3. Regional Strategy Optimization:
### Insight:
Sales vary significantly across different states and regions, suggesting that certain areas may be underperforming due to untapped market potential or ineffective sales strategies.
### Recommendation: 
Analyze the specific characteristics of underperforming regions to tailor marketing campaigns, optimize inventory distribution, and explore local partnerships. Additionally, consider introducing region-specific promotions to boost sales.

## 4. Enhance Customer Segmentation:
### Insight: 
Sales contribution from different customer segments reveals an opportunity to realign marketing efforts to target the most profitable segments more effectively. There may also be untapped potential in underperforming segments.
### Recommendation: 
Implement targeted marketing campaigns that focus on the most profitable customer segments. Additionally, explore personalized offers or loyalty programs to increase engagement with these key customer groups while also trying to convert underperforming segments into higher-value customers.

## 5. Improve Profit Margins:
### Insight:
Despite strong sales, profit margins are under pressure, likely due to high operational costs, inefficient pricing strategies, or the focus on lower-margin product categories. 
### Recommendation:
Reevaluate pricing strategies, particularly for lower-margin products, and consider adjusting prices to better reflect their value. Additionally, identify and reduce unnecessary operational costs, such as excess inventory or inefficient supply chain practices.

## 6. Reduce Product Returns:
### Insight: 
The return of 296 products indicates a potential issue with product quality, customer expectations, or purchase experience. 
### Recommendation: 
Analyze return data to identify common reasons for returns. If quality issues are identified, work with suppliers to address them. For mismatches in customer expectations, improve product descriptions, images, and customer education efforts. Implement a more transparent and efficient return policy to enhance customer satisfaction while reducing return rates.

## 7. Leverage Best-Selling Products for Cross-Selling Opportunities:
### Insight: 
Staples are identified as the best-selling product. This popularity can be leveraged to cross-sell related items. 
### Recommendation:
Develop cross-selling strategies where customers purchasing Staples are recommended complementary products, increasing the overall basket size and profitability. By addressing these insights, the "Super Store" can optimize its sales strategies, improve profitability, and enhance customer satisfaction, ultimately leading to more sustainable growth.




