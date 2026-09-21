# Uber Driver Profitability Analysis

Kingston & Portmore, Jamaica

Based on 166 completed Uber trips using a 2020 Honda Jazz Crosstar.

dashboard/dashboard.png

---

## Project Objective

This project estimates the realistic profitability of driving with Uber in Kingston and Portmore, Jamaica.

The analysis includes:

- Fuel costs
- Utilisation rates
- Outlier removal
- Monthly income forecasts
- Vehicle mileage forecasts
- Driver profitability metrics

---

## Dashboard Summary
| Metric | Value |
|----------|---------:|
| Effective Net Earnings | JMD 1,688/hr |
| Gross Monthly Income | JMD 329,094 |
| Net Monthly Income | JMD 263,992 |
| Monthly Fuel Spend | JMD 65,102 |
| Projected Mileage | 4,173 km |
| Fuel Required | 296 L |

---

## Methodology

### Fuel Cost
Fuel consumption is estimated using:

Fuel Economy:
14 km/L

Fuel Price:
JMD 220/L  

<br>

### Outlier Detection
Trips are classified as valid when earnings per minute fall between the 5th and 95th percentiles.

This removes:

- Cancelled trips
- Earnings adjustment anomalies (ex. uber recalculations for rides not ended by driver)
- Unrealistic surge trips

while retaining approximately 90% of valid driving activity.  

<br>

### Monthly Forecast - 168 hours (standard 40-hour week)
Projected mileage:
4,173 km/month

Projected fuel consumption:
296 L/month

Projected net income:
JMD 263,992/month

---

## Key Insights
- Average net earnings after fuel costs exceed JMD 1,600/hr.
- Fuel consumes approximately 15% of gross earnings.
- A full-time driver working a standard 40-hour week can expect approximately JMD 264,000 monthly net income after fuel.
- Annual mileage is projected at approximately 50,076 km.

---

## Files
- Dashboard Screenshot
- PDF Report
- Spreadsheet Model
- Raw Trip Dataset

---
