DHAKA SMART ROUTE FINDER - REAL MAP VERSION

RUN
1. Extract the ZIP.
2. Open the folder in VS Code.
3. Open index.html using Live Server.
4. Keep internet connected because Leaflet and OpenStreetMap tiles load online.

REAL PARTS
- OpenStreetMap background
- Interactive zoom/pan
- Approximate real coordinates for selected Dhaka places
- Geographic straight-line distance calculated from latitude/longitude

SIMPLIFIED PROJECT PARTS
- Graph edges are educational connections between locations.
- Edge lines are straight overlays, not exact turn-by-turn road polylines.
- Traffic/flood/crime values are simulation values, not live data.

ALGORITHMS
BFS, DFS, UCS, DLS, IDS, Bidirectional, Greedy Best-First, A*

EDGE WEIGHT
Distance(km) + 2*Traffic + 3*Flood + 2.5*Crime

BEST DEMO
Source: Mirpur
Destination: Motijheel
Algorithm: A*
Try Normal Day, Heavy Rain, Road Block, then Compare All.
