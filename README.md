# Data Mining Methodologies — CRISP-DM, KDD, and SEMMA

This repository contains three comprehensive end-to-end data mining projects, each demonstrating a different industry-standard methodology:

## 📂 Projects

### 1. [CRISP-DM — Telco Customer Churn](./crispdm_telco/)
**Dataset:** IBM Telco Customer Churn  
**Task:** Binary classification (predict customer churn)  
**Methodology:** CRISP-DM (Cross-Industry Standard Process for Data Mining)

**Phases covered:**
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment (demo with Gradio UI)

**Notebook:** [`crispdm_telco.ipynb`](./crispdm_telco/crispdm_telco.ipynb)

- 📹 Video explanation: *coming soon*
- 📝 Medium article: *coming soon*

---

### 2. [KDD — UCI Adult (Census Income)](./kdd_adult/)
**Dataset:** UCI Adult (Census Income)  
**Task:** Binary classification (predict income >$50K)  
**Methodology:** KDD (Knowledge Discovery in Databases)

**Phases covered:**
1. Selection
2. Preprocessing
3. Transformation
4. Data Mining
5. Interpretation & Evaluation

**Notebook:** [`kdd_adult.ipynb`](./kdd_adult/kdd_adult.ipynb)

- 📹 Video explanation: *coming soon*
- 📝 Medium article: *coming soon*

---

### 3. [SEMMA — UCI Bank Marketing](./semma_bank/)
**Dataset:** UCI Bank Marketing  
**Task:** Binary classification (predict term deposit subscription)  
**Methodology:** SEMMA (Sample, Explore, Modify, Model, Assess)

**Phases covered:**
1. Sample
2. Explore
3. Modify
4. Model
5. Assess

**Notebook:** [`semma_bank.ipynb`](./semma_bank/semma_bank.ipynb)

- 📹 Video explanation: *coming soon*
- 📝 Medium article: *coming soon*

---

## 🚀 Getting Started

All notebooks are designed to run in **Google Colab** and include automatic dependency installation.

### Running the notebooks:

1. Click on any notebook link above
2. Download the `.ipynb` file
3. Upload to [Google Colab](https://colab.research.google.com/)
4. Run all cells (dependencies will be installed automatically)

Alternatively, you can run locally:

```bash
# Clone the repository
git clone https://github.com/ArshanBhanage/crispdm-semma-ldd.git
cd crispdm-semma-ldd

# Install Jupyter
pip install jupyter notebook

# Launch Jupyter and open any notebook
jupyter notebook
```

## 📊 Methodology Comparison

| Methodology | Origin | Phases | Industry Focus | Best For |
|-------------|--------|--------|----------------|----------|
| **CRISP-DM** | 1996, industry consortium | 6 phases (cyclic) | Cross-industry | Business-driven projects with deployment focus |
| **KDD** | 1996, academic (Fayyad et al.) | 5 phases (linear) | Database research | Data-centric discovery and research |
| **SEMMA** | SAS Institute | 5 phases (linear) | SAS tooling | Rapid modeling and statistical analysis |

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas**, **numpy** — data manipulation
- **scikit-learn** — machine learning models and pipelines
- **matplotlib** — visualization
- **Gradio** — UI deployment demo (CRISP-DM)
- **ucimlrepo** — dataset fetching (KDD, SEMMA)

## 📁 Repository Structure

```
crispdm-semma-ldd/
├── crispdm_telco/
│   ├── crispdm_telco.ipynb
│   └── README.md
├── kdd_adult/
│   ├── kdd_adult.ipynb
│   └── README.md
├── semma_bank/
│   ├── semma_bank.ipynb
│   └── README.md
└── README.md (this file)
```

## 🎯 Learning Objectives

By exploring these notebooks, you will:

- Understand the **differences and similarities** between CRISP-DM, KDD, and SEMMA
- Learn **end-to-end workflows** for classification problems
- Master **feature engineering**, **model selection**, and **evaluation** best practices
- See how to **calibrate probabilities** and make **business-driven threshold decisions**
- Gain experience with **scikit-learn pipelines** for reproducible ML

## 📚 References

- **CRISP-DM**: [Wikipedia](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining)
- **KDD**: Fayyad, U., Piatetsky-Shapiro, G., & Smyth, P. (1996). *From Data Mining to Knowledge Discovery in Databases*
- **SEMMA**: [SAS Documentation](https://documentation.sas.com/doc/en/emref/14.2/emref_semma_overview.htm)

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report issues or suggest improvements
- Add new methodology implementations
- Enhance documentation or add visualizations

## 📧 Contact

For questions or collaboration opportunities, reach out via GitHub issues or connect on:

- **GitHub:** [@ArshanBhanage](https://github.com/ArshanBhanage)
- **Medium:** *link coming soon*
- **Video walkthrough:** *link coming soon*

---

⭐ **If you find this repository helpful, please consider starring it!** ⭐
