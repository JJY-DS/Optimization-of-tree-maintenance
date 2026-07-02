
# 🌳 Optimization of Tree Maintenance — Paris Open Data

> Data-driven analysis to optimize urban tree maintenance scheduling across Paris domains using growth stage classification.

---

## 🎯 Project Overview

Urban tree maintenance is costly and resource-intensive. This project uses **Paris Open Data** to analyze tree growth stages across city domains, enabling smarter scheduling of maintenance visits and more efficient allocation of staff and resources.

---

## 🌱 Business Problem

> **How can the city of Paris optimize the number and timing of tree maintenance visits based on tree growth stages?**

Different growth stages require different levels of care:

| Stage | Label | Maintenance Need |

| Young | **J** | Maximum care required |
| Young Adult | **JA** | Shaping & pruning needed |
| Adult | **A** | Minimal intervention |
| Mature | **M** | Base/root checks only |

---

## 🔄 Project Pipeline

```
Paris Open Data (Raw)
        ↓
Data Cleaning & Outlier Removal
        ↓
Feature Engineering (Binning by Circumference & Height)
        ↓
Growth Stage Classification (J / JA / A / M)
        ↓
Descriptive Statistical Analysis
        ↓
Regional Visualizations by Domain & Tree Type
        ↓
Maintenance Planning Recommendations
```

---

## 📈 Key Findings

### Tree Distribution by Growth Stage (Domain: Alignment)

| Growth Stage | Tree Count |

| J — Young | 16,802 |
| JA — Young Adult | 20,503 |

### Species Spotlight: Platanus (Plane Tree)

| Growth Stage | Count |

| J — Young | 4,751 |
| JA — Young Adult | 6,407 |

> These figures can directly inform visit frequency and staffing levels by domain and species.

---

## 💡 Key Insights

- **Circumference and height** are reliable proxies for determining a tree's development stage
- Domains with high concentrations of **J and JA stage trees** require more frequent visits and dedicated staff
- Analysis can be used to **build a maintenance calendar** by region, reducing unnecessary visits to Adult/Mature trees
- Species-level breakdown (e.g. Platanus) allows for targeted maintenance planning

---

## 🛠️ Tools & Technologies

| Tool | Purpose |

| Python | Core analysis language |
| Pandas / NumPy | Data cleaning & transformation |
| Matplotlib / Seaborn | Visualizations by domain & stage |
| Jupyter Notebook | Development & presentation |
| PowerPoint | Stakeholder presentation |

---

## 📁 Repository Structure

```
Optimization-of-tree-maintenance/
│
├── Optimization_trees_visualization_project.pptx   # Full presentation with visuals
└── README.md
```

> 💡 The PowerPoint includes all visualizations, regional maps, and growth stage distribution charts.

---

## 🌍 Data Source

**Paris Open Data** — publicly available dataset on urban trees in Paris  
🔗 https://opendata.paris.fr (updated every year)

---

## 👩‍💻 Author

**Dr. Jyoti Pabbi** — Data & BI Analyst | Nürnberg, Germany  
🔗 [LinkedIn](https://www.linkedin.com/in/drjyoti25/) · [GitHub](https://github.com/JJY-DS)
