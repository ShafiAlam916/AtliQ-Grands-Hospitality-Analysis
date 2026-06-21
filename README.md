# 📊 AtliQ Grands Hospitality Analysis

---

## 🎥 Presentation Video
👉 **Watch the full project walkthrough here:**  
[Presentation Video Link](https://www.linkedin.com/posts/mdshafialam_powerbi-revenuemanagement-hospitalityanalytics-ugcPost-7431547849802403840-Y_5q/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFANRrUB8YOiQ7CrZlkNSWAytjyAKghfpAs)

---

## 🚀 Project Overview

**Difficulty:** Intermediate  
**Domain:** Hospitality  
**Function:** Revenue  

This project is part of the **Codebasics Resume Challenge**, designed to simulate a real-world revenue analytics scenario in the hospitality industry.

AtliQ Grands, a premium hotel chain operating in the luxury and business hotel segment, is experiencing a decline in market share and revenue due to increasing competition and ineffective data-driven decision-making.

To address this challenge, I developed a comprehensive revenue analytics dashboard aimed at enabling strategic insights across occupancy, pricing, bookings, and cancellation performance. The solution centralizes hotel performance data and transforms it into actionable intelligence to support revenue optimization and regain competitive advantage.

---

## ❗ Business Problem

- AtliQ Grands are losing **market share** in the luxury/business hotel segment  
- Declining **revenue performance** due to competitive pressure  
- Strategic decisions are not backed by structured data insights  
- Lack of an in-house **data analytics team** to support revenue optimization  
- Limited visibility into critical KPIs such as occupancy, ADR, RevPAR, and cancellation trends  

The Managing Director recognized the need to incorporate **Business & Data Intelligence** to regain revenue growth and improve strategic decision-making.

---

## 🎯 Objectives

As a Data Analyst, I was provided with sample data and a stakeholder mock-up dashboard to perform the following tasks:

1. I created all required metrics according to the predefined metric list, including revenue, occupancy %, ADR, RevPAR, cancellation rate, and other revenue KPIs.  
2. I developed an interactive Power BI dashboard aligned with the stakeholder-provided mock-up to ensure usability and business relevance.  
3. I generated additional actionable insights beyond the provided metrics, identifying trends, inefficiencies, and performance gaps to support better revenue strategies.  

The goal was to deliver a structured analytics solution that enables leadership to make confident, data-driven decisions.

---

## 🏢 Company Overview

AtliQ Grands owns multiple **five-star hotels across India** and has been operating in the hospitality industry for over **20 years**.

However, due to aggressive strategic moves from competitors and ineffective management decision-making, the company has been steadily losing its **market share and revenue** in the luxury and business hotel categories.

To remain competitive in a data-driven market, AtliQ Grands identified the urgent need for a robust analytics framework capable of delivering performance visibility across properties, room categories, booking platforms, and time periods.

---

## 🗂️ Datasets Used

This project uses five structured CSV datasets consisting of dimension and fact tables.

### 📌 Dimension Tables

- **dim_date**  
  Contains date-level details including month-year format, week number, and day type (Weekend/Weekday).

- **dim_hotels**  
  Includes hotel property information such as property ID, property name, category (Luxury/Business), and city.

- **dim_rooms**  
  Defines room categories (RT1–RT4) and their corresponding room classes (Standard, Elite, Premium, Presidential).

---

### 📊 Fact Tables

- **fact_aggregated_bookings**  
  Contains daily property-level booking performance including:
  - Successful bookings
  - Room capacity
  - Room category
  - Check-in date

- **fact_bookings**  
  Detailed transactional-level data including:
  - Booking ID
  - Booking & check-in/check-out dates
  - Number of guests
  - Booking platform
  - Booking status (Cancelled, Checked Out, No Show)
  - Revenue generated and revenue realized
  - Customer ratings

Revenue logic:
- Cancelled bookings → 40% revenue deduction applied  
- Checked Out / No Show → Full revenue realized  

---
