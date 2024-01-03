# Pizza_sales_Dasbord
Pizza Sales Dataset contain 48620 rows and 12 columns.
Columns are below mentioned.
1.	pizza_id:
•	Description: This column contains a unique identifier for each pizza, often in the form of a serial number or a code that uniquely represents a specific pizza variant. In this Dataset it is only like a serial number
•	Example: 1,2,3,4……………………………………48620
2.	order_id:
•	Description: This column represents an identifier for each order. It helps in tracking and distinguishing different orders.
•	Example: 1, 2, 2, 2, 3, 3
3.	pizza_name_id:
•	Description: This column contains unique identifiers or codes for each pizza name. It establishes a connection with the specific pizza variant.
•	Example: hawaiian_m, classic_dlx_m, five_cheese_l
4.	quantity:
•	Description: Indicates the quantity of a particular pizza variant ordered in a specific order.
•	Example: 1, 2, 3
5.	order_date:
•	Description: Represents the date when the order was placed for the specific pizza.
•	Example: 01-01-2015 to 31-12-2015
6.	order_time:
•	Description: Represents the time when the order was placed for the specific pizza.
•	Example: 13:45:00, 18:30:00
7.	unit_price:
•	Description: Denotes the price of a single unit (individual pizza) before any additional factors like quantity or size are considered.
•	Example: $10.99, $15.50
8.	total_price:
•	Description: Represents the total price of a specific pizza order, taking into account the quantity and any other relevant factors.
•	Example: $21.98, $46.50
9.	pizza_size:
•	Description: Indicates the size of the pizza ordered, such as Medium (M), Large (L), Small (S), Extra Large (XL), Extra Extra Large (XXL).
•	Example: M, L, S, XL, XXL
10.	pizza_category:
•	Description: Represents the category or type of pizza, such as classic, chicken, veggie, supreme.
•	There are 4 categories in Dataset. 
•	Example: Classic, Chicken, Veggie, Supreme
11.	pizza_ingredients:
•	Description: Contains information about the specific ingredients used in the preparation of a particular pizza.
•	Example: Sliced Ham, Pineapple, Mozzarella Cheese
	?duja Salami, Pancetta, Tomatoes, Red Onions, Friggitello Peppers, Garlic
	Bacon, Pepperoni, Italian Sausage, Chorizo Sausage
	Barbecued Chicken, Red Peppers, Green Peppers, Tomatoes, Red Onions, Barbecue Sauce
	Brie Carre Cheese, Prosciutto, Caramelized Onions, Pears, Thyme, Garlic
	Calabrese Salami, Capocollo, Tomatoes, Red Onions, Green Olives, Garlic
	Capocollo, Red Peppers, Tomatoes, Goat Cheese, Garlic, Oregano
	Capocollo, Tomatoes, Goat Cheese, Artichokes, Peperoncini verdi, Garlic
	Chicken, Artichoke, Spinach, Garlic, Jalapeno Peppers, Fontina Cheese, Gouda Cheese
	Chicken, Pineapple, Tomatoes, Red Peppers, Thai Sweet Chilli Sauce
	Chicken, Red Onions, Red Peppers, Mushrooms, Asiago Cheese, Alfredo Sauce
	Chicken, Tomatoes, Red Peppers, Red Onions, Jalapeno Peppers, Corn, Cilantro, Chipotle Sauce
	Chicken, Tomatoes, Red Peppers, Spinach, Garlic, Pesto Sauce
	Coarse Sicilian Salami, Tomatoes, Green Olives, Luganega Sausage, Onions, Garlic
	Eggplant, Artichokes, Tomatoes, Zucchini, Red Peppers, Garlic, Pesto Sauce
	Genoa Salami, Capocollo, Pepperoni, Tomatoes, Asiago Cheese, Garlic
	Kalamata Olives, Feta Cheese, Tomatoes, Garlic, Beef Chuck Roast, Red Onions
	Mozzarella Cheese, Pepperoni
	Mozzarella Cheese, Provolone Cheese, Smoked Gouda Cheese, Romano Cheese, Blue Cheese, Garlic
	Mushrooms, Tomatoes, Red Peppers, Green Peppers, Red Onions, Zucchini, Spinach, Garlic
	Pepperoni, Mushrooms, Green Peppers
	Pepperoni, Mushrooms, Red Onions, Red Peppers, Bacon
	Prosciutto di San Daniele, Arugula, Mozzarella Cheese
	Ricotta Cheese, Gorgonzola Piccante Cheese, Mozzarella Cheese, Parmigiano Reggiano Cheese, Garlic
	Sliced Ham, Pineapple, Mozzarella Cheese
	Soppressata Salami, Fontina Cheese, Mozzarella Cheese, Mushrooms, Garlic
	Spinach, Artichokes, Kalamata Olives, Sun-dried Tomatoes, Feta Cheese, Plum Tomatoes, Red Onions
	Spinach, Artichokes, Tomatoes, Sun-dried Tomatoes, Garlic, Pesto Sauce
	Spinach, Mushrooms, Red Onions, Feta Cheese, Garlic
	Spinach, Mushrooms, Tomatoes, Green Olives, Feta Cheese
	Spinach, Red Onions, Pepperoni, Tomatoes, Artichokes, Kalamata Olives, Garlic, Asiago Cheese
	Tomatoes, Anchovies, Green Olives, Red Onions, Garlic
	Tomatoes, Red Peppers, Jalapeno Peppers, Red Onions, Cilantro, Corn, Chipotle Sauce, Garlic


