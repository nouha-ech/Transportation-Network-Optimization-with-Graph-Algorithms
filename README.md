# Operational Research for Transportation Networks: UK Road Network Study


##  Project Overview

This project was developed as part of the **Operational Research and Optimization** module.

The objective is to apply graph theory and optimization techniques to a real-world transportation network. The study focuses on the road network of the United Kingdom, modeled as a graph to analyze accessibility, connectivity, and route optimization.

Transportation networks can be represented as graphs where intersections or locations are nodes and roads are edges. This representation enables the application of graph algorithms and operational research methods to solve practical problems related to transportation planning and cost minimization.

---

## Objectives

The main objectives of this project are to:

- Model a real transportation network as a graph.
- Analyze network structure and connectivity.
- Study accessibility between locations.
- Implement graph traversal algorithms.
- Find optimal routes between nodes.
- Minimize transportation and travel costs.
- Apply operational research concepts to a real-world dataset.

---

## Case Study

The project explores the road transportation network of the United Kingdom.

Using graph modeling techniques, the network is analyzed to answer questions such as:

- How connected is the network?
- Which locations are the most accessible?
- What is the shortest path between two points?
- How can transportation costs be reduced?
- How efficient is the overall network structure?

---

## Dataset

A real-world transportation dataset was used to represent the UK road network.

The dataset contains:

- Locations and intersections
- Road connections
- Connectivity information
- Distance-based relationships between locations

The data is transformed into a graph structure for analysis and optimization.

---

# Part I: Graph Structures, Modeling and Traversal

## Graph Construction

The transportation network is represented by a graph:

- **Nodes (Vertices):** cities, intersections, or transportation hubs.
- **Edges:** roads connecting two locations.
- **Weights:** distances or transportation costs associated with each road.

Mathematically:

G = (V, E)

Where:

- V represents the set of vertices.
- E represents the set of edges.

---

## Network Analysis

Several structural properties of the network are studied:

- Number of nodes
- Number of edges
- Degree distribution
- Connected components
- Network density
- Connectivity level

These metrics provide insights into the organization and accessibility of the transportation system.

---

## Breadth-First Search (BFS)

Breadth-First Search is used to explore the graph level by level.

Applications:

- Reachability analysis
- Accessibility evaluation
- Exploration of neighboring locations

### Steps

1. Start from a selected node.
2. Visit all adjacent nodes.
3. Continue level by level until all reachable nodes are explored.

---

## Depth-First Search (DFS)

Depth-First Search explores one branch completely before backtracking.

Applications:

- Connectivity analysis
- Graph exploration
- Component identification
- Cycle detection

### Steps

1. Start from a selected node.
2. Move to an unvisited neighbor.
3. Continue recursively.
4. Backtrack when no further nodes are available.

---

## Accessibility Analysis

Accessibility measures the ease with which locations can reach other locations within the network.

The analysis focuses on:

- Highly connected locations
- Isolated areas
- Network reachability
- Accessibility performance

---

# Part II: Network Optimization

## Shortest Path Problem

One of the primary challenges in transportation systems is finding the optimal route between locations.

The objective is to minimize:

- Distance
- Travel time
- Transportation cost

---

## Dijkstra's Algorithm

Dijkstra's algorithm is used to compute shortest paths in weighted graphs.

### Advantages

- Finds optimal routes
- Efficient for transportation networks
- Widely used in navigation systems

### Outputs

- Shortest path
- Minimum distance
- Ordered sequence of visited nodes

---

## Cost Optimization

Transportation efficiency depends directly on route optimization.

The goal is to:

- Reduce travel distances
- Lower transportation costs
- Improve overall network efficiency

Applications include:

- Logistics planning
- Delivery routing
- Transportation management

---

## 
