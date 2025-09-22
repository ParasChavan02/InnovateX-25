❄️ UrbanCool: AI-Driven Weather-Responsive Cooling System
Tagline: Cooling Smarter. Living Better.

🚀 Overview
This repository contains the source code for a Streamlit prototype of UrbanCool, a conceptual AI-driven system designed to orchestrate and optimize urban cooling resources. The application simulates how the system fuses real-time data to make intelligent decisions, providing an interactive and visual demonstration of its core functionalities.

This prototype is built to showcase the potential of using AI to combat the urban heat island effect, save energy, and improve public comfort and safety. All data is simulated and does not require external API keys.

✨ Core Features
Interactive Dashboard: A clean, modern UI to control and monitor the entire system.

Multi-City Simulation: Select from multiple cities (Delhi, Mumbai, Pune, Bangalore) to see geographically-specific simulations.

Dynamic Data Fusion: Visualizes the combination of weather forecasts, simulated heat island maps, and IoT crowd sensor data.

AI Prediction Engine: A simulated AI model that predicts "hot + crowded" zones in real-time based on fused data and user-configurable sensitivity.

IoT Device Control Map: An interactive map (using Folium) showing the status and intensity of cooling devices (Misting Fountains, Shade Sails, etc.) as they are dynamically controlled by the AI.

Live Feedback Loops: Real-time charts (using Plotly) displaying energy consumption vs. a baseline and the effective temperature drop achieved in cooled zones.

Benefits & ROI Panel: Dynamically updated metrics highlighting key benefits like energy savings, cost reduction, and public health risk mitigation.

Anomaly & Resilience Simulation: Randomly injects system anomalies (e.g., "Sensor Failure") to demonstrate fallback routines and system resilience.

Future-Proofing Simulator: A panel to project the benefits of scaling the system across more neighborhoods or adding new types of cooling devices.

🛠️ Tech Stack
Framework: Streamlit

Data Manipulation: Pandas & NumPy

Charting: Plotly

Mapping: Folium & streamlit-folium

Language: Python

⚙️ How to Run the Application
Clone the Repository (or Download the Code)

git clone <repository-url>
cd <repository-directory>

Alternatively, save the urbancool_app.py file to a local directory.

Install Dependencies
It is recommended to use a virtual environment.

pip install streamlit pandas numpy plotly folium streamlit-folium

Run the Streamlit App
Open your terminal, navigate to the directory containing the urbancool_app.py file, and execute the following command:

streamlit run urbancool_app.py

Your default web browser will automatically open with the running application.

This project serves as a powerful proof-of-concept and visualization tool.