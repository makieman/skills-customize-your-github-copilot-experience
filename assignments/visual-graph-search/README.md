# 📘 Assignment: Visual Graph Search

## 🎯 Objective

Build a Python program that represents a network as a graph and visually traces breadth-first search (BFS) and depth-first search (DFS). In one focused lesson, you will connect a visual model of nodes and edges to the way algorithms explore data.

## 📝 Tasks

### 🛠️ Model a Graph

#### Description

Represent the network below as an adjacency-list dictionary. Draw the same graph in your notes or on paper, labeling the nodes and edges.

```text
      B --- D
     / \     \
    A   C --- E
     \       /
      F -----
```

#### Requirements

Completed program should:

- Store every node and its directly connected neighbors
- Treat each connection as bidirectional
- Print the neighbors for a node selected by the user

### 🛠️ Trace BFS and DFS

#### Description

Implement BFS and DFS to search for a target node. Record the order in which each algorithm visits nodes, then compare the results with your graph drawing.

#### Requirements

Completed program should:

- Implement `breadth_first_search(graph, start, target)`
- Implement `depth_first_search(graph, start, target)`
- Track visited nodes so each node is processed at most once
- Return the visit order and whether the target was found
- Display a clear step-by-step trace for both searches

### 🛠️ Explain the Difference

#### Description

Use your trace to explain how the queue used by BFS and the stack or recursion used by DFS change the search path.

#### Requirements

Completed program should:

- Show the queue or stack state after each search step
- Compare the BFS and DFS visit orders for at least two start/target pairs
- Explain one situation where BFS is a better choice than DFS
- State the time complexity of each search in terms of vertices and edges
