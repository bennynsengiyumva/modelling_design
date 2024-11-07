
Here's the specification (narration) for the Gishushu Traffic Light System, based on the state diagram provided:

Specification: Gishushu Traffic Light System
Overview
The Gishushu Traffic Light System governs the traffic flow at a major intersection, managing both the North-South and East-West directions. The system operates through alternating green and yellow lights, ensuring smooth transitions between different phases to allow safe and efficient movement for both vehicles and pedestrians.

State Descriptions
The traffic light system operates in a cycle, switching between four primary states:

North-South Green

Description: The North and South directions are given a green light, allowing vehicles in these directions to move. Vehicles in the East and West directions are stopped at this point.
Duration: The green light for North-South remains on for a fixed duration, depending on the traffic conditions.
Transitions: After the green light duration ends, the system transitions to the North-South Yellow state.
North-South Yellow

Description: The North-South direction receives a yellow light, signaling that the green light will soon turn off, and vehicles must prepare to stop. East-West vehicles remain stopped.
Duration: The yellow light remains active for a brief duration, typically 3-5 seconds.
Transitions: After the yellow light duration ends, the system transitions to the East-West Green state.
East-West Green

Description: The East and West directions are given a green light, allowing vehicles in these directions to proceed. North-South traffic remains stopped at this point.
Duration: The green light for East-West remains on for a fixed duration, depending on the traffic conditions.
Transitions: After the green light duration ends, the system transitions to the East-West Yellow state.
East-West Yellow

Description: The East-West direction receives a yellow light, signaling that the green light will soon turn off, and vehicles must prepare to stop. North-South traffic remains stopped.
Duration: The yellow light remains active for a brief duration, typically 3-5 seconds.
Transitions: After the yellow light duration ends, the system transitions back to the North-South Green state, restarting the cycle.
Cycle Flow
The system operates in a continuous loop, alternating between North-South Green and East-West Green states, with corresponding Yellow transitions. The cycle is designed to balance the flow of traffic in both directions and is timed to optimize vehicle movement while maintaining safety at the intersection.

Pedestrian Signals (Optional)
For pedestrian crossings, there could be an additional set of signals integrated into the system:

Walk Signal: Allows pedestrians to cross safely while the corresponding traffic light is red.
Don’t Walk Signal: Instructs pedestrians to stop and wait while vehicles are moving.
