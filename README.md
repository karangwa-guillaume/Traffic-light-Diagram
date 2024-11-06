Specification (Narration) of Gishushu Traffic Light System:
Initialization:

The system starts in the NS_Green state, where vehicles traveling from North to South (main road) are allowed to move. The lights for other directions are Red at this point.
The pedestrian lights for the North-South direction are Red, meaning pedestrians cannot cross the main road.
NS Green to Yellow:

When the NS_Green light has been active for the designated green duration, it transitions to NS_Yellow, signaling that the North-South traffic will soon stop, and vehicles should prepare to stop.
At this point, pedestrians are still not allowed to cross.
NS Yellow to Red:

After the yellow phase, the NS_Red light turns on for the main road, halting the vehicles traveling north and south.
Pedestrian signals for the North-South direction turn Green, allowing pedestrians to cross safely.
The system then transitions to the EW_Green state, where vehicles traveling East to West are allowed to go, and pedestrians are not allowed to cross during this phase.
EW Green to Yellow:

After the green duration for East-West traffic, the EW_Yellow light signals that the East-West vehicles should prepare to stop.
Pedestrians waiting for the East-West crossing will have their lights turn Green, allowing them to cross safely when vehicles are stopped.
EW Yellow to Red:

The EW_Red light turns on after the yellow light, halting the vehicles moving east-west.
The pedestrian light for East-West is then turned Red, meaning pedestrians must stop crossing.
North-East (NE) and South-East (SE) Direction Transitions:

Next, the system switches to the NE_Green state, allowing vehicles traveling from North to East and from South to East to go.
Pedestrian signals for North-East and South-East are Green, allowing pedestrians to cross diagonally while the vehicles move in their respective directions.
After the allotted time for NE_Green and SE_Green, these states transition to NE_Red and SE_Red respectively, signaling both vehicles and pedestrians to stop.
South-West (SW) and North-West (NW) Direction Transitions:

Next, the system allows vehicles to go in the SW_Green and NW_Green states, while pedestrians can cross diagonally if their corresponding pedestrian lights are Green.
The pedestrian lights for South-West and North-West turn Red once the vehicle lights change.
West-East (WE) Transitions:

The system allows vehicles traveling West to East to move, while pedestrians wishing to cross West to East are granted a Green pedestrian light to cross the street when vehicles are stopped.
After the green duration for West-East traffic ends, the pedestrian light turns Red, and the system transitions back to the NS_Green state, ready to begin the cycle again.
Cycle Repeats:

The traffic light system repeats this cycle, ensuring that each direction of traffic (North-South, East-West, etc.) gets its fair share of green time while ensuring pedestrian safety.
Pedestrian lights are aligned with the vehicle signal phases: when vehicles stop (i.e., Red), pedestrians are given the chance to cross, and when vehicles are allowed to go, pedestrians must stop.
