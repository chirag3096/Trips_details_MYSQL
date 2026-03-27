## Trips Details- MySQL Data Analysis Project

## Problem: 
A ride-hailing platform needed to analyze trip operations, driver performance, payment behavior, and booking conversion rates to identify operational inefficiencies and improve platform performance.

## Tools:
MySQL · DDL/DML · Joins · Subqueries · Aggregate Functions · Views

## Database Structure
Designed and managed a relational MySQL database with 5 interconnected tables:
Table --  Key Fields
Trip  --  strip_id, fare, fare_method, driver_id, cust_id, distance, duration
Trip Details --  Searches, estimates, quotes, cancellations, OTP, ride completion
Location  --  Area mapping for pickup/drop
Duration  --  Trip duration categories
Payment  --  Payment method mapping


## Business Questions Solved (20+)

## Operations & Volume
#Total trips, completed trips, total distance travelled
#Average fare per trip, average distance per trip
#Which duration category had the most trips

## Driver & Customer Analysis
#Top 5 earning drivers
#Which driver-customer pair had the most repeated orders
#Total bookings cancelled by driver vs customer

## Payment & Revenue
#Total earnings across all trips
#Most used payment method
#Fare distribution by duration category

## Location Intelligence
#Top 2 locations by trip volume
#Area with highest trips by duration

## Conversion Funnel Analysis
#Search → Estimate rate
#Estimate → Quote rate
#Quote acceptance rate
#Quote → Booking rate
#Overall platform conversion rate

## Key Insights
Identified the top 5 revenue-generating drivers — actionable for incentive planning
Conversion funnel analysis revealed drop-off points between search and booking — critical for product optimization
Location-duration matrix uncovered peak demand zones for fleet allocation



