

🧠 PCA for Construction Network Analysis

This repository contains a research-driven implementation of Principal Component Analysis (PCA) tailored for unlabeled construction network datasets. The project introduces a novel method to rank network metrics based on their statistical importance, supporting decision-making in construction management and digital twin modeling.

---

📌 Project Overview

- Challenge: Traditional PCA is designed for labeled datasets, but construction networks often lack clear labels.  
- Innovation: This project adapts PCA to work with unlabeled graph-based data, enabling the ranking of network features (e.g., degree centrality, betweenness, clustering coefficient) by their contribution to structural complexity and communication quality.  
- Application: Supports strategic planning, communication optimization, and metric prioritization in construction informatics.

---

📚 Published Research

This project is based on the peer-reviewed paper:

“A novel PCA-based approach for ranking network metrics in construction communication analysis”  
Published in: Journal of Cleaner Production, Volume 320, 2021  
Authors: Ali Rahimian, et al.  
🔗 Read the paper on ScienceDirect

---

🧰 Technologies Used

- Python 3.9+  
- NumPy, Pandas, Scikit-learn for data processing and PCA  
- NetworkX for graph metric extraction  
- Matplotlib / Seaborn for visualization  
- Jupyter Notebook for interactive analysis

---

📁 Repository Structure

`
PCA-for-Construction-Network-Analysis/
├── data/                    # Sample network datasets (CSV, GraphML)
├── notebooks/               # Jupyter notebooks for PCA and metric ranking
├── scripts/                 # Python scripts for preprocessing and PCA execution
├── results/                 # Output plots and ranked metrics
├── README.md                # Project overview
└── requirements.txt         # Dependencies
`

---

🚀 Getting Started

1. Clone the repository  
   `bash
   git clone https://github.com/Alirahimia/PCA-for-Construction-Network-Analysis.git
   cd PCA-for-Construction-Network-Analysis
   `

2. Install dependencies  
   `bash
   pip install -r requirements.txt
   `

3. Run the notebook  
   `bash
   jupyter notebook notebooks/PCANetworkAnalysis.ipynb
   `

---

📊 Key Results

| Metric | PCA Weight | Interpretation |
|--------|------------|----------------|
| Degree Centrality | 0.42 | Most influential in network structure  
| Clustering Coefficient | 0.31 | Indicates local connectivity  
| Betweenness | 0.18 | Moderate role in communication flow  
| Eigenvector Centrality | 0.09 | Least impact in this dataset  

> Note: Results vary by dataset and network topology.

---
🤝 Contact

For academic collaboration or questions, feel free to reach out:

- Ali Rahimian  
- Email: alirahimian21@yahoo.com  
- GitHub: Alirahimia
