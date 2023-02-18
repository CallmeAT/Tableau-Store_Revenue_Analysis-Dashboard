I created this dashboard in Tableau as part of my #TableauProject. It analyzes store revenue according to states, months, region, product category and gender.
The project's dataset consists of information gathered from superstore orders, which was cleaned and visualized using the KPIs listed below:

Statewise Revenue: Here I have taken into account the total revenue earned by different states. Wherever the sales are high, the concentration of the colors is high.

Revenue by Age: We are looking for a histogram to show the revenue by age, and since AGE is a measure, Tableau wants to perform a function on it. 
So I created an Age Range bins, size of the bins is the difference between the age. Here, I have set the difference as 10, so the ages are in the range of 10.

Monthly Revenue: This visualisation shows total revenues based on the month of the year. The revenues can be filtered according to product category.

Quantity & Discount% Interdependence: This visualisation shows that there is a pattern formed here. As the Discount% is increasing, the Quantity ordered is likely increasing. 
There is a positive correlation between the 2 fields.

Revenue by Region: In this visualisation, I have created a 'Donut Chart' by creating a calculated field with 0 axis. 
This helps us get 2 charts, and we can remove all the attributes and values from the 2nd chart and overlap it with the 1st chart. I have merged this chart by using 'Dual Axis'.

Revenue by Category and Gender: Since 'Butterfly chart' is not a part of Tableau's built-in feature. I have created a 'Butterfly chart' by creating a calculated field. I have used a formula here for formulating thesales revenue of Female and Male customers.
Formula:
IF [Gender] = 'M' THEN [Total] END
IF [Gender] = 'F' THEN [Total] END

Using the 'donut chart' calculated field, we can put the category between male and female revenue to make it appear as a butterfly chart.

------------------------------
I created this dashboard in Tableau as part of my #TableauProject. It analyzes store revenue according to states, months, region, product category and gender.

The project's dataset comprises information gathered from superstore orders, which was cleaned and visualized using the KPIs listed below:

State-wise Revenue:

Revenue by Age

Monthly Revenue

Quantity & Discount% Interdependence

Revenue by Region

Revenue by Category and Gender



Here, I experimented with a butterfly chart and a donut chart.

Learning to create new charts was a lot of fun.

I think these dynamic dashboards let you see your data visually, apply filters as needed, and click to explore the underlying data in more detail.  



I believe that an interactive dashboard is a tool for managing corporate data that enables users to engage with information by tracking, analyzing, checking, and displaying important business KPIs.

Please let me know what you think...


#business #data #learning #project #tableau 




-----------------------------


Statewise Revenue
Revenue by Age
Monthly Revenue
Quantity & Discount% Interdependence
Revenue by Region
Revenue by Category and Gender