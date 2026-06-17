# Errico Capstone
This repository tracks progress on my capstone project.

**Capstone Update 5-29-26**

Progress Update:
* Added interactive building inputs: building type, climate zone, floor area, occupancy, ceiling height
* Incorporated preliminary cooling load, ventilation airflow, and equipment sizing calculations
* Added building load summary dashboard with governing equations
* Developed HVAC system comparison module (VAV, Heat Pump, DOAS, RTU)
* Added annual energy consumption and operating cost analysis with system recommendation logic
* Created visualization tools for comparing HVAC system performance

Next steps: 
* Integrate ASHRAE 62.1 (national ventilation code) requirements so that building type influences outdoor air calculations to improve realism of HVAC sizing/selection

**Capstone Update 6-16-26**
Progress Update:
* Updated occupancy selection to allow either ASHRAE default values or user-defined custom occupancy inputs
* Integrated occupancy inputs directly into notebook calculations
* Added an ASHRAE 62.1 (national HVAC ventilation code) lookup table and incorporated it into calculations to enable automatic use of code-based ventilation rates

Next Steps:
* Explore adding zoning/room-level inputs to the building model
* Expand the system selection module to provide clearer justification for selected systems and include additional performance comparison tools and visualizations
