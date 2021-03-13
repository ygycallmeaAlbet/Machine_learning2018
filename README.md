# UW STAT 444 Final Project Winter 2019

Short Description
=============
**Goal:** Predict house price
**Methods:** smoothing, random forest, and boosting. Other methods are optional.
**Scoring Metric:** RMLSE, which is the Root-Mean-Squared-Error (RMSE) between the (natural) log of the predicted value and the log of the observed sales price

Data
====
The housing_price data is a cleaned subset of the [D.C. Residential Properties Kaggle dataset](https://www.kaggle.com/christophercorrea/dc-residential-properties), where you can find detail descriptions of the variables. Briefly, it contains information about single- unit single-building non-condo residential properties. The response is PRICE.

Description of variables
---------------------------

* Id
* BATHRM: Number of Full Bathrooms
* HF_BATHRM: Number of Half Bathrooms (no bathtub or shower)
* HEAT: Heating
* AC: Cooling
* ROOMS: Number of Rooms
* BEDRM: Number of Bedrooms
* AYB: The earliest time the main portion of the building was built
* YR_RMDL: Year structure was remodeled
* EYB: The year an improvement was built more recent than actual year built
* STORIES: Number of stories in primary dwelling
* SALEDATE: Date of most recent sale
* PRICE: Price of most recent sale
* GBA: Gross building area in square feet
* STYLE: Style
* STRUCT: Structure
* GRADE: Grade
* CNDTN: Condition
* EXTWALL: Extrerior wall
* ROOF: Roof type
* INTWALL: Interior wall
* KITCHENS: Number of kitchens
* FIREPLACES: Number of fireplaces
* USECODE: Property use code
* LANDAREA: Land area of property in square feet
* FULLADDRESS: Full Street Address
* ZIPCODE: Zip Code
* NATIONALGRID: Address location national grid coordinate spatial address
* LATITUDEP: Latitude
* LONGITUDE: Longitude
* ASSESSMENT_NBHD: Neighborhood ID
* ASSESSMENT_SUBNBHD: Subneighborhood ID
* CENSUS_TRACT: Census tract
* CENSUS_BLOCK: Census block
* WARD: Ward (District is divided into eight wards, each with approximately 75,000 residents)
* QUADRANT: City quadrant (NE,SE,SW,NW)
* fold: A variable for k-fold corss validation
