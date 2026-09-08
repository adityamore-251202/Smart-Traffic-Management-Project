# Smart Traffic Intersection System 🚦

## Overview
This project was developed as my final year, last semester hardware model.  
It demonstrates a **smart traffic management system** where four roads meet at one junction point.  
The system uses **ultrasonic sensors** and an **Arduino Mega** to dynamically adjust traffic signal timings based on vehicle density.

## Project Description
- Four ultrasonic sensors were placed at equal distances on each road approaching the junction.
- A central signal lamp was installed at the intersection.
- When vehicles are detected by the sensors, the system measures traffic density.
- The Arduino Mega increases the green signal timing for the road with higher traffic density.
- An **ESP32-CAM** was integrated to help traffic police visualize traffic conditions in real time.  
  - Synchronization challenges prevented full implementation, but the concept was tested.

## Tools & Technologies
- **Arduino Mega** (traffic signal control logic)
- **Ultrasonic Sensors** (vehicle detection)
- **ESP32-CAM** (traffic visualization)
- **Python, Pandas, NumPy** (data cleaning & exploratory data analysis for congestion trends)

## Results
- Successfully demonstrated dynamic traffic signal timing adjustment based on real‑time vehicle density.
- Identified congestion trends through exploratory data analysis.
- Supported traffic optimization concepts for smart city applications.

## Challenges
- Synchronization issues with ESP32-CAM prevented full integration.
- Limited resources restricted large‑scale testing.

## Future Work
- Recreate Python scripts for data cleaning and EDA.
- Add sample datasets (CSV files) for demonstration.
- Build Power BI dashboards for traffic visualization.
- Improve ESP32-CAM synchronization for real‑time monitoring.

## Project Photo
![Smart Traffic Intersection](project_photo.jpeg)

---

### Author
**Aditya More**  
Aspiring Data Analyst / BI Analyst  
[LinkedIn Profile](https://www.linkedin.com/in/adityamore251202) | [GitHub Profile](https://github.com/adityamore-251202)

