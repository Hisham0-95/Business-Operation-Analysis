# Comprehensive BPO Operations & Workforce Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?logo=microsoft&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoftexcel&logoColor=white)

> Built as part of a Business Operations Analyst assessment at Concentrix

---

<img width="1429" height="798" alt="Attendance & Shrinkage Dashboard" src="https://github.com/user-attachments/assets/47fa129a-9d8e-4b07-83d5-581b70e10a32" />
<img width="1430" height="803" alt="Quality Command Center" src="https://github.com/user-attachments/assets/9df5f17a-046a-445b-844e-ffe9b93d89b7" />
<img width="1434" height="806" alt="Productivity Dashboard" src="https://github.com/user-attachments/assets/819d8ba6-f164-41d2-b117-37d90bc7fe81" />

---

## Tools Used
- **Power BI** — Dashboard design, DAX measures, data modeling
- **DAX** — Custom KPI calculations (AHT, Occupancy, Shrinkage, Utilization)
- **Excel** — Data preparation and transformation

---

## Project Overview

This Power BI project provides a comprehensive, end-to-end analysis of Business Process Outsourcing (BPO) and customer service operations. By bridging the gap between workforce availability and agent performance, this dashboard empowers operational leaders to identify bottlenecks, optimize staffing, and monitor adherence to service level targets.

---

## Business Objectives

- **Monitor Workforce Availability:** Identify trends in absenteeism, sickness, and overall schedule adherence to ensure optimal staffing levels.
- **Evaluate Channel Performance:** Compare Actual Average Handle Time (AHT) against channel-specific targets across Phone, Email, and Chat interactions.
- **Measure Productivity:** Accurately track how agents spend their logged-in time through Utilization and Occupancy metrics.

---

## Key Metrics & KPIs

### Shrinkage & Attendance Metrics
- **Absenteeism %:** Ratio of total absent days against total scheduled days
- **Unplanned Shrinkage %:** Unexpected time off (Unplanned Days ÷ Scheduled Days)
- **Planned Shrinkage %:** Approved time off (Planned Days ÷ Total Days)
- **Sickness %:** (Sick + Planned Sick) ÷ (Scheduled Days + Planned Sick)

### Productivity & Performance Metrics
- **AHT:** Weighted Average Handle Time targets based on contact volume across distinct channels
- **Utilization %:** Time agents spend in productive states vs. total logged-in duration
- **Occupancy %:** Active handle time vs. total available time while logged in

### Quality & User Experience Metrics
- **User Experience:** Positive experience scores ÷ Total valid responses
- **Professionalism %:** Agent conduct and quality standards adherence
- **Resolution Rate:** Total resolved contacts ÷ Total eligible contacts
- **Knowledge Score:** Agent product and process expertise during interactions

---

## Insights

1. **Unplanned Shrinkage by Country:** India faces critical attendance challenges with a 15.44% Unplanned Shrinkage rate, compounded by 5.72% Absenteeism and 7.49% Sickness.
2. **Attendance by Company:** Mahindra & Mahindra has the highest unplanned shrinkage rate at 16.48% with 0% planned shrinkage.
3. **Overstaffing Observation:** The widening gap between Occupancy % and Utilization % signals significant idle time and overstaffing inefficiency.
4. **Ferrari User Experience:** 50% of Ferrari customers were unsatisfied post-contact, indicating a critical service quality gap.

---

## Summary & Strategic Outlook

### Phase 1: Diagnosis
- **Single Source of Truth:** Deployed three integrated Command Centers covering Availability, Efficiency, and Quality
- **Critical Leakage Identified:** Pinpointed systemic shrinkage variance in India and the "Substitution Effect" between Planned and Unplanned shifts
- **Efficiency Gaps Quantified:** Confirmed overstaffing as the primary driver of low CPH (3.29) and high idle time
- **Process Gaps Uncovered:** Detected a "Transfer Paradox" where high-knowledge agents bypass resolution protocols

### Phase 2: Execution
- **Stabilize Availability:** Launch targeted PIPs for outlier Team Leaders and a Perfect Attendance Bonus pilot
- **Optimize Cost:** WFM to review interval arrival patterns and reduce headcount during low-volume windows
- **Elevate Experience:** Deploy the "Ferrari Tiger Team" and initiate cross-channel (Phone → Email) mentorship program