12.	pizza_name:
•	Description: Represents the full name or label of the pizza, providing a clear description of the pizza variant.
•	Example: The Hawaiian Pizza, The Classic Deluxe Pizza, The Five Cheese Pizza, The Italian Supreme Pizza, etc.
•	There are 32 different names of Pizza available in dataset.
	The Barbecue Chicken Pizza
	The Big Meat Pizza
	The Brie Carre Pizza
	The Calabrese Pizza
	The California Chicken Pizza
	The Chicken Alfredo Pizza
	The Chicken Pesto Pizza
	The Classic Deluxe Pizza
	The Five Cheese Pizza
	The Four Cheese Pizza
	The Greek Pizza
	The Green Garden Pizza
	The Hawaiian Pizza
	The Italian Capocollo Pizza
	The Italian Supreme Pizza
	The Italian Vegetables Pizza
	The Mediterranean Pizza
	The Mexicana Pizza
	The Napolitana Pizza
	The Pepper Salami Pizza
	The Pepperoni Pizza
	The Pepperoni, Mushroom, and Peppers Pizza
	The Prosciutto and Arugula Pizza
	The Sicilian Pizza
	The Soppressata Pizza
	The Southwest Chicken Pizza
	The Spicy Italian Pizza
	The Spinach and Feta Pizza
	The Spinach Pesto Pizza
	The Spinach Supreme Pizza
	The Thai Chicken Pizza
	The Vegetables + Vegetables Pizza

KPIs
Key Performance Indicators (KPIs) in Power BI are visualizations or metrics that provide a clear and quick view of an organization's performance against its strategic objectives. Power BI allows you to create, customize, and monitor KPIs through various visualizations and dashboards. Here's a guide on how to set up KPIs in Power BI:
Define Your KPIs:
Clearly define the key metrics that represent the performance of your business or project. These could be related to sales, revenue, customer satisfaction, project completion rates, etc.
Data Preparation:
Ensure that your data is structured appropriately and that you have the necessary datasets in Power BI to support your KPI calculations. You might need to aggregate data, create calculated columns, or transform data as needed.
Create Measures:
In Power BI, measures are used to calculate KPI values. You can create measures using the DAX (Data Analysis Expressions) language. For example, if you have a sales dataset, you might create measures for Total Sales, Average Sales, etc.
Create KPI Visualizations:
Once you have your measures in place, you can create KPI visualizations using Power BI's various chart types. Common visualizations for KPIs include cards, gauges, and tables.

