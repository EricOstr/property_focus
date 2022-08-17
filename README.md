# Property Focus

This Webapp ranks properties for sale in Helsinki by the predicted return on equity (ROE) achieved if the properties for sale were bought and subsequently rented out.

This is an unfinished project (contains bugs!), see development here: [www.property-focus.com](https://www.property-focus.com/home). The data is stale as the database has not been refreshed.

The Webapp [accepts search parameters](#advanced-search) and assumes certain values, such as amount of downpayment, mortgage interest rate and predicted rental income, to deduce the most attractive ROE opportunities. Key assumption being the predicted rental income. This is predicted by a Random Forrest model, for which the driving independent variables are floor space, number of rooms, and location - defined by the label given by an upstream K-means clustering model. For a detaile description of how ROE is calculated, you can download the corresponding [excel file](#downloadable-excel-1), which details the financial model used and financing schedule. 

Users can deep dive the analysis on [specific properties](#inidivudal-property-page-1) and test different payoffs with varying assumption values. It is also possible to go directly to the property listing to contact the seller.

Users can [create profiles](#user-profile) and save properties for future reference.

Languages supported are English and Finnish.

Underlying code is not available.

See below for website screenshots.


### Landing Page
<img width="1437" alt="landing_page" src="https://user-images.githubusercontent.com/45294679/185247404-f6a62187-2ccc-4a3f-bd55-2a57054521d3.png">



### Search Results
![search_results](https://user-images.githubusercontent.com/45294679/185248349-c5f9bdcc-2a23-4371-981d-4a0fadb660e2.png)



### Search Parameters
![search_parameters](https://user-images.githubusercontent.com/45294679/185248398-9e2c6bd6-e659-4459-afa1-1872e0bfbb2f.png)



### Advanced Search
![advanced_search](https://user-images.githubusercontent.com/45294679/185248451-e9d7df00-e3ca-4715-91ea-2676875819fc.png)



### Inidivudal Property Page 1
![prop_1](https://user-images.githubusercontent.com/45294679/185248540-77738cca-6875-43e6-b170-d9d503f38d4c.png)



### Inidivudal Property Page 2
![prop_2](https://user-images.githubusercontent.com/45294679/185248585-e2faf833-c0bd-44f7-869b-80edadba25b9.png)



### Inidivudal Property Page 3
![prop_3](https://user-images.githubusercontent.com/45294679/185248637-38092ef2-90a0-4638-8e0b-02b7b6251e2d.png)



### Downloadable Excel 1
![excel_1](https://user-images.githubusercontent.com/45294679/185248926-9582d22f-345f-4100-b3d3-fd9a1dd828e8.png)



### Downloadable Excel 2
![excel_2](https://user-images.githubusercontent.com/45294679/185249017-9eded8aa-abd2-40de-88b2-e0b4421c7d14.png)



### User Profile
![profile](https://user-images.githubusercontent.com/45294679/185248684-796b2507-31f8-41fb-9061-fd280207788c.png)


