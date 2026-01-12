# 🏙 NYC Noise Complaint Analysis (2022–2024)

A data-driven analysis of New York City’s noise complaints using **311 Service Request data** to identify patterns, hotspots, and policy-relevant insights.  
This project translates large-scale urban data into **actionable recommendations for city leadership**.

> 🎓 Course Project: **EAI 6120 – AI Communication & Visualization**  
> 🏫 Northeastern University, College of Professional Studies  
> 📅 December 2025  

---

## 🔎 Executive Summary

Noise complaints in NYC are **concentrated, predictable, and actionable**.

- A small number of **boroughs and neighborhoods** generate a disproportionate share of complaints.
- Complaints spike during **late-night quiet hours (10 PM – 7 AM)** and on **weekdays**.
- **Residential and street/sidewalk noise** account for the majority of cases.
- Without targeted intervention, complaint volumes are likely to continue rising.

> This is not a random problem — **focused enforcement at specific places and times can reduce a large share of complaints**.

---

## 📊 Data & Scope

- **Data Source:** NYC Open Data – 311 Service Requests  
- **Time Period:** 2022–2024  
- **Complaint Type:** Noise-related service requests  
- **Assumptions:**
  - Some complaints may represent repeat reports for the same location.
  - “Quiet hours” are defined as late-night hours to highlight policy impact.

---

## 🧠 Key Questions Addressed

- Where do most noise complaints originate?
- When do complaints peak (hourly, weekday vs weekend)?
- Which noise sources drive the highest volume?
- How quickly are complaints resolved?
- Where should the city prioritize enforcement?

---

## 📍 Major Findings

### Borough-Level Concentration
- The **Bronx** generates the highest number of complaints.
- **Brooklyn and Manhattan** follow closely.
- Complaints are **not evenly distributed citywide**.

### Noise Sources
- **Residential noise** accounts for ~50% of all complaints.
- **Street/sidewalk noise** contributes ~22%.
- Other categories contribute marginally.

### Time Patterns
- Complaints spike **exactly at the start of quiet hours (10 PM)**.
- Late-night complaints remain elevated despite lower city activity.
- **Weekdays generate ~44% more complaints than weekends**.

### Service Performance
- Most complaints are resolved quickly.
- A small subset experiences long delays (24–72 hours), driving repeat complaints and dissatisfaction.

---

## 🗺 Spatial Insights

Noise complaints cluster in **specific neighborhoods**, not randomly across the city.  
These hotspot zones represent **high-impact targets** for enforcement, outreach, and prevention strategies.

---

## 🏛 Policy Implications

- Citywide, uniform enforcement is inefficient.
- Resources should be allocated **by burden**, not evenly.
- Late-night residential noise offers the **highest return on enforcement effort**.
- Repeat locations should be proactively tracked and addressed.

---

## ✅ Recommended Actions

1. **Late-Night Enforcement Focus**  
   Prioritize patrols during quiet hours in hotspot zones.

2. **Residential Noise Prevention**  
   Education and warnings for repeat residential offenders.

3. **Place-Based Interventions**  
   Target high-density corridors rather than blanket citywide policies.

4. **Repeat-Location Tracking**  
   Flag addresses with frequent complaints for proactive intervention.

---

## 📂 Repository Structure

```text
├── notebooks/        # Full data analysis & visualization
├── visuals/          # Key charts and maps
├── presentation/     # Executive presentation deck
