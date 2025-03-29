# AtliQ Hospitality Analysis - PowerBI

## Problem statement

Atliq Grands owns multiple five-star hotels across the Country. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, Atliq Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of Atliq Grands wanted to incorporate “Business and Data Intelligence” in order to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them insights from their historical data.

## Task List
You are a data analyst who has been provided with sample data and a mock-up dashboard to work on the following task.

Create the metrics according to the metric list.
Create a dashboard according to the mock-up provided by stakeholders.
Create relevant insights that are not provided in the metric list/mock-up dashboard.


## Provided Mock-up Dashboard:

![mock up dashboard_atliq grands](https://github.com/user-attachments/assets/bc26ef11-5e63-41b2-ad82-a5191cee4b5c)

## Data Model

![Data Model](https://github.com/user-attachments/assets/430504ec-5b05-49b9-aa65-2b1ba3d0631d)

## Overall Analysis View


## Monthly Analysis View


## Learnt things from this Project 
- Learnt to build a new visual (Calendar visual) using matrix table, which can be utilized for different purpose of analyze. ([Article referred](https://www.linkedin.com/pulse/calendar-matrix-syed-ahmed-ali/?trackingId=VgyLpo%2BYxVRs8tD03PXcPQ%3D%3D))
- By referring different cancellation polices followed by different hotels, understood that most of the hotels charge zero fee, only if the booking is cancelled before three months of booking date. If the booking is cancelled after that, the charge range from 60 to 90% of the booking cost.
- Learnt, how to use bookmarks and selection for different purposes. (Page navigation and clear filter button in the dashboard was achieved using bookmarks and selection. website like page navigation [YouTube tutorial](https://www.youtube.com/watch?v=xCSYLrcLW00)   )
- Tried using color palette and stick with that colors throughout the dashboard ([Color palette link](https://colorhunt.co/palette/06113cff8c32ddddddeeeeee))

## Some Important insights from the Dashboard

- Mumbai generates the highest revenue (669 M) followed by Bangalore, Hyderabad and Delhi
- 
- AtliQ Exotica performs better compared to all 7 type of properties with 320 Million revenue, rating 3.62, occupancy percentage 57 and cancellation rate as 24.4%.
- AtliQ Bay has the highest occupancy of 66%
- Week 24 recorded the highest revenue among all, which is 139.6 Million
- Delhi tops both in occupancy and rating followed by Hyderabad, Mumbai, Bangalore
- AtliQ lost around 298 Million in cancellation 
- Elite type rooms has the most booking and as well higher cancellation rate

  ## Metric List
Revenue:	To get the total revenue_realized

Total Bookings:	To get the total number of bookings happened

Total Capacity:	To get the total capacity of rooms present in hotels

Total Succesful Bookings:	To get the total succesful bookings happened for all hotels

Occupancy %	:"Occupancy means total successful bookings happened to the total rooms available(capacity)"

Average Rating:	Get the average ratings given by the customers

No of days:	"To get the total number of days present in the data. In our case, we have data from May to July. So 92 days."

Total cancelled bookings:	To get the"Cancelled" bookings out of all Total bookings happened

Cancellation %:	"calculating the cancellaton percentage."

Total Checked Out:	To get the successful 'Checked out' bookings out of all Total bookings happened

Total no show bookings:	"To get the""No Show"" bookings out of all Total bookings happened (""No show"" means those customers who neither cancelled nor attend to their booked rooms)"

No Show rate %	calculating the no show percentage.

Booking % by Platform	"To show the percentage contribution of each booking platform for bookings in hotels."
Booking % by Room class:	"To show the percentage contribution of each room class over total rooms booked."

ADR: "Calculate the ADR(Average Daily rate). It is the ratio of revenue to the total rooms booked/sold. It is the measure of the average paid for rooms sold in a given time period"
Realisation %: "calculate  the realisation percentage. It is nothing but the succesful ""checked out"" percentage over all bookings happened."

RevPAR: "Calculate the RevPAR(Revenue Per Available Room) RevPAR represents the revenue generated per available room, whether or not they are occupied. RevPAR helps hotels measure their revenue generating performance to accurately price rooms. RevPAR can help hotels measure themselves against other properties or brands."

DBRN: "calculate DBRN(Daily Booked Room Nights)This metrics tells on average how many rooms are booked for a day considering a time period"

DSRN: "calculate DSRN(Daily Sellable Room Nights). This metrics tells on average how many rooms are ready to sell for a day considering a time period"

DURN	"calculate DURN(Daily Utilized Room Nights). This metric tells on average how many rooms are succesfully utilized by customers for a day considering a time period"

Revenue WoW change %: "To get the revenue change percentage week over week."

Occupancy WoW change %:	"To get the occupancy change percentage week over week."

ADR WoW change %:	"To get the ADR(Average Daily rate) change percentage week over week."

Revpar WoW change %:	"To get the RevPar(Revenue Per Available Room) change percentage week over week."

Realisation WoW change %:	"To get the Realisation change percentage week over week."

DSRN WoW change %:	"To get the DSRN(Daily Sellable Room Nights) change percentage week over week."
