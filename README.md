# Refugee-Movement-Around-the-World
# Refugee Movement Around the World

Analyzed global refugee movement patterns using Neo4j graph analytics to uncover migration routes, host country networks, and temporal trends. This project visualizes complex relational data to surface insights about displacement flows and resettlement patterns across regions and time periods.

***

## 🎯 What It Does

* **Graph Analytics:** Uses Neo4j to model refugee movements as a network of countries, routes, and time periods

* **Migration Route Discovery:** Identifies key pathways and corridors used by displaced populations

* **Host Country Network Analysis:** Understands which countries receive the most refugees and how those relationships evolve

* **Temporal Trending:** Tracks how refugee flows change over decades in response to global events

## 🛠️ Tech Stack

* **Graph Database:** Neo4j, Cypher Query Language

* **Data Analysis:** Python, Pandas, NumPy

* **Visualization:** NetworkX, Matplotlib

* **Data Source:** UNHCR Refugee Statistics

## 📊 Key Findings

| Insight                   | Description                                                                           |
| ------------------------- | ------------------------------------------------------------------------------------- |
| Major Migration Corridors | Identified the most frequently used routes between origin and asylum countries        |
| Host Network Hubs         | Discovered which nations serve as central nodes in the global refugee support network |
| Temporal Shifts           | Analyzed how conflicts in specific regions trigger cascading displacement effects     |

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/Biankapaul/refugee-movement-analysis.git
cd refugee-movement-analysis

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter notebook
jupyter notebook Refugee_Movement_Around_The_World_Code.ipynb
```

## 📓 Notebook Overview

The analysis is contained in `Refugee_Movement_Around_The_World_Code.ipynb`:

1. **Data Ingestion:** Load and clean UNHCR refugee data
2. **Graph Construction:** Build Neo4j graph schema with nodes (countries, years) and edges (refugee flows)
3. **Network Analysis:** Run graph algorithms to find centrality, shortest paths, and community clusters
4. **Visualization:** Generate network maps and temporal trend charts

## 📝 About This Project

Built as part of the UC Berkeley MIDS program. This project demonstrates the power of graph databases for understanding complex human migration patterns — going beyond traditional tabular analysis to reveal hidden network structures.

## 📬 Contact

* LinkedIn: [linkedin.com/in/bianka-paul-004b03194](https://www.linkedin.com/in/bianka-paul-004b03194)

* Medium: [@paulbianka](https://medium.com/@paulbianka)

