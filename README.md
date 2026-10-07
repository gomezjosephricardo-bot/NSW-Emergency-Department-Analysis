# NSW-Emergency-Department-Analysis

## Overview
Analysis of 16 years of NSW emergency department data (170,000+ records) 
to identify demand trends, seasonal capacity pressure, and hospitals 
at highest risk of performance failure during winter surges.

## Data Source
Bureau of Health Information (BHI), Healthcare Quarterly
Period: January 2010 – June 2026 (66 quarters)
Citation: Bureau of Health Information. Healthcare Quarterly ED Dataset. 
Sydney (NSW); BHI: 2026.

## Key Findings
- ED demand has grown 60% since 2010, reaching 804K presentations per quarter
- Median wait times increased 37% post-COVID (160 to 220+ minutes)
- Low-acuity presentations (T4-T5) dropped from 60% to 42%, indicating 
  GP diversion is working — but demand is still rising because high-acuity 
  cases (T1-T3) are increasing
- Five hospitals identified as most vulnerable to winter performance decline
- Post-COVID demand has exceeded pre-COVID peaks while wait times continue rising

## Recommendations
1. Targeted winter staffing increases for at-risk hospitals (Fairfield, 
   Blacktown, Westmead)
2. Capacity investment focused on high-acuity care, not further GP diversion
3. Early warning monitoring for hospitals showing large seasonal declines 
   but still passing benchmarks
4. Further investigation into post-COVID wait time deterioration

## Tools
Power BI, DAX, Power Query

## Dashboard Pages
- Page 1: Patient Volume Trends (demand growth, seasonal patterns, KPIs)
- Page 2: Hospital Performance Under Pressure (winter drop ranking, 
  summer vs winter comparison)
- Page 3: Wait Time Deterioration (summer vs winter wait times over time)
- Page 4: Triage Analysis (T1-T5 breakdown, GP diversion trend)
- Page 5: Key Findings & Recommendations
