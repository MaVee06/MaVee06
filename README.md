# 🚍 Smart Campus Shuttle System

This project models the shuttle system at Mangosuthu University of Technology as part of a digital transformation initiative. It includes a directed graph, an adjacency matrix, and an adjacency list (hash map) to represent shuttle routes between key campus locations.

---

## 📍 Key Locations (Nodes)
- Admin Building
- Engineering Block
- Science Labs
- Library
- ICT Department
- Residence A
- Residence B
- Cafeteria
- Sports Complex
- Main Entrance

---

## 🛣️ Shuttle Routes (Edges)

- Admin → Library  
- Library → ICT  
- ICT → Engineering  
- Engineering → Science Labs  
- Science Labs → Cafeteria  
- Cafeteria → Residence A  
- Residence A → Residence B  
- Residence B → Main Entrance  
- Main Entrance → Admin  
- Library → Sports (event-based)

---

## 🧠 What This Project Does

- Models campus routes using a **Directed Graph**
- Represents the routes using:
  - 🔗 Adjacency List (Hash Map)
  - 📊 Adjacency Matrix
- Visualizes the route map using Python libraries

---

## 🐍 Technologies Used

- Python
- `networkx`
- `matplotlib`
- `pandas`

Install dependencies using:

```bash
pip install networkx matplotlib pandas