Set Target Values:
KPIs typically have target values or benchmarks. In Power BI, you can set target values for your KPIs. This helps you easily compare actual performance against the desired goals.
Use Conditional Formatting:
Apply conditional formatting to your KPI visualizations to make it visually intuitive. For example, you can use colours to represent whether a KPI is above or below the target.
Create Dashboards: 
Dashboards in Power BI allow you to bring together multiple visualizations, including your KPIs, into a single view. Arrange your KPI visualizations on a dashboard for a comprehensive overview.
Drill Down:
Power BI allows users to drill down into data for more detailed analysis. Ensure that your KPI visualizations are interactive, allowing users to explore underlying data.
Schedule Data Refresh:
If your Power BI report relies on live or regularly updated data, set up a schedule for data refresh to ensure that your KPIs reflect the most current information.
Share and Collaborate:
Share your Power BI reports and dashboards with relevant stakeholders. Power BI allows for easy sharing and collaboration, making it accessible to a broader audience.
KPI are: 
Total_Revenue :	 	817.86K
Avg_Order_Value: 		38.31
Total_Pizza_Sold: 		50K
Total_Orders:			21K
Average_Pizza_per_Order:	2.32

•	The total revenue for the year was $817,860.
•	The average order value was $38.31.
•	The total number of pizzas sold was 21,350.
•	The best-selling pizza was the Classic, which made up 23.96% of total sales.
•	The busiest day of the week was Friday, followed by Saturday and Thursday.
•	The busiest month of the year was December.
Data insights :
Category	Detail	Value (Estimate)
Revenue	Total Revenue	$817,860
Revenue	Average Order Value	$38.31
Revenue	Total Pizzas Sold	21,350
Pizza Popularity	Best-Selling Pizza	Classic (23.96%)
Pizza Popularity	Second Best-Selling Pizza	Supreme (25.46%)
Pizza Popularity	Third Best-Selling Pizza	Veggie (23.68%)
Pizza Popularity	Fourth Best-Selling Pizza	Hawaiian (10.80%)
Pizza Popularity	Fifth Best-Selling Pizza	Meat Lover's (7.10%)
Pizza Size	Most Popular Size	Large (45.89%)
Pizza Size	Second Most Popular Size	Medium (30.49%)
Pizza Size	Least Popular Size	Regular (21.77%)
Day of Week Sales	Busiest Day	Friday (22.5% of weekly sales)
Day of Week Sales	Second Busiest Day	Saturday (20.8% of weekly sales)
Day of Week Sales	Third Busiest Day	Thursday (19.3% of weekly sales)
Day of Week Sales	Least Busy Day	Monday (12.7% of weekly sales)
Month of Year Sales	Busiest Month	December (20.1% of yearly sales)
Month of Year Sales	Second Busiest Month	November (16.8% of yearly sales)
Month of Year Sales	Third Busiest Month	October (15.4% of yearly sales)
Month of Year Sales	Least Busy Month	July (8.9% of yearly sales)



Here are the top 5 pizzas by revenue:
Pizza Name	Revenue
The Thai Chicken Pizza	$43,000
The Classic Deluxe Pizza	$38,000
The Barbecue Chicken Pizza	$34,000
The California Chicken Pizza	$33,000
The Spicy Italian Pizza	$31,000

Here are the top 5 pizzas sold by quantity:
Pizza Name	Quantity Sold
The Classic Deluxe Pizza	41,000
The Thai Chicken Pizza	38,000
The California Chicken Pizza	37,000
The Barbecue Chicken Pizza	36,000
The Spicy Italian Pizza	33,000

Here are the bottom 5 pizzas by revenue:
Pizza Name	Revenue
The Brie Carre Pizza	$11,600
The Spinach Pesto Pizza	$15,600
The Mediterranean Pizza	$15,400
The Spinach Supreme Pizza	$15,300
The Green Garden Pizza	$14,000

Here are the bottom 5 pizzas sold by quantity:
Pizza Name	Quantity Sold
The Brie Carre Pizza	490
The Spinach Pesto Pizza	970
The Mediterranean Pizza	934
The Spinach Supreme Pizza	950
The Green Garden Pizza	997

