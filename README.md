# DS8007_Airbnb_Toronto_EDA

## Background

	Since 2008, Airbnb has been a popular method to look for traveling possibilities. As of end of 2021, it has six-millions of active listings worldwide, more than one-hundred-thousands of cities and towns with active Airbnb listings [Dgomonov, 2019], one-hundred-fifty billions were earned by hosts [Airbnb Newsroom, 2022].
  
## Purpose

	The purpose of this project is to provide insights for both customers and hosts. Mainly for hosts, will have a better business insight. Business insights such as, which neighbourhood have most listings? When is the period of busy of off season? What does name and description for popular listings looks like? What is most frequently used words? etc. For customers, price related questions will be answered. Such as how does price change during the year? Will price be higher when it comes to weekends? etc. 
  
## Methodology

	The tools used were Jupyter notebook and python, and data visualizations will be implemented by matplotlib and seaborn python packages. The data comes from the Airbnb public data, http://insideairbnb.com/get-the-data/. Data files used in this project were listings and calendar. The raw listings is a csv file and contains 74 attributes and 15084 observations, however for this project, listings will be referenced to a data frame with only 1 columns and 15084. Since other attributes were irrelevant to the project, they were dropped during the data preprocessing. The 11 attributes from listings were:  id, accommodates, description, host_name, neighbourhood_cleansed, latitude, longitude, room_type, price, number_of_reviews, reviews_per_month. The 8 attributes are listing_id, date, available, price, adjusted_price, minimum_nights, maximum_nights, weekday.
  
  
  
Reference

About us. Airbnb Newsroom. (2022, February 24). Retrieved March 9, 2022, from
 https://news.airbnb.com/about-us/ 


Cooper, C. (2017, April 25). Neighbourhood profile: Central willowdale (Yonge & Finch). GTA Real Estate News | Presented by Living Realty. Retrieved April 13, 2022, from 
https://news.livingrealty.com/neighbourhood-profile-central-willowdale/#:~:text=The%20stretch%20of%20Yonge%20between,all%20within%20steps%20of%20home. 


Get the Data. Inside Airbnb. (n.d.). Retrieved April 13, 2022, from 
http://insideairbnb.com/get-the-data/ 
