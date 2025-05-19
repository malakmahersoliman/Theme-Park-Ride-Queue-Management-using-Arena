# Theme Park Ride Queue Simulation

## Project Title  
Simulation of Theme Park Visitor Flow and Ride Queue Optimization Using Arena

---



## Overview  
This project simulates the experience of visitors at a theme park, focusing on their movement through ticketing, rides, and other park activities. The model aims to analyze visitor flow, reduce queue times, and compare ticketing strategies (Fast Pass vs Regular) using Arena simulation software.

---

## Objectives  
- Model realistic visitor behavior in a theme park environment.  
- Compare and analyze Fast Pass and Regular ticket pathways.  
- Implement queue prioritization using Arena's Queue Sets.  
- Study visitor choices across multiple activities including rides, food court, rest area, and gift shop.  
- Evaluate queue lengths, ride utilization, and overall system efficiency.

---

## Model Features  

| Feature             | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| Ticket System       | Visitors select between Regular (80%) and Fast Pass (20%) tickets.         |
| Ride System         | Includes three rides: Roller Coaster, Ferris Wheel, and Kiddie Ride.       |
| Activity Choices    | Visitors choose to visit rides, dine at the food court, or relax in rest areas. |
| Gift Shop           | Visitors may stop by a gift shop before leaving the park.                  |
| Queue Priority      | Fast Pass ticket holders are prioritized using shared queue sets.          |
| Animation           | Entities are color-coded based on ticket type (e.g., red for Fast Pass, blue for Regular). |

---

## Core Logic Components  

- **Create Module**: Simulates scheduled visitor arrivals with peak and off-peak variations.  
- **Process Module**: Handles ticket counters and ride usage with defined delays and resources.  
- **Decide Module**: Routes entities based on ticket type, ride choice, activities, and exit conditions.  
- **Queue Sets**: Allow Fast Pass users to be served before Regular ticket holders in a shared queue.  
- **Assign Module**: Sets entity attributes such as TicketType for later decision-making.  
- **Dispose Module**: Represents visitors exiting the system.

---

## How to Run the Model  

1. Open the `.doe` Arena file using the student version of Arena.  
2. Set the simulation duration in the Run Setup (e.g., 480 minutes for a full park day).  
3. Start the simulation by clicking "Run" → "Go".  
4. Use the Run Controller to observe the system step-by-step if needed.  
5. Analyze the results via the "Reports → Category Overview" section.

---

## Files Included  

- `theme_park_simulation.doe`: Arena model file  
- `README.md`: This file  
- `screenshots/`: Folder with model images or animation visuals (optional)  
- `report.docx` or `report.pdf`: Full documentation (if submitted separately)

---

## Future Improvements  

- Implement time-triggered events (e.g., parades at specific hours).  
- Track monetary data such as ticket sales and shop revenue.  
- Add group size logic or age-based restrictions to rides.  
- Introduce weather-based ride availability (for advanced modeling).
