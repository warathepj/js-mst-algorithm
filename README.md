# MST Algorithms Visualization

An interactive web-based visualization tool for Minimum Spanning Tree (MST) algorithms, demonstrating both Kruskal's and Prim's algorithms in action.

## Features

- Interactive graph creation and manipulation
- Visual demonstration of two MST algorithms:
  - Kruskal's Algorithm
  - Prim's Algorithm
- Real-time visualization of algorithm execution
- Color-coded edges showing:
  - Regular edges (gray)
  - Currently considered edges (orange)
  - MST edges (green)

## Usage

1. Open `index.html` in a web browser
2. Use the control buttons to:
   - Add random nodes
   - Add random edges
   - Generate a random graph
   - Clear the graph
   - Select and run either Kruskal's or Prim's algorithm

## Controls

- **Add Node**: Adds a random node to the graph
- **Add Edge**: Adds a random edge between two existing nodes
- **Random Graph**: Generates a new random graph with 6 nodes and 10 edges
- **Algorithm Selector**: Choose between Kruskal's and Prim's algorithms
- **Start**: Begins the selected algorithm's visualization
- **Clear**: Removes all nodes and edges from the graph

## Algorithm Details

### Kruskal's Algorithm

Sorts edges by weight and builds the MST by adding the smallest edge that doesn't create a cycle.

### Prim's Algorithm

Grows the MST from a starting node, repeatedly adding the smallest edge that connects a new node to the existing tree.

## Implementation

Built using vanilla JavaScript and HTML5 Canvas for visualization. The implementation includes:

- Union-Find data structure for Kruskal's algorithm
- Priority queue simulation for Prim's algorithm
- Interactive canvas rendering
- Animated algorithm execution

## License

MIT License
