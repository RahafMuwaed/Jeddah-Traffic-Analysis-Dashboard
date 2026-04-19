 Jeddah Traffic Analysis Dashboard

 Overview

This project analyzes traffic patterns in Jeddah by transforming route data into interactive insights using Power BI.

The goal is to identify congestion patterns, understand route efficiency, and analyze movement between city zones.

⸻

 Objectives
	•	Identify the most congested routes
	•	Analyze traffic flow between zones
	•	Understand the relationship between distance, duration, and speed
	•	Provide data-driven insights for urban mobility

⸻

 Data Collection

Traffic data was generated using:
	•	OpenRouteService API
	•	Python (requests library)

Routes were defined between key locations in Jeddah, and the following were extracted:
	•	Distance (km)
	•	Duration (minutes)

⸻

 Data Processing

The dataset was enriched by calculating:
	•	speed_kmh = distance / duration
	•	traffic_score = duration / distance
	•	traffic_level (Low / Medium / High classification)
	•	Zone Flow (e.g., North → South)

⸻

 Dashboard Features

The Power BI dashboard includes:
	•	KPI Cards
	•	Average Duration
	•	Average Speed
	•	Peak Traffic Score
	•	Top Congested Routes
	•	Highlights worst-performing routes
	•	Zone Flow Analysis
	•	Identifies congestion between city areas
	•	Traffic Distribution
	•	Percentage of High / Medium / Low traffic
	•	Distance vs Duration (Scatter Plot)
	•	Shows efficiency and outliers

⸻

 Key Insights
	•	Congestion is concentrated in specific routes, not evenly distributed
	•	Some zone connections consistently show higher traffic pressure
	•	Distance alone is not a reliable indicator of travel time
	•	Certain routes are inefficient despite short distances

⸻

 Tools & Technologies
	•	Power BI
	•	Python
	•	OpenRouteService API
	•	Data Visualization & Analysis
