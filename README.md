# Airline Flight Operations Analytics | Power BI

## Project Overview

This project uses Microsoft Power BI to analyze airline flight operations across four airlines and five destinations. The dashboard focuses on flight volumes, on-time performance, cancellations, delays, passenger metrics, and destination-level operational patterns.

## Business Objective

To develop an interactive analytical solution that helps users compare airline performance, identify operational issues, and explore flight disruption patterns to support data-informed decisions.

## Tools & Technologies

- Microsoft Power BI
- DAX (Data Analysis Expressions)
- Data Modeling
- Interactive Dashboards and Filters
- Power BI Q&A and Key Influencers, as described in the project report

## Key Performance Indicators

The initial project report records the following metrics:

| KPI | Reported Value |
|---|---:|
| Total Tickets Booked | 50 |
| Total Airlines | 4 |
| Total Operating Flights | 78 |
| Passenger Load | 100 |
| On-Time Flight Rate | 53.85% |
| Cancellation Rate | 29.49% |
| Delayed Flight Rate | 16.66% |
| Total Destinations Covered | 5 |

*Note: These are values from the initial report and require validation against the Power BI model before being treated as final results.*

## Dashboard Features

- On-time flight monitoring
- Airline-level performance comparisons
- Destination-wise flight classification
- Cancellation and delay analysis
- Key Influencers visual
- Q&A functionality
- Interactive dashboard filters
- Airline operations monitoring

## Initial Observations

The initial analysis reported that:
- Airline A operated 22 flights.
- Phoenix and Houston were reported among the busiest destinations, with 20 flights each.
- Chicago recorded the highest number of cancellations, with seven reported cancellations.
- Airline D was reported to have the highest delayed-flight rate in the airline comparison.

These findings should be verified against the underlying data and final measures before publication.

## DAX and Data Modeling

The project uses DAX measures and a dedicated `Flight_Passenger` table to support operational analysis.

Examples of calculations include:
- Distinct flight counts
- Total cancelled flights
- Total on-time flights
- Cancellation and on-time rates
- Passenger counts by airline
- Ticket counts

## Interactive Power BI App

[Open the Airline Operations Power BI App](https://app.powerbi.com/Redirect?action=OpenApp&appId=b9d7508e-51f6-4288-b58f-ba5331720071&ctid=276e0cb4-cbcf-4a5a-8266-cd933c139077)

Access may depend on Power BI permissions and the availability of the published app.

## Repository Structure

- `powerbi/` - Power BI report file
- `screenshots/` - Page previews
- `documentation/` - Project report and supporting documentation

## Future Improvements

- Validate KPI definitions and airline-level calculations.
- Investigate cancellation and delay patterns by destination.
- Improve data model consistency and DAX measure documentation.
- Add verified operational recommendations based on the final results.

## Author

Saumya Lahri
