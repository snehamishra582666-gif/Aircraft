# Sky Track Analytics

## Project Overview

**Sky Track Analytics** is an interactive airline and flight performance dashboard built in **Microsoft Power BI**. It brings key flight, passenger, booking, delay, and ticket-price information into one report so users can explore airline operations and identify performance patterns.

The Power BI report contains two pages:
- **Page 1 – Dashboard:** KPI cards, charts, and slicers for exploring flight performance.
- **Page 2 – Analysis Questions:** Questions that guide the analysis and interpretation of the dashboard.

## Dashboard Features

### Key Performance Indicators (KPIs)

The dashboard displays these headline metrics:
- Total Flights
- Total Passengers
- Total Distance
- On-Time Flights
- Average Ticket Price
- Average Delay

### Visual Analysis

The report includes visuals to explore:

1. **Flight trend:** Total flights over time.
2. **Airline comparison:** Number of flights operated by each airline.
3. **Destination traffic:** Flight volume by destination city.
4. **Booking-channel share:** Passenger distribution across booking channels.
5. **Airline delays:** Average delay by airline.
6. **Delay trend:** Average delay across months and years.
7. **Ticket prices by destination:** Average ticket price for each destination city.
8. **On-time performance by channel:** On-Time % across booking channels.

### Interactive Filters

Users can filter the report using:
- Airline
- Arrival date
- Destination city
- Origin city
- Booking channel

The charts and KPI cards can be explored using these slicers to focus on selected airlines, locations, dates, or booking channels.

## Business Questions

The report is designed to help answer questions such as:

- How have total flights trended over the year?
- Which airline operates the most flights?
- Which destination cities receive the most traffic?
- What share of bookings comes from each channel?
- Which airline has the worst average delay?
- What is the overall on-time performance?
- Does average delay change month to month?
- Is there a relationship between ticket price and delay?
- Which destination cities have the highest average ticket price?
- Which booking channel has the best on-time record?

## Tools and Technologies

- **Microsoft Power BI Desktop** – report creation and data visualization
- **Power BI data model and measures** – calculation and presentation of performance metrics

## How to Use the Project

1. Download or clone this repository.
2. Open `aircraft_dashboard.pbix` in Microsoft Power BI Desktop.
3. Go to the Dashboard page to view the KPIs and charts.
4. Use the slicers to filter by airline, arrival date, origin city, destination city, or booking channel.
5. Review the Analysis Questions page to guide your interpretation of the results.

## Project File

| File | Description |
|---|---|
| `aircraft_dashboard.pbix` | Power BI report containing the dashboard and analysis questions |

## Insights and Outcomes

The dashboard provides a consolidated view of flight volume, passenger activity, airline performance, delays, booking-channel distribution, and ticket pricing. It supports interactive exploration and helps users compare performance across airlines, cities, dates, and booking channels.

> **Note:** The actual findings depend on the data loaded into the Power BI report and the filters selected. Add specific numerical insights here after reviewing the dashboard results.

## Future Enhancements

- Add a clearly documented data-source section.
- Include a data dictionary describing each column and measure.
- Add more detailed delay and punctuality analysis.
- Publish the report to Power BI Service, if access and licensing allow.

---

**Project:** Sky Track Analytics  
**Report format:** Power BI (`.pbix`)
