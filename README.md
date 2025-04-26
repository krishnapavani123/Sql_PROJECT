# 🚀 Namma Yatri Ride-Hailing Data Analysis Project
**This project simulates a real-world ride-hailing backend like Ola or Uber, using open Namma Yatri app data.**  
It captures trips, payments, trip details, durations, and geospatial mapping to deliver actionable, scalable insights into transportation operations.
| Table | Description |
|:---|:---|
| `Trips` | Core trip bookings — tripid, driverid, loc_from,loc_to, fare,faremethod,custid,distance,duration |
| `Trip_Details` | Metrics including tripid,driver_not_cancelled,cus_not_cancelled,end_ride breakup. |
| `Payment` | Payment methods, loc_from |
| `Assembly` | Areas |
| `Duration` | Time-based tracking from ride acceptance to completion |

## 🛠️ Key Features

- **Trip Efficiency**: Track delays, trip times, wait times.
- **Revenue Analysis**: Analyze total earnings, surge impacts, payment channel preferences.
- **Cancellation Patterns**: Identify cancellation hotspots and root causes.
- **Geospatial Insights**: Understand mobility patterns at the constituency level.
- **Scalability**: Built for real-time expansion into live systems and analytics platforms.

---


## 🚀 How to Set Up

1. **Clone** the repository or download the zip.
2. **Import tables** from `SqlProject.Tables.zip` into your SQL environment.
3. **Review schema** connections via `Tables.Schema.png`.
4. **Execute** queries from `Quries.sql` to generate powerful analytics.



