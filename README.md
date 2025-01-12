# **NYC Taxi Data Analysis: Hotspot Recommendations for Drivers**

This project delves into New York City's taxi system, analyzing millions of taxi rides to uncover patterns in passenger pickup and drop-off locations. The goal is to provide actionable insights for taxi drivers, helping them identify the best locations to position their vehicles based on time and geography.

---

## **Core Insights and Approach**
1. **Identifying High-Demand Zones**: Leveraged clustering algorithms to analyze geographical coordinates and time-of-day data for spotting areas with maximum activity.
2. **Prioritizing Zones by Connectivity**: Applied node importance metrics to assess how well zones connect to other busy areas, enhancing drivers' ability to capture multiple rides efficiently.
3. **Data Visualization**: Created interactive visual tools to explore trends, hourly hotspots, and zone rankings dynamically.

---

## **Highlights of the Solution**
### **Data Preprocessing**
- Removed inconsistencies like outliers, illegal records, and trips outside NYC limits.
- Extracted new features such as trip duration and day of the week for deeper analysis.

### **Clustering-Based Insights**
- Designed K-Means clustering in 2D and 3D to pinpoint evolving demand hotspots.
- Time-dependent clustering revealed shifts in activity across hours and regions.

### **Node Importance Algorithm**
- Built a graph representing taxi zones and their ride frequencies.
- Implemented a transposed node importance algorithm to rank zones based on connections to active areas.

### **Interactive Visualizations**
- Developed heatmaps and cluster maps to showcase patterns and high-priority zones interactively.
- Highlighted hourly variations in taxi demand to assist in real-time decision-making.

---

## **Data Utilization**
The project utilizes the NYC Yellow Taxi dataset from 2016, which includes:
- Pickup and drop-off coordinates.
- Ride timestamps, allowing temporal analysis.
- Trip-specific details such as fare and tip amounts.

Supplementary shapefiles were employed to map coordinates to predefined taxi zones, enriching the analysis with regional context.
