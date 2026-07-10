# Uber Ride Bookings Dashboard (Power BI)

![](https://github.com/AkashSharma-Artist/Uber-Ride-Bookings-Dashboard-Power-BI-/blob/main/ChatGPT%20Image%20Jul%2011%2C%202026%2C%2012_10_39%20AM.png)
 
A multi-page Power BI dashboard built to analyze Uber ride booking data end-to-end 
— from booking status and revenue to rider behavior and trip distance. The report 
is structured across dedicated pages so each aspect of the ride-hailing business 
can be explored independently while staying connected through shared KPIs.
 
## Overview
Ride-hailing platforms generate rich operational data — bookings, cancellations, 
revenue, vehicle types, and rider patterns. This dashboard consolidates that data 
into a single interactive tool, letting stakeholders drill from a high-level 
overview into vehicle-specific, revenue-specific, rider-specific, or 
distance-specific views.
 
## Dashboard Structure (6 Pages)
 
| Page | Focus |
|------|-------|
| **Home** | Landing page with title and navigation entry point |
| **Overview** | High-level KPIs — bookings, revenue, distance, ratings, top locations |
| **Vehicle** | Booking & revenue performance broken down by vehicle type |
| **Revenue** | Revenue trends by month, payment method, vehicle type, and customer |
| **Rider** | Rider behavior — first-time vs returning vs regular riders, cancellations |
| **Distance** | Trip distance trends by vehicle type, time slot, and pickup location |
 
## Key Metrics (KPIs)
- Completed Bookings
- Lost Bookings
- Booking Value (Revenue)
- Total Distance & Average Distance
- Customer Count
- Customer & Driver Ratings
- First-time / Returning / Regular Rider counts
## Page-Level Highlights
 
**Overview Page**
- Monthly trend of Completed Bookings (area chart) and Booking Value (column chart)
- Booking Value by Vehicle Type
- Top Pickup & Drop Locations (multi-row cards)
- Customer and Driver rating summary
- Booking status breakdown (donut charts)
**Vehicle Page**
- Detailed table: Completed Bookings, Booking Value, Customer Count, and 
  Contribution % per Vehicle Type, with monthly sparkline trends
- Booking status breakdown by vehicle
**Revenue Page**
- Revenue trend by month (area chart)
- Revenue by Payment Method
- Revenue by Vehicle Type
- Revenue by Customer ID (top customers)
**Rider Page**
- Customer Count trend by month
- First-time vs Returning vs Regular rider breakdown (donut charts)
- Booking count by Payment Method
- Cancellation reasons (by driver)
- Detailed rider-level table: bookings, lost bookings, avg/total distance
**Distance Page**
- Total Distance trend by month
- Distance by Vehicle Type
- Booking Count by Time Slot & Weekday (pivot table)
- Booking Count by Pickup Location
## Tech Stack
- Power BI Desktop
- DAX (custom measures: Completed Bookings, Lost Bookings, Avg Distance, 
  Contribution %, First-time/Returning/Regular Rider segmentation, etc.)
- Power Query (data transformation)
- Custom theme, icons, and vehicle images for visual branding
## Tools & Techniques Used
- Multi-page report design with consistent KPI card headers on every page
- DAX-driven rider segmentation (first-time vs returning vs regular)
- Sparklines within table visuals for compact trend visualization
- Pivot table for time-slot × weekday booking analysis
- Custom slicers for interactive filtering across all pages
## How to View
This is an interactive Power BI report. To explore it fully (filters, drill-downs, navigation):
1. Download the `.pbix` file from this repository
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Use the navigation buttons on the Home/Overview page to move between Vehicle, Revenue, Rider, and Distance views
*A static preview image is included in this repo for quick reference, but the full interactive experience requires Power BI Desktop.*
 
## Conclusion
This dashboard demonstrates the ability to model and analyze operational data 
from a ride-hailing business across multiple dimensions — vehicles, revenue, 
riders, and distance — using well-structured DAX measures and a clean, 
multi-page navigation design. The rider segmentation logic (first-time, 
returning, regular) and the sparkline-enabled summary table in particular 
show comfort with more advanced Power BI techniques beyond basic charting, 
making this a strong addition to a data analytics portfolio.

![](https://github.com/AkashSharma-Artist/Uber-Ride-Bookings-Dashboard-Power-BI-/blob/main/Dashboard%20Img/1.png)
![](https://github.com/AkashSharma-Artist/Uber-Ride-Bookings-Dashboard-Power-BI-/blob/main/Dashboard%20Img/2.png)
![](https://github.com/AkashSharma-Artist/Uber-Ride-Bookings-Dashboard-Power-BI-/blob/main/Dashboard%20Img/3.png)
![](https://github.com/AkashSharma-Artist/Uber-Ride-Bookings-Dashboard-Power-BI-/blob/main/Dashboard%20Img/4.png)
![](https://github.com/AkashSharma-Artist/Uber-Ride-Bookings-Dashboard-Power-BI-/blob/main/Dashboard%20Img/5.png)
![](https://github.com/AkashSharma-Artist/Uber-Ride-Bookings-Dashboard-Power-BI-/blob/main/Dashboard%20Img/6.png)
![](https://github.com/AkashSharma-Artist/Uber-Ride-Bookings-Dashboard-Power-BI-/blob/main/Dashboard%20Img/7.png)
![](https://github.com/AkashSharma-Artist/Uber-Ride-Bookings-Dashboard-Power-BI-/blob/main/Dashboard%20Img/8.png)
