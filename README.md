# MQTT Weather Station with SQLite and Real-Time Visualization

## Description
This project connects to an MQTT broker to receive temperature and humidity data, stores it in an SQLite database, and displays it in real-time using a web interface. The graph averages data every 5 minutes.

---

## Prerequisites
- Node.js & npm installed
- MQTT broker running (WebSocket enabled)
- SQLite installed (optional, only for viewing the database manually)

---

## Setup Instructions

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/weather-station.git
cd weather-station
```
## Install dependencies:
```bash
npm install express sqlite3 mqtt cors
```
## Run the backend server:
```bash
node server.js
```
Open index.html in a browser:


# Simply open the file in a web browser
Verify the setup:
Check the console for MQTT connection status.
View temperature and humidity values updating in real-time.
Observe the graph showing averaged data every 5 minutes.
Additional Tips
If the backend is not accessible, ensure CORS is enabled and that the server is running on the correct port.
To view the SQLite database, use a tool like DB Browser for SQLite.
Future Improvements
Add historical data visualization.
Implement data export options (e.g., CSV).
yaml

---

### **Summary**
This solution includes everything needed to visualize temperature and humidity in a real-time graph with aver
