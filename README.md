In this task, I analyzed a sales dataset using Python libraries including pandas, sqlite3, and matplotlib. I began by importing the CSV file named sales_data (1).csv, which contains details such as the date, product category, region, units sold, sales revenue, and profit. After successfully loading the data into a pandas DataFrame, I established a connection to a SQLite database using sqlite3. Although I didn’t create a table manually, the dataset could be stored in the database using df.to_sql() if needed. I executed multiple SQL queries to gain insights from the data. These included calculating the total quantity sold and total revenue grouped by product category, by product category and region, and by region individually. The results were then visualized using bar charts in matplotlib, where I plotted both the quantity sold and revenue for each product category. These visualizations provided a clear and effective summary of the sales performance across various categories and regions.
