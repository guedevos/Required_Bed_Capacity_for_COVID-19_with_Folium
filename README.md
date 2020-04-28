# Required_Bed_Capacity_for_COVID-19_with_Folium
Calculation of Required Bed Capacity for COVID-19 and Visualization with Folium

* ### **Weekly Surveillance Summary of U.S. COVID-19 Activity**

All the exclusive information is obtained from the following links.

References:
- https://www.cdc.gov/mmwr/volumes/69/wr/mm6915e3.htm 
- https://www.cdc.gov/coronavirus/2019-ncov/covid-data/covidview/index.html

Although it varies according to factors such as age and region, the overall cumulative hospitalization rate is 29.2 per 100,000.

It varies for hospitalization rate of confirmed cases too. Age is the most effective feature for hospitalization. This rate will decrease as the number of cases increases, so I will use it as 16.5%.

Closed cases/Total cases ratio is around 17.6%. (24.04.2020)

* ### **Bed Occupancy in Hospitals**

Bed occupancy rate is between 65-
70% in U.S. 
Rates for other countries can be found in the following links.

References:
- https://www.statista.com/statistics/185904/hospital-occupancy-rate-in-the-us-since-2001/
- http://www9.who.int/bulletin/volumes/88/8/09-073361/en/
- https://gateway.euro.who.int/en/indicators/hfa_542-6210-bed-occupancy-rate-acute-care-hospitals-only/


* ### **USA State Borders**

References:
- https://github.com/PublicaMundi/MappingAPI/blame/master/data/geojson/us-states.json
