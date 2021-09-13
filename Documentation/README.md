# Rhaetian Railway: Bernina Express

This simulation covers the mountain route between Tirano., Italy and St. Moritz in Switzerland. Trains are operated by
*Rhaetian Railway* and consist of local *Panorama Express* services which are limited stop special tourist trains with glass observation
carriages, and *Regio* services which call at all main stations and serve request stops along the line.

The line operates through all seasons but is most famous for its winter running with trains climbing up the valley from
Poschiavo into Bernina Pass and ploughing through the snow on towards St. Moritz.

The route is mainly single track with regular passing points both in and out of station limits. 
Where possible the simulation has been kept as accurate as possible, however some station designs could not be directly
simulated due to unusual split platform designs (e.g. at Campcologno).

## Station List

* Tirano
* Campocologno
* Campascio
* Brusio
* Miralago
* Le Prese
* Li Curt
* Poschiavo
* Cadera
* Cavaglia
* Alp Grüm
* Ospizio Bernina
* Bernina Lagalb
* Bernina Diavolezza
* Bernina Suot
* Morteratsch
* Surovas
* Pontresina
* Punt Muragl Staz
* Celerina Staz
* St. Moritz


## Simulation

The included timetable covers the period from 06:15 to 13:15 during peak time in 2020. Due to the long distance and
low service frequency it is recommended you run the simulation at 4x speed and have both activity and log panels open
within ROS.

### Regio Services
Regional services are labelled as *Regio* in the timetable and operate between St. Moritz and Tirano. To model request
stops there is variation in the calling points for each service running up and down the line, make sure to pay close
attention to calling/passing points.

### Panorama Express
Panorama Express services are labelled also and run a limited stop service along the route.

**Note**: some services enter/exit
in the direction of Chur just north of Pontresina.

### Tips

* Be careful when handling services leaving depots, the route has very few starter signals. As an example if the points are not reset at *Poschiavo* after a service leaves the sidings, and that service changes direction, it will re-enter the siding.
* Try to time services to be at their stations on time not early. This is very important for ensuring services pass at the correct stations at the right time and so run on time.

## Feedback/Bugs
If you encounter any issues with this simulation please raise an issue on the repository for the project [here](https://github.com/Railway-Op-Sim/CH-Bernina-Express).
