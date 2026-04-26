1. Mapping architectural elements to graph components

Architectural spaces are represented as nodes, while their physical or functional connections are represented as edges:

Hotel rooms (first floor) are mapped as nodes and highlighted in red, with the main entrance embedded within this system.
Hotel rooms (second floor) are mapped as nodes in blue, distinguishing vertical zoning between floors.
The double-height entrance space with stairs is represented as a central node, acting as a vertical circulation hub.
Corridors are represented as intermediary nodes in green, linking rooms to the central entrance and enabling horizontal movement.
MEP (Mechanical, Electrical, Plumbing) rooms are mapped as nodes in yellow, positioned on the periphery to reflect their service role.
Windows are abstracted as cyan nodes, and doors as orange nodes, representing points of environmental access (light/air) and physical access (entry/exit).

2. Logic behind node and edge definitions
Nodes represent discrete architectural elements or functional units (rooms, corridors, entrance, MEP spaces, doors, windows). Each node corresponds to a spatial or operational entity with a specific role in the building.
Edges represent direct relationships or accessibility between nodes:
A connection between a room and a corridor indicates circulation access.
A connection between a corridor and the entrance/stair node represents vertical and horizontal flow.
A room–door edge defines entry points, while a room–window edge defines environmental connections.
Connections to MEP rooms represent service adjacency or infrastructure linkage rather than public circulation.
