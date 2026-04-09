# Airline Revenue & Passenger Behaviour Intelligence Dashboard | Power BI · DAX

Power BI dashboard analysing $645K in airline revenue across 250 bookings, 6 airlines, and 8 global cities — uncovering pricing patterns, passenger behaviour, and revenue drivers.

---

## Links

[Live Dashboard](https://app.powerbi.com/groups/me/reports/d1af0f15-4af0-4fe7-96e9-874b84047de1/58402d2b1828c7d30048?experience=power-bi) · [LinkedIn](https://www.linkedin.com/in/prachi252/) · [GitHub](https://github.com/Prachi0259)

---

## About

This project analyses airline booking data to understand what actually drives revenue across routes, travel classes, and cities. The dashboard spans two pages — revenue segmentation and flight duration analysis — built using Power BI with custom DAX measures and Power Query transformations.

**Source:** flight_bookings.csv

---

## Dataset

| Column | Description |
|--------|-------------|
| Booking_ID | Unique booking identifier |
| Airline | 6 airlines (B Airways, S Airlines, E Airlines, L Airlines, Air I, Q Airways) |
| Departure_City | 8 cities (Mumbai, London, Delhi, Singapore, Frankfurt, Paris, Dubai, New York) |
| Travel_Class | Economy, Business, First, Premium Economy |
| Ticket_Price | Price in USD |
| Payment_Method | Credit Card, Cash, Net Banking, PayPal, Debit Card, UPI |
| Passenger_Age | Age of the traveller |
| Flight_Duration_hr | Duration in hours |
| Distance_km | Route distance in kilometres |

**Total Records:** 250 bookings

---

## Key Findings

B Airways leads revenue at $129K — 46% higher than Q Airways at $88K, driven by premium class bookings rather than volume.

Ticket price has no linear relationship with flight distance across 1,889K km of routes. Pricing is class-driven, not distance-driven — Business and First class command higher fares regardless of route length.

Payment preferences are evenly split across 6 methods at approximately 18% each, with no dominant channel — indicating broad customer diversity and the need for equal payment infrastructure investment.

Air I operates the longest routes at 13 hrs average duration, while London and Frankfurt show the highest flight duration variance due to a mix of short-haul and long-haul routes.

---

## Dashboard

**Page 1 — Revenue Drivers & Passenger Segmentation**
Revenue by Airline, Departure City, Payment Method, and Passenger Age Group. Booking split by payment method and travel class with airline slicer.

**Page 2 — Flight Duration & Pricing Pattern Analysis**
Avg Flight Duration by Class, Duration Variance by City, Ticket Price vs Flight Duration scatter (coloured by Travel Class), Duration by Airline and Age Group.

---

## Repository Structure

```
Airline-Revenue-Passenger-Analytics/
├── Airline_Revenue_Passenger_Behavior_Intelligence_Dashboard.pbix
├── data/
│   └── flight_bookings.csv
├── screenshots/
│   ├── Page 1.png
│   └── Page 2.png
└── README.md
```

---

## Tools

Power BI Desktop · DAX · Power Query 

---

## Author

**Prachi**
prachi7.work@gmail.com · [LinkedIn](https://www.linkedin.com/in/prachi252/) · [GitHub](https://github.com/Prachi0259)
