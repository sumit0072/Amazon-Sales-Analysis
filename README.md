<h1>Amazon Sales Data Analysis</h1>
<h2>Amazon</h2>
<p>Amazon.com is an ecommerce platform that sells many product lines, 
including media (books, movies, music, and software), apparel, baby products,
consumer electronics, beauty products, gourmet food, groceries, health and 
personal care products, industrial & scientific supplies, kitchen items, 
jewelry, watches, lawn and garden items, musical instruments, sporting goods, 
tools, automotive items, toys and games, and farm supplies and consulting 
services.</p>
<h2>Business Problem</h2>
<p>Sales management has gained importance to meet increasing competition and 
the need for improved methods of distribution to reduce cost and to increase 
profits. Sales management today is the most important function in a 
commercial and business enterprise.</p>
<ul>
    <li>Do ETL : Extract-Transform-Load some Amazon dataset and find for me</li>
    <li>Sales-trend : month wise , year wise , yearly_month wise</li>
    <li>Find key metrics and factors and show the meaningful relationships between attributes.</li>
</ul>
<h2>Solution Dashboard</h2>
<p>Created a simple and informative dashboard about the Amazon Sales Analysis</p>
<a href="https://app.powerbi.com/viewr=eyJrIjoiNmRlMDg1NTktNWQxNy00YTQxLWJmNmYtODY2NmU2NDM0NGYyIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9&pageName=ReportSectionaed43aaac5d19943ebec"><img src="https://github.com/sumit0072/Amazon-Sales-Analysis/blob/main/Screenshot%20(54).png" width="900" height="600"></a>

<h2>ETL (Extract, Transform, Load)</h2>
<p>Once I know the basic features of the data I have to work with, I 
imported the MySQL database into Power BI.</p>
<h2>Data Transformation in Power BI</h2>
<p>Once the data is imported in Power BI, we do ‘transform data’ i.e. using 
Power Query editor to perform certain operation on to the data. Ensuring 
correct data types, creating custom/conditional columns are some fundamental 
task performed in Power Query.</p>
<h2>Modeling Schema in Power BI</h2>
<p>Created 'one to many' relationship model between dimension table and 
fact table using primary key and foreign key concept.</p>
<h2>Created Measures</h2>
<p>Created required measures using aggregation, filter DAX functions.</p>
<h2>Creating a Report in Power BI</h2>
<p>A report is created in Power BI with various charts depicting Sales Trend,
Yearly Sales Trend, Monthly Sales Trend, Yearly Month wise Sales Trend, Sales
Analysis & Profit Analysis using decomposition chart, Top and Bottom 5 items
by Sales, Top & Bottom 5 items by Profit, Top 5 Sales Representative & Top 5
Customer by Sales, Relationship between Total Sales & Sales Cost, Sales & 
Discount Amount relationship by month, Sales Quantity Trend, Orders Trend and 
High Margin Items. Sales Segmentation by Total Sales, Total Profit, Total 
Orders & Sales Quantity.</p>
<p>Tabular Analysis include Item-wise total sales, total profit, sales 
quantity & orders. Also, carried out tabular analysis, for Item wise Sales
difference by year 2017 & 2019, Sales for same period last year. Carried out
tabular analysis as YTD, QTD, MTD for Orders and Sales Quantity.</p>
<h2>Deployment in Power BI</h2>
<p>In Power BI, You can directly publish the report online to your 
workstation. If you do not have the work email-id then you can save the file
in ‘.pbix’ version. This helps another viewer see your work and understand 
the story or insights you’re communicating.</p>
<h2>Insights</h2>
<ul>
<li>Yearly Sales Trend shows a drop in 2018 because we have data for only
first 3 months of 2018.</li>
<li>The 1st quarter of 2017 has the highest sales compared all other 
quarter.</li>
<li>Festival Months like March, June, August and September shows significant 
increase in number of sales.</li>
<li>Increase in the discount amount has led to increase in the sales amount
as well. Typical time period of Amazon Shopping Sale is around March, June,
August and September which boosts sales amount.</li>
<li>Item 'Better Large Canned Shrimp' is generating the highest sales and the 
highest profit. Also, the highest quantity sold for this item.</li>
<li>We are getting the highest orders for Item 'Better Fancy Canned Sardines' </li>
<li>Sales Representative id 141 has the highest sale i.e. $25.47M and Customer with
customer_key 10021485 has the highest spend i.e. $11.40M.</li>
<li>From sales segmentation we can conclude that we have more numbers of high
sales.</li>
<li>From tabular analysis of Item wise sales difference by year 2017 and 2019,
we conclude that year 2017 has marginally higher sales than year 2019.</li>
<li>We can say 4th quarter of year 2017 and 2019 have more orders compared
to all other quarters.</li>
<li>The 1st quarter of 2017 has the highest sales quantity compared all 
other quarter.</li>
</ul>

