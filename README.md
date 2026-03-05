# AD8PA HamClock Navigator (v2.1)

A lightweight, single-file browser utility designed to remotely control a **HamClock** via its REST API. This tool provides quick "one-click" navigation for map projections and intuitive tabbed control over data pane rotations.

## 🚀 Features

* **Persistent Settings**: Saves your HamClock IP, QTH Longitude, and Pane selections in your browser's local storage so they are ready the next time you open the utility.
* **Quick Robinson Views**: Global Robinson projection views centered on the **Americas**, **Europe/Africa**, or **Asia/Oceania**.
* **Mercator Zooms**: High-detail regional Mercator projection views for all major continents.
* **System Controls**: Quick toggles for the **RSS Feed** and **Night Shading**.
* **Smart Home Button**: Automatically resets the map to a Mercator projection at Zoom 1 before centering on your specific QTH longitude to ensure perfect alignment.
* **Full Map Reset**: Returns the map to a global Mercator view centered on the prime meridian with no zoom.
* **Advanced Pane Manager**: Tabbed data set selector for Panes 0-3 with "Steal" logic to prevent duplicate views across different panes.

## 🛠 How to Use

1. **Open the file**: Double-click the `HamClockNav_v2.html` file to open it in any modern web browser.
2. **Configure**: 
    * Enter your HamClock’s **IP Address**.
    * Enter your **Home (QTH) Longitude** (e.g., `-90`).
3. **Navigate & Control**: Click any map buttons to update the HamClock display. The green "status dot" in the upper right corner will flash to confirm each command.
4. **Manage Panes**:
    * Click the **PANE SETTINGS ⚙** button to reveal the tabbed interface for Panes 0, 1, 2, and 3.
    * Select the data sets (e.g., Aurora, Moon, DX Cluster) you want to rotate through each pane.
    * **Note**: Because the utility cannot "read" current HamClock settings, you must manually sync your checkboxes during the first use. These selections are then "sticky" and stored in your browser.

## 📺 Live View
To view your HamClock live stream alongside this utility in your browser, navigate to:  
`http://[YOUR_IP_ADDRESS]:8081/live.html`

## ❓ Troubleshooting

* **API Access**: Ensure **Remote API** is enabled in your HamClock setup menu and is using the default **Port 8080**.
* **Connection**: Ensure the device running this utility is on the same local network as your HamClock.
* **Out of Sync**: If you change pane settings directly on the HamClock hardware, you will need to manually update the checkboxes in the Navigator to keep them in sync.

---
**Created by:** AD8PA | **License:** MIT