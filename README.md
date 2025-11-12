# 🛰️ Routing Simulator using Dijkstra’s Algorithm

## 📘 Course Project
**B.Tech – Computer Science and Engineering (CSE)**  
**Subject:** Computer Networks  
**Section:** A  
**Team Name:** **Class C**

| Name              | Roll Number  |
|-------------------|--------------|
| Aman Kumar Ojha   | 2023021008   |
| Alok Ranjan       | 2023021007   |
| Samarjeet         | 2023021057   |

---

## 🧠 Project Overview
The **Routing Simulator** is a web-based visualization tool that demonstrates **Dijkstra’s Shortest Path Algorithm** in the context of **computer network routing**.  
It simulates how routers discover the most efficient path between two nodes in a network based on **minimum cost/distance**.

Users can **add routers (nodes)**, **connect them (edges)** with weighted links, and **simulate data routing** between any two nodes.  
The simulator also generates a **Routing Table** showing each hop and the associated cost.

---

## 🎯 Objectives
- To understand how **routing algorithms** determine shortest paths in a network.  
- To visualize how **Dijkstra’s Algorithm** operates step-by-step.  
- To simulate **dynamic network creation** using nodes and weighted edges.  
- To analyze the resulting **routing table** and **packet movement** visually.  

---

## ⚙️ Features

### 🟢 Add Node
- Allows the user to add new routers dynamically by clicking anywhere on the canvas.
- Each router is assigned a unique name entered by the user.

### 🔗 Add Connection (Edge)
- Connects two routers by selecting them sequentially.
- Prompts the user to input the **link cost/weight** representing transmission cost.

### ▶ Simulate Routing
- Uses **Dijkstra’s Algorithm** to compute the **shortest path** between two selected routers.
- Visually animates packet movement along the computed path.

### 📋 Show Routing Table
- Displays the **hop-by-hop routing table** containing:
  - Hop number  
  - Source and destination router names  
  - Distance (edge weight)

### 🧹 Clear Network
- Clears all nodes, connections, and logs to reset the simulator for a new session.

---

## 🧮 Algorithm Used — Dijkstra’s Algorithm

**Dijkstra’s Algorithm** finds the shortest path between nodes in a weighted graph.  
It is widely used in **network routing protocols** such as OSPF (Open Shortest Path First).

### 🔸 Steps:
1. Initialize all node distances as **infinity**, except the source node (distance = 0).  
2. Select the node with the **minimum tentative distance** that hasn’t been visited yet.  
3. Update the distances to its neighboring nodes.  
4. Repeat until all nodes have been visited or the destination is reached.  
5. Construct the **shortest path** using the predecessor array.

---

## 🧩 Technologies Used
| Technology | Purpose |
|-------------|----------|
| **HTML5 Canvas** | For drawing the network graph |
| **CSS3** | For styling the interface and buttons |
| **JavaScript (ES6)** | For simulation logic and Dijkstra’s algorithm |
| **DOM Manipulation** | To update logs, routing tables, and modes dynamically |

---
## 🖥️ How to Run the Project

### Option 1 – Run Locally
1. Download or clone this repository:
   ```bash
   git clone https://github.com/yourusername/routing-simulator.git