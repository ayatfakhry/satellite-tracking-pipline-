# Satellite Tracking Pipeline 🚀

An automated multi-satellite tracking and pass prediction system using real orbital (TLE) data.

## 📡 Overview
This project simulates a ground station tracking system that:
- Predicts satellite passes over a given location
- Selects the optimal satellite for tracking
- Generates tracking tables (Azimuth & Elevation)
- Produces motor command outputs for future hardware integration
- Provides an interactive dashboard for analysis and visualization

## ⚙️ Features
- Multi-satellite pass prediction
- Best satellite selection using a custom ranking score
- Full-day tracking analysis
- Tracking table generation
- Motor command simulation
- Interactive dashboard (Gradio)

## 🛠️ Technologies Used
- Python
- Skyfield (orbital calculations)
- Pandas (data processing)
- Matplotlib (visualization)
- Gradio (dashboard)

## 📊 Project Structure
- `satellite_tracking_data_engineering.ipynb` → Core pipeline & analysis  
- `satellite_tracking_dashboard.ipynb` → Interactive dashboard  

## 👩‍💻 Author
Ayat Fakhry
