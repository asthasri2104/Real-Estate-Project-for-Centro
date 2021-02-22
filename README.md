# Real-Estate-Project-for-Centro

**Background**
Real estate is the largest asset class in the world and plays a crucial role in the U.S. economy. Most
real estate firms have made decisions in the past based on intuition, experience, and historical data.
Today, with the availability of modern tools and the huge amount of high-quality data that has never
been collected before at a reasonable cost, it is possible for such firms to better understand how
properties are priced and make informed decisions accordingly.
Centro is a data-driven asset management company based in Miami, Florida, which focuses on the
acquisition and management of apartment communities and shopping centers throughout the
Southeast United States and Texas. It has so far raised and deployed $150M in 4 years and is looking
for potential avenues to expand the business. Given the nascent stages of data-driven quantitative real
estate investment, the company wants to stay ahead of the curve by understanding the key variables
that are, if not directly affecting rent and sale prices, good indicators of them. The ultimate goal is to
create an automated evaluation model that will not only help the company make more lucrative
decisions but also speed up the decision-making process.

**About the Problem**
The client wants to identify key indicators of rent and sale price by analyzing two datasets of over
20,000 rental properties in Texas, Florida, Georgia, and North Carolina which include hundreds of
fields such as property location, construction material, unit size, rent per square foot, and last sale
price. They would also like to stitch this data with external data from publicly available data sources
to better capture the supply and demand of the market.

**Solution**
This report is based on the study that was conducted over 20,000 rental properties in Texas, Florida,
Georgia, and North Carolina and identifies 29 critical features that are functional indicators in
predicting rent price. The raw dataset provided by the client includes hundreds of columns of information on rental
properties ranging from property location to unit size. Exploratory data analysis and visualizations of
the data uncovered anomalies present within variables as well as correlations between variables. Such
findings led to the urge for using _**linear regression**_ to test the observed patterns, and to potentially
reveal unobserved ones.
In preparation for modeling, the original data was cleaned, transformed, and then supplemented with
external data that captures the demographics and affluence of the population in the area. A total of 24
numerical variables alongside six categorical variables were tested against average effective rent per
square foot. Twenty-nine out of the thirty variables tested turned out to be significant indicators of
rent.
Using the linear regression model as the foundation, an excel based price prediction tool prototype
was developed for Centro (the client) that takes features of a rental property as input and calculates
estimated rental income and suggests sale price as output. Centro can improve its return on investment
by using this tool to find properties that are highly underpriced.
It is important to note that there are limitations to this study. In order to achieve better prediction
accuracy, the client can work on improving data quality, including more data on properties or
variables, and incorporating longitudinal data in future studies.
