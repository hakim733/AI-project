# Building a Data-Driven Future: Predicting soda Sales with Linear Regression

Country Beeristan, a high potential market, accounts for nearly 10% of Stallion & Co.’s global beer sales. Stallion & Co. has a large portfolio of products distributed to retailers through wholesalers (agencies). There are thousands of unique wholesaler-SKU/products combinations. In order to plan its production and distribution as well as help wholesalers with their planning, it is important for Stallion & Co. to have an accurate estimate of demand at SKU level for each wholesaler.

Currently demand is estimated by sales executives, who generally have a “feel” for the market and predict the net effect of forces of supply, demand and other external factors based on past experience. The more experienced a sales exec is in a particular market, the better a job he does at estimating. Joshua, the new Head of S&OP for Stallion & Co. just took an analytics course and realized he can do the forecasts in a much more effective way. He approached me, to transform the exercise of demand forecasting.

## data

The following data were provided :
price_sales_promotion.csv: (hectoliter) Holds the price, sales & promotion in dollar value per hectoliter at Agency-SKU-month level
historical_volume.csv: (hectoliters) Holds sales data at Agency-SKU-month level from Jan 2013 to Dec 2017
weather.csv: (Degree Celsius) Holds average maximum temperature at Agency-month level
industry_soda_sales.csv: (hectoliters) Holds industry level soda sales
event_calendar.csv: Holds event details (sports, carnivals, etc.)
industry_volume.csv: (hectoliters) Holds industry actual beer volume
demographics.csv: Holds demographic details (Yearly income in $)

## Test data Formats
Volume_forecast.csv: You need to first forecast the demand volume for Jan’18 of all agency-SKU combination.
sku_recommendation.csv: Secondly, you need to suggest 2 SKUs which can be sold by Agency06 & Agency14. These two agencies are new and company wants to find out which two products would be the best products for these two agencies.


 Then, I tackled this real-world machine learning challenge: accurately predicting soda sales at the SKU level for thousands of wholesaler-product combinations.

Leveraging the power of linear regression, I developed a model that outperformed traditional sales forecasting methods. By analyzing historical sales data, market trends, and external factors, I was able to build a robust model that provides valuable insights into future demand.

Key achievements:

Improved forecasting accuracy: Our model significantly reduced forecast errors, leading to more efficient inventory management and reduced stockouts.
Enhanced decision-making: The model empowers sales executives to make data-driven decisions, optimizing sales strategies.
Streamlined operations: By automating the forecasting process, we saved time and resources.
Technical skills:

Python
NumPy
Pandas
Scikit-learn
Linear Regression

