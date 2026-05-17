# smartHome_Dashboard
# smartHome_Dashboard

SmartHome Device Simulation – A real-time browser-based visualizer 
for Smart Home devices communicating via MQTT over WebSocket. 
Displays LED states with brightness and color effects, 
plus live temperature sensor readings. Built with Vanilla JS & MQTT.js.

Dashboard showing live LED states and temperature sensors across multiple rooms.

Features:
- LED Visualization – Real-time display of 4 smart lights (Living Room, Office, Bedroom, Kitchen) with color glow effects and brightness bars
- Temperature Sensors – Live temperature readings from 4 sensors/thermostats displayed as progress bars
- MQTT via WebSocket – Connects to the HiveMQ public broker in real time
- Connection Status – Live indicator showing broker connection state
- Log Monitor – Built-in console showing all incoming MQTT messages with timestamps
- Responsive Layout – Adapts from 4 columns → 2 columns → 1 column on smaller screens