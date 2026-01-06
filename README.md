# 🌃  The NYC Nightlife Noise Pulse
## **_An Analysis of Commercial Disturbance and Residential Sleep Vulnerability_**



## 📌 Executive Summary
This project analyzes **118,676** noise complaints to identify where nighttime commercial activity creates the highest risk for residential sleep interference. By mapping 5**2,260** specific nighttime events (11 PM – 5 AM), I identified the neighborhoods and hours where the city’s "nightlife pulse" is most intense.

### 🔍 Key Insights

**The 11 PM "Danger Zone":** Noise complaints across NYC peak sharply at 23:00 (11:00 PM). This is a critical urban health insight, as it coincides with the beginning of the most restorative residential sleep cycles.

**Top Hotspot - Inwood (10034):** Surpassing traditionally "loud" areas like the Lower East Side (10002), Inwood recorded 1,047 commercial noise events, making it the city's primary friction zone.

**The Brooklyn's Rise:** High-density commercial noise is no longer exclusive to Manhattan; Bed-Stuy (11216) and Prospect Heights (11238) now rank among the top 5 noise hotspots.

## 🗺️  Geographic Distribution (The "Where")

Before diving into specific numbers, I mapped the total density of complaints. The heatmap reveals a concentrated "Noise Axis" running from Upper Manhattan through the East Village and into the Northern Brooklyn corridor.

👉 **[Explore the Live Interactive Heatmap](https://megwilliams17.github.io/Urban_Noise_-_Sleep/nyc_sleep_risk_map.html)**
*(Note: This map is best viewed on a desktop browser for full interactivity.)*





**How to read this map:** 
Warmer colors indicate higher concentrations of nighttime commercial noise complaints. The intensity of Inwood (ZIP 10034) stands out despite its smaller size, visually confirming its role as NYC's primary nighttime noise hotspot.


**_Insight:_** The spatial density confirms that noise follows specific commercial corridors and gentrifying residential hubs rather than being randomly distributed.


## 📉  The Nightly Pulse (The "When")

To understand the impact on residents, I analyzed the volume of complaints by hour. In NYC, commercial noise isn't a steady hum; it is a sharp spike that climbs through the evening.




<div align="center">
  <img src="NYCCommercialNoisePulse.png" width="90%">
  <p><i>Figure 1: The 11 PM Pulse — Hourly distribution of commercial noise complaints.</i></p>
</div>




**_Insight:_** The data shows a massive surge starting at 10 PM and peaking at 11 PM before a slow decline into the early morning. This highlights a direct conflict between the late-night economy and the public health need for sleep.


## 📊  Impact by Neighborhood (The "Who")

I mapped Zip Codes to actual neighborhood names to provide human context. While the Lower East Side is famous for its bars, the data shows that Inwood and Washington Heights are experiencing higher volumes of reported distress.




![The Impact](NYCNeighbourhoods.png)





| Neighborhood | Zip Code | Complaint Count|
| :--- | :---| :--- |
|**Inwood / Washington Heights**|10034 |1,047 |
| **Lower East Side/ Chinatown** |10002 |833 | 
| **East Village / Alphabet City** | 10009 |816 | 
| **East Harlem** |10029 | 792 | 
|**Bed-Stuy (Brooklyn)** |11216 | 762 |










## 🛠️  Methodology & The "Data Scientist Pivot"

A critical part of this project was a Data Integrity Audit.

- **The Problem:** I originally intended to compare Residential vs. Commercial noise ratios. However, I discovered that 'Residential' descriptors in this 311 subset were exclusively linked to Animal Welfare cases.

- **The Action:** To maintain scientific honesty, I pivoted to a Volume & Density Analysis of Commercial noise, ensuring the final results were accurate and verified.



## 🚦  Final Conclusion & Recommendations

This analysis proves that commercial noise is a significant urban stressor peaking during residents' most vulnerable hours. While the data doesn't explicitly label businesses as "clubs" or "bars," the clusters suggest a high density of late-night commercial venues.

### Recommendations:

1. **Targeted Enforcement:** Prioritize noise mitigation in the 10034 and 10002 zip codes specifically between 10 PM and Midnight.

2. **Acoustic Planning:** City planners should implement stricter soundproofing ordinances and acoustic mitigation for new commercial developments in the identified Top 10 Zip Codes.