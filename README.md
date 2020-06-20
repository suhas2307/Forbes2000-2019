Problem Statement
Analysis of the Forbes2000 companies 2019 list to derive conclusions based on Profits, Market cap, Assets and Revenue.

Goals of the Analysis
•	Find the Top 10 companies based on market cap, profits, sales and assets – Horizontal bar chart
•	Visualise profit by sectors across continents 
•	Visualise which sectors are heavily represented in the Top 2000 companies – Histogram 
•	Find the correlation between profits vs market cap and profits vs assets – Scatter Plot with regression 
•	Plotting Heat map based on profits and market cap 
•	Applying markers on the map for the headquarters of the company – for exploration
•	Text pertaining to the data for the selected country

Description of Data Analysis Tools
•	Read the input csv file using Pandas and load the data into Postgres database

•	Through Flask connect to the database using SQLAlchemy and select the records

•	Jsonify the data and return it to be used in JavaScript as an API call

•	Create a Dashboard for Visualizations using HTML

•	Visualizations will be rendered using Leaflet.js, Plotly and D3.js

