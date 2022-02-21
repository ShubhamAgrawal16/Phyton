#AIM
Data Analysis process on brand comparison for two flipkart products(Redmi and Samsung)

#DESCRIPTION
Collecting data of mobiles of two different brands from the flipkart website( Redmi and Samsung) . Analyzing and comparing the price difference in both the brands with same specifications. Finding out the better brand of mobile to buy according to the price and ratings. For this we use Primary data source for collecting the raw data by using the web scraping methods to finding out the flipkart website 
from bs4 import BeautifulSoup as s
from urllib.request import urlopen as u
by using above two lines of code we can use the beautiful soup as s and requesting the url of the websites by from urllib.request import urlopen
After this collecting the data of both the mobiles we use dictionary for creating it in a dataframe so that we can easily use data analysis process on our collected raw data 
we can start with  the data preparation, data preprocessing, , data cleaning ,EDA(Exploratary data analysis) process , Model building purpose.
This was the simple steps of doing data analysis process since we use concat function for concatenation of two dataframe for the process . 
For Visualization we use Matplotlib and Seaborn type of python libraries for finding the results. 
This is a simple project based on the Pandas(Jupyternotebook).

#Conclusion
#By comparing both the mobiles on flipkart(Redmi and Samsung)
1. The costliest mobile was Redmi as compared with samsung.
2. In Redmi the most soldout model is M1 11x 5G.
3. In Samsung the most soldout model is F12.
4. Black is the most soldout color.
5. Lowest model in Samsung is Metro 313.
6. Lowest model in Redmi is 7A.
7. Maximum rating was in 4.2 
