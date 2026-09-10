# Analysis of Global Emission Trends and Drivers
Data was extracted from the OWID(Our World in Data) co2 data repsository, which contain information on CO2 emissions on over 164 countries, and other variables such as year, is
o code, population, GDP, co2, co2-per-capita, energy-per-capita, and energy-per-GDP.

# Link to Dataset

https://github.com/owid/co2-data/blob/master/owid-co2-data.csv
https://github.com/owid/co2-data/blob/master/owid-co2-codebook.csv

# Top Emitters: Total vs. Per Capita
Which countries emit the most CO2, and are their differences in when measuring for emission-per-capita?
The top 10 largest emitters of CO2 from greatest to least were China, US, India, Russia, Japan, Indonesia, Iran, Saudia Arabia, South Korea, and Germany.
Interestingly, the list changes when measuring CO2-per-capita: Qatar, Kuwait, Brunei, Bahrain, Trinidad and Tobago, Saudi Arabia, United Arab Emirates, New Caledonia, Sint Maarten, and Oman in order from greatest to least. 

# Global Emissions Over Time
A graph was created to examine how global CO2 emissions have chagned thoughout history. The data goes back from 1750 to 2024. Global emissions are near xzero until around 1850, likley due to the INdustrial Revolution. There is a sharp increase in emissions after 1950, to today.

# Correlation Between Wealth and Emissions
Is there relationship between a country's wealth and CO2 emissions per person? There is a strong correlation, with a few outliers. Sweden, France, and Switzerland are countries that have low emissions but are extremely wealthy. There are signs that other energy sources that are clean and renewable are being used more in these nations.

# Decoupling Economic Growth and CO2 emissions
It is possible for a country to see GDP increase whilst still cutting CO2 emissions. The UK's GDP and CO2 rose together through the industrial era, then there is a decoupling around 1970. Since 1970, GDP doubled while the country's CO2 emissions decreased by more than half. Note that his emission is based of territory and not consumption.

# Predicting Per-Capita Emissions using Linear Regression
Simple ML techniques were used to determine what features are best in order to predict a country's per-capita emissions. Please note that traditional feature selection techniques were not used, but rather were chosen based off what assumptions. Multiple linear regression using GDP-per-capita, energy-per-capita, and energy per GDP, with a correlation coefficientent of 0.43 was found. When standardizing the coeffiencts, it was shown that energy consumption per capita was the most significant feature. Note that this model explains only 43% of variation, so other features must be looked at for a fuller picture.



