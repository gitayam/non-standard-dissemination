# Graphical Training Aid (GTA): Leaflet Dissemination using sUAS

This document is for academic purposes only. It provides the guidelines and manual calculations for planning and executing leaflet dissemination using Small Unmanned Aerial Systems (sUAS). The GTA incorporates open source techniques adapted specifically for sUAS operations, contrasting standard aerial dissemination practices (referenced in GTA 33-01-003).

This document further deviates from GTA 33-01-003 by using meters and kilometers instead of feet and nautical miles. A conversion to nautical miles and feet is provided in the appendix.
## Terms and Definitions

### sUAS

Small Unmanned Aerial System

### Leaflet

A leaflet is a single sheet of paper or other material that is used to disseminate information.

### Leaflet Dispersion

The dispersion of a leaflet is the area that the leaflet will cover when it is dropped from a sUAS.

### Wind Azimuth

The wind azimuth is the direction from which the wind is blowing.

### Aircraft Descent Time

The descent time is the time it takes for the aircraft to descend to the target altitude.

### Speed
1. Aircraft Speed: The speed of the aircraft is the speed at which the aircraft is flying.
2. Wind Speed: The speed of the wind is the speed at which the wind is blowing.
### Drift
1. Forward Drift: The forward drift is the distance the leaflet will drift forward due to the wind.
2. Lateral Drift: The lateral drift is the distance the leaflet will drift laterally due to the wind.


Section 1: Operational Considerations

sUAS operations require accurate wind estimation and leaflet drift calculations for effective dissemination.

For comparison and historical reference, traditional aircraft methods (C-130, F-16, UH-60) and high-altitude leaflet dissemination techniques are detailed in GTA 33-01-003 (June 2014).

Always validate calculations with operational test drops when possible to confirm actual drift and dispersion.

Section 2: Calculating Leaflet Dispersion from sUAS

# Appendix A: UAS Leaflet Drop Calculation Worksheet (Meters – w/ Auto-Rotation Factor)

This worksheet provides a manual calculation method for sUAS leaflet drops using meters. The FM-based auto-rotation factor of 1.11 enhances accuracy in lateral drift estimation.

Step-by-Step Calculation

Step 1: Plot Wind Azimuth

Mark the center point (target) on your map.

Draw a line in the wind's direction using a map protractor or compass rose (no back azimuth required).

Step 2: Descent Time

Formula:

Example:100 m ÷ 0.76 ≈ 131.6 seconds

Step 3: Forward and Lateral Drift

UAS speed: 8.75 m/s (~17 knots)

Convert wind speed to meters per second (m/s):



Forward Drift:



Lateral Drift (with auto-rotation factor):



Step 4: Total Drift Estimate (Major Axis)

Formula:

Step 5: Spread Width (Minor Axis)

Formula:

Step 6: Ellipse Area

Formula:

Step 7: Leaflet Density

Formula:

Quick Reference Calculation Table

Step

Parameter

Formula/Constants

Example Calculation

1

Wind Azimuth

Map/Compass

Direction line drawn on map

2

Descent Time (s)

Altitude (m) ÷ 0.76

100 m ÷ 0.76 = 131.6 s

3

UAS Speed (Forward Drift)

8.75 m/s

8.75 × 131.6 s = 1151.5 m

3

Wind Speed Conversion (m/s)

Wind (kts) × 0.514

10 kts × 0.514 = 5.14 m/s

3

Lateral Drift (Auto-Rotation)

Wind (m/s) × Time (s) × 1.11

5.14 m/s × 131.6 s × 1.11 = 751.3 m

4

Total Drift (Major Axis)

Forward Drift + (Lateral Drift ÷ 2)

1151.5 m + (751.3 m ÷ 2) = 1527.2 m

5

Minor Axis

Total Drift × Spread Factor

1527.2 m × 0.4 = 610.9 m

6

Ellipse Area

Major Axis × Minor Axis × 0.785

1527.2 m × 610.9 m × 0.785 ≈ 732,791 m²

7

Leaflet Density

(Leaflets ÷ Area) × 100

(10,000 ÷ 732,791 m²) × 100 ≈ 1.36 per 100 m²

# Appendix B: sUAS Leaflet Drop Tables

# Appendix C: sUAS Leaflet Planning Examples

# Appendix D: References

GTA 33-01-003: Aerial Delivery Operations (Headquarters, Department of the Army, June 2014).

UAS Leaflet Drop Characteristics, referenced in FM 3-05.301, and associated sUAS operational testing documents.

This document provides a standardized approach, ensuring mission effectiveness and operational safety in leaflet dissemination with sUAS.

