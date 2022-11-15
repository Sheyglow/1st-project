# Analyzing Unicorn Companies
# Background
A unicorn company, or unicorn startup, is a private company with a valuation over USD1 billion. As of March 2022, there are 1,000 unicorns around the world.
Popular former unicorns include Airbnb, Facebook and Google. Variants include a decacorn, valued at over USD10 billion, and a hectocorn, valued at over USD100 billion.<br />
Which industries are booming? Where should your next investment be? With the rise of the ‘amateur investor’ and the availability of platforms enabling people to invest and sell stock in public companies, it’s never been a better time to understand the financial performance of companies across the globe!

# Field Description
Below are their unicorns database, which contains the following tables:

Dates:<br />
Column	Description<br />
company_id:	A unique ID for the company.<br />
date_joined:	The date that the company became a unicorn.<br />
year_founded:	The year that the company was founded.<br />

Funding:<br />
Column	Description<br />
company_id:	A unique ID for the company.<br />
valuation:	Company value in US dollars.<br />
funding:	The amount of funding raised in US dollars.<br />
select_investors:	A list of key investors in the company.<br />

Industries:<br />
Column	Description<br />
company_id:	A unique ID for the company.<br />
industry:	The industry that the company operates in.<br />

Companies:<br />
Column	Description<br />
company_id:	A unique ID for the company.<br />
company:	The name of the company.<br />
city:	The city where the company is headquartered.<br />
country:	The country where the company is headquartered.<br />
continent:	The continent where the company is headquartered.<br />

# Project Objective
Using a PostgreSQL database you’ll be able to analyze information about unicorn companies worth over $1 billion! You’ll find out which industries have the highest average valuation and then zoom in on these to determine how many new unicorns have been produced annually between 2019 and 2021!<br />
As the firm is interested in trends for the top-performing industries, your results should be displayed by industry, then year in descending order.

# Data sourcing
The dataset was gotten from Datacamp projects.

# Insights
The data was analysed using SQL and visualized by Power BI
