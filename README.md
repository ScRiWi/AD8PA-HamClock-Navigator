AD8PA-HamClock-Navigator (v2.1)

Description:

A lightweight, single-file browser utility designed to remotely control a HamClock via its API from a device that is on the same local network as HamClock.  Provides quick "one-click" navigation of map projections and direct control over the pane views.

Features:

Persistent Settings: Saves your HamClock IP, QTH Longitude and Pane settings in your browser's local storage.

Quick Robinson Views: Global Robinson projection views centered on either the Americas, Europe/Africa, or Asia/Oceania.

Mercator Zooms: High-detail regional Mercator projection views for all major continents.

System Controls: Quick toggles for the RSS Feed and Night Shading.

Home Button: Resets map to Mercator projection centered at the QTH longitude with no zoom.

Full Map Reset:  Global Mercator view centered on the prime meridian with no zoom.

Pane Manager: Data set selectior for Panes 0-3.

How to Use:

Open the file: Double-click the HTML file to open it in any modern web browser.

Configure: Enter your HamClock’s IP Address and enter your Home (QTH) Longitude (e.g., -90).

Navigate & Control: Click any of the Robinson Global or Mercator Zoon map buttons to update the map display.

Pane Views: Click on the PANE SETTNGS button to show tabs for Pane 0 (left-most pane in HamClock), Pane 1 (pane to right of callsign pane), Pane 2 (pane to the right of pane 1), and Pane 3 (pane to the right of pane 2).

Panes 0, 1, 2 & 3 have access to the various HamClock data set views (e.g., Auroa, Moon, DX Clstuer).  Select the views you want to have rotate through each pane.  Views selected for one pane grey out that view for other panes to avoid dublicates; but, you can still click on a greyed out selection to "steal" it from the other pane.  Also, beware that the check box settings are stored in the browser's local storage.  There is no means to read the HamClock pane settings.  Therefore, the selections a blank at startup and you have to manually "sync" the settings and any changes made directly via the HamClock UI will cause the utility Pane settings check boxes to be out of sync. 

The green "status dot" in the upper right hand corner flashes to confirm each command.

Troubleshooting:

API Access: Ensure "Remote API" is enabled in your HamClock setup menu and is using default Port 8080.

Connection: Ensure your device is on the same local network as the HamClock.
