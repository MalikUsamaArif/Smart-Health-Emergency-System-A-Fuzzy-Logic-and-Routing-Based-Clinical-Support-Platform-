# Smart Health Emergency System

[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Initial Release: Fuzzy Triage + A* Routing System

### Overview
AI-powered emergency response platform featuring:
- **Fuzzy Logic Triage**: Patient risk classification using vital parameters
- **A* Ambulance Routing**: Optimal pathfinding with real-world road data
- **Clinical Dashboard**: Real-time monitoring interface

![System Architecture](docs/architecture.png)

## Key Features
| Module | Components | Technologies |
|--------|------------|--------------|
| **Fuzzy Triage** | 6 input parameters, 529 rules, Risk scoring | `simpful`, `scikit-fuzzy` | 
| **A* Routing** | OSM data integration, Path penalties, Geocoding | `osmnx`, `networkx`, `geopy` |
| **Dashboard** | Patient analytics, Route visualization, Records management | `streamlit`, `folium`, `pandas` |

## Getting Started
```bash
git clone https://github.com/yourusername/smart-health-emergency.git
pip install -r requirements.txt
streamlit run app.py
