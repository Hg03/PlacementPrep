## CheatSheet

![alt text](https://github.com/Hg03/PlacementPrep/blob/main/assets/1.jpeg)

![alt text](https://github.com/Hg03/PlacementPrep/blob/main/assets/2.jpeg)

![alt text](https://github.com/Hg03/PlacementPrep/blob/main/assets/3.jpeg)

## Practice Queries

**1. Write a query that identifies cities with higher than average home prices when compared to the national average. Output the city names.**

**Steps -**
- National average value is only one right ??
- We have to compare every city's average value with national average value.
- Group by city and compare the avg market price with national average market price.

**Schema**

Tables:
<zillow_transactions>
id                  int
state               varchar
city                varchar
street_address      varchar
mkt_price           int

```sql
select city
from zillow_transactions
group by city 
having avg(mkt_price) > 
(select avg(mkt_price) from zillow_transactions)
```
**2. Find the date with the highest total energy consumption from the Meta/Facebook data centers. Output the date along with the total energy consumption across all data centers.**

**Steps -**


**Schema**

fb_eu_energy, fb_asia_energy, fb_na_energy
date            datetime
consumption     int




[Video Playlist to refer](https://youtube.com/playlist?list=PLdrw9_aIADIO_l7hCd4xiJ2mBwiOb4jkU)
