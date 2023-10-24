# rockbuster_stealth
Concept project on **product analysis** using SQL to inform a fictional company's transition from a chain of physical stores into an online video rental platform
## Context
Rockbuster Stealth LLC is a fictional movie rental company that used to have stores around the world. 
Facing competition from streaming services such as Netflix and Amazon Prime, the Rockbuster Stealth management team is planning to use its existing movie licenses to launch an online video rental service in order to stay competitive.

For the purpose of this excercise, I was hired as a data analyst by Rockbuster Stealth's business intelligence (BI) department to help wiht the launch strategy for the new online service. 

## Objective
The Rockbuster Stealth Management board has asked a series of business questions to which they expect data-driven answers to use for their 2020 company strategy The main questions they would like answered are:
* Which movies contributed the most/least to revenue gain?
* What was the average rental duration for all videos?
* Which countries are Rockbuster customers based in?
* Where are customers with a high lifetime value based?
* Do sales figures vary between geographic regions?

## Data
The data set used for this excercise was provided by Rockbuster along with the Project Brief. It contains information about Rockbuster's film inventory, customers, and payments among other things. 

The data was loaded into a PostgreSQL database in order to carry out the analysis. 

The database contains the following tables: 

### Fact Tables
* Payment
* Rental
### Dimension Tables
* store
* film_actor
* inventory
* film_category
* customer
* staff
* actor
* film
* category
* address
* language
* city 
* country
## Visualizations
Visualizations were created in Tableau.

[Rockbuster map](https://public.tableau.com/shared/RKJQ5848X?:display_count=n&:origin=viz_share_link)

[Revenue analytics](https://public.tableau.com/views/revenueanalytics/BestandWorstTitlesbyRevenue?:language=en-US&:display_count=n&:origin=viz_share_link)
