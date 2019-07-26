# MeetJeStad Carrier PCB

----
This PCB provides mounting space for a MeetJeStad device and allows it to be powered from mains (230VAC) with battery backup.. It also provides additional connectors for the Nova SDS011 PM2.5/PM10 particulate and ASAIR AM2305 tempature/humidity sensors. 

The pcb is developed by The Things Network Apeldoorn community for the 'Hitte Markstraat' project commissioned by the Dutch Apeldoorn municipality and is primarily a single layer through-hole design to make the assembly easy; pcb etching as well as soldering.

**WARNING: This pcb carries mains 230V AC which is potentially deadly! Do not work on this board with mains power connected!**

## Components
Below is a list of primary components for this design:

* Housing: Bopla M-237-V0
* MeetJeStad node v2
* Power regulation and battery charger: Adafruit PowerBoost 500c
* Battery backup: 1200mA LiPo 3.7V pouch
* AC/DC Power converter: MeanWell IRM-03-05

In the schematic each component has an OC_xxx attribute with an product number for a supplier, mainly Farnell for the passives, connectors and other small componetents.

