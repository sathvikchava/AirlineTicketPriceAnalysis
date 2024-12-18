# Airline Ticket Price Analysis

## Overview
This project investigates the factors influencing airline ticket prices using statistical analysis and Python. It includes a detailed exploration of the role of weather, holiday seasons, advance booking, in-flight amenities, and luggage allowance in pricing.

## Objectives
- To analyze how operational and seasonal factors affect ticket pricing.
- To determine business insights that can optimize airline pricing strategies.

## Tools Used
- Python (Pandas, Matplotlib, statsmodels)
- Tableau
## Dataset Description

This project uses a structured airline dataset to analyze factors influencing flight ticket prices. The dataset contains **numerical** and operational features that directly or indirectly impact flight pricing.

---

### Features Overview

| **Feature**              | **Description**                                     | **Type**         |
|--------------------------|----------------------------------------------------|------------------|
| `FlightID`              | Unique identifier for each flight.                 | Integer          |
| `Distance`              | Distance of the flight in miles.                   | Float            |
| `DateOfFlight`          | Date of the flight.                                | Date             |
| `FlightDuration`        | Duration of the flight in hours.                   | Float            |
| `AdvanceBookingDays`    | Days the ticket was booked in advance.             | Integer          |
| `LuggageAllowance`      | Luggage allowance in kilograms.                    | Integer          |
| `FuelSurcharge`         | Fuel surcharge in USD.                             | Float            |
| `FlightPrice`           | Price of the flight ticket in USD. (**Target**)    | Float            |




## Methods
- Exploratory Data Analysis
- Statistical Hypotheses Testing (ANOVA and Regression)
## Hypothesis Questions and Results

### 1. **Weather Conditions and Ticket Prices**
   - **Hypothesis**: Does the state of the weather affect the cost of tickets?
   - **Result**: **Rejected**  
     Weather conditions do not significantly impact ticket prices.

---

### 2. **Advance Booking and Ticket Prices**
   - **Hypothesis**: Does making reservations further in advance result in lower ticket costs?
   - **Result**: **Rejected**  
     There is no significant relationship between advance booking days and ticket prices.

---

### 3. **Holiday Seasons and Ticket Prices**
   - **Hypothesis**: Do ticket prices increase during holiday seasons?
   - **Result**: **Accepted**  
     Ticket prices are significantly higher during holiday seasons.

---

### 4. **In-flight Add-ons and Ticket Prices**
   - **Hypothesis**: What impact do in-flight amenities (e.g., food, Wi-Fi, entertainment) have on ticket prices?
   - **Result**: **Rejected**  
     In-flight add-ons like meals, Wi-Fi, and entertainment have no significant impact on ticket prices.

---

### 5. **Luggage Allowance and Ticket Prices**
   - **Hypothesis**: Does the maximum luggage allowance affect the cost of tickets?
   - **Result**: **Rejected**  
     There is no significant relationship between luggage allowance and ticket prices.

---

These findings provide actionable insights for airlines to optimize their pricing strategies while understanding the factors that impact or do not impact ticket pricing.

## Key Insights
- **Weather Conditions**: No significant impact on ticket prices.
- **Holiday Seasons**: Ticket prices are higher during holidays.
- **Advance Booking**: No clear relationship with pricing.
- **In-flight Amenities**: Minimal effect on prices.
- **Luggage Allowance**: No significant relationship with ticket costs.

