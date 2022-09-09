
# Airbnb Exploratory Data Analysis

Airbnb is a for-profit service that links homeowners with travellers searching for lodging. Airbnb encourages its hosts to set the pricing for their units with the aid of a few guidelines that allow hosts to compare their listings to others in the area to decide a reasonable price.

This exploratory data analysis showcases area traffic, different comparison between prices and localities in the New York region. This study also gives relationships between parameters such as reviews, minimum nights spent and prices spent by travellers in comparison to selective locality in New York.

As a result, the most popular and busy area observed is Manhattan, with average price of $150 , “Entire home/Apt” or “Private Room” in room listing type. Generally travellers prefer to stay in areas with lower prices.

To obtain above conclusions data analysis is done by grouping and sorting relevant parameters. For behavioural observations different plots have been marked. This EDA challenges hosts and Airbnb to focus on most traffic making areas and how they can improve business in least busy areas.



## Problem Statement

On the other hand, guests who use Airbnb frequently experience lodging issues for a variety of reasons. Seasonal rushes, unforeseen cancellations of reservations, host preferences, etc. may all fall under this category.

As airbnb seeks to learn more about its services and service providers, data will be analysed in accordance with the following questions.

**Q.1** Which are the busiest or least busy areas according to customers and why?

**Q.2** Which hosts are the busiest and why?

**Q.3** Is there any noticeable difference of traffic among different areas and what could be the reason for it?

**Q4.** What can we learn from prices, area & reviews from a given dataset?

## Authors

- [@Aman Guleria](https://www.github.com/AMAN-GULERIA)
- [@Saurabh Aradwad](https://www.github.com/SaurabhAradwad)
- [@Ayush Sharma](https://www.github.com/SharmaAyush98)
- [@Rishika Rai](https://www.github.com/Rishika70)


## Referance Project Document

- [Project Report](https://docs.google.com/document/d/1mbanu4gkizrLOHRH6HMQ7F8R5-9NN6Q0-niGN-qylVg)
- [Project Summary](https://docs.google.com/document/d/1p3cOFLT8r2IEQqYt6VN15pRm08pgmH2a_VRbNvxpJK4)
- [Colab Notebook ✔](https://colab.research.google.com/drive/1V5g1DG36tKmnOIo16fTS24fcYwWPVrER)
- [Presentation PPt](https://docs.google.com/presentation/d/1UCrj69m1apzEDxoeaXlcaRbl86SRJWj8B3CENUpoI_A/edit?usp=drive_web&ouid=117820608631250670510)
## Data Summary

All columns and type of information stored in the csv file is as follows

- **Id** -unique id in the dataset
- **name**- name which is listed on Airbnb as “home/apt”,” private room”,” shared room”
- **host_id**- unique id of the host in Airbnb Dataset
- **host_name**- name of host
- **Neighbourhood_group** - areas in New York
- **Neighbourhood** - sub-areas that are located inside areas
- **latitude**- location latitude on Earth's surface
- **longitude**- location longitude on Earth's surface
- **room_type**- listed room type [‘home/apt’, ’private room’, ‘shared room’]
- **price**- price per night
- **minimum_nights** - sub areas which are located inside areas
- **number_of_reviews**- total count of reviews for listed name
- **last_reviews**- last reviews for listed name
- **Reviews_per_month** - reviews received per month
- **calculated_host_listings_count** - count of total number of listings for that host
- **availability_365** - number of available days in a year (365 Days)

## Conclusions

Airbnb is a for-profit service that links homeowners with travellers searching for lodging. Airbnb encourages its hosts to set the pricing for their units. This study gives relationships between parameters such as reviews, minimum nights spent and prices spent by travellers in comparison to selective localities in New York.

To do exploratory data analysis, we have received 49000 rows and 16 columns of csv data from Airbnb New York. Airbnb is interested in learning more about its services and service providers. We can see the data details in the data summary.

We used Numpy, Pandas, Matplotlib, Seaborn, and Folium packages for this EDA. The first inspection was performed after importing data into Pandas. We discovered some missing values. Then we cleaned up the data because missing values are treated as integer 0.

This EDA concentrated on the busiest and least busy areas, as well as hosts. We also targeted traffic in various areas. We plotted this traffic on a street view map using latitude and longitude data. We discovered the most and least preferred room types. We also learned about prices, areas, and reviews from the provided dataset.


These are the important conclusions made out of this EDA.

- Most Busiest Area(Neighbourhood_group) - Manhattan
- Least Busy Area- Staten Island
- Most preferred room type - Entire Home/ Private Room
- Least preferred room type - Shared Room
- High Traffic Area - Manhattan
- Highest reviewed area - Queens
- Avg Price in Manhattan - $150 per night
- High price density variation is found out for Manhattan
- Most of the listings have a price average of $65 per night in New York.
- Top 9 out of 10 “ Private Room” type listings are priced at $50 per night.
- Business in least busy areas can be improved by room listing type preferences and competitive pricings.
- For profitability Manhattan & Brooklyn can be focused more to work on as these areas are more popular among travellers.
- For future scope health and safety measures should be added with quality standards.
