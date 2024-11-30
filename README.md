# Emergency Nav
**Emergency Nav** is a navigation system designed to assist in emergency situations by providing the shortest and safest routes to a destination. The application is particularly useful for first responders, emergency teams, or individuals needing quick and reliable directions during critical scenarios.

### Features
**Shortest Path Calculation:** Uses graph-based algorithms to determine the most efficient route.

**Dynamic Updates:** Incorporates real-time data (e.g., roadblocks, hazards) for safer navigation.

**User-Friendly Interface:** Easy-to-use interface for quick route planning.

**Scalable Design:** Can integrate with external data sources like GPS or live traffic updates.

## Requirements
Ensure the following dependencies are installed:

**Python (>= 3.7)**

**NetworkX**

**Matplotlib**

**NumPy**

**Pandas**

### Install dependencies using:

bash

pip install -r requirements.txt


## How It Works
**Graph Representation:** The map is represented as a graph with nodes (locations) and edges (routes).

**Pathfinding Algorithm:** Algorithms like Dijkstra or A* are used to compute the shortest path.

**Dynamic Adjustments:** Real-time updates adjust the graph for hazards or closed routes.

**Visualization:** Routes are displayed visually for better understanding.


## Usage

**Clone the repository:**

**bash**

git clone https://github.com/ShubhamDwn/Emergency_Nav.git

cd Emergency_Nav

Input your map data (nodes and edges) in the required format.

Run the navigation script:

**bash**

python emergency_nav.py

Follow the prompts to enter start and end points, and view the calculated route.

### Example

#### Input:

**Start:** Node A

**Destination:** Node B

#### Output:

**Shortest Path:** Node A → Node C → Node B

**Distance:** 10 units

Graphical representation of the route will also be displayed.

## Future Enhancements:
Add support for live GPS and traffic data.

Implement multi-language support for broader usability.

Optimize algorithms for faster computation on large datasets.

Introduce voice-assisted navigation.

## Contributing
Contributions are welcome! Fork the repository, make your changes, and submit a pull request. Ensure your contributions align with the project goals.


## Author
Developed by Shubham Dhavan and Team.
Feel free to reach out for queries, collaborations, or feedback!
