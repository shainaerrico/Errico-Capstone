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

**Capstone Update 7-12-26**

Progress Update: 
* Expanded the building inputs to allow users to define the number of zones and enter design parameters for each zone, providing a more accurate building load calculation. Occupancy is automatically populated from ASHRAE 62.1, with an option to override the default values
* Generated an engineering report with technical justifications based on the calculated airflow requirements and zoning inputs
* Improved equipment selection by implementing a multi-criteria decision-making approach

Next Steps:
* Transition from simplified building-level assumptions to detailed zone-level load calculations
* Add heating load calculations, as the current tool is primarily focused on cooling analysis
* Improve calculation accuracy, validation, and overall data presentation
* Begin incorporating and testing the tool using real project data and building inputs

**Capstone Update 8-2-26**
Proress Update
* Published the Pluto notebook on a webpage through GitHub. Still troubleshooting display issues and working on hiding code cells: https://shainaerrico.github.io/Errico-Capstone/
* Started drafting the final report and presentation

Next Steps
* Finish refining the notebook
* Apply the tool to a real‑world project
* Continue developing the report, presentation, and webpage
