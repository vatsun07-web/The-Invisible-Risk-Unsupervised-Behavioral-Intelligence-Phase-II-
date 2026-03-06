# The Invisible Risk: Unsupervised Behavioral Intelligence (Phase II)
### Unlocking Hidden Opportunity in a 2.2M-Record P2P Lending Portfolio

## 🔗 Project Evolution: From Phase I to Phase II
This project is the strategic continuation of **Phase I: Credit Risk Assessment (Supervised Default Prediction)**. 

* **Phase I (The Shield):** Developed a binary classifier to predict "will they default?" based on historical labels.
* **Phase II (The Radar):** Developed an unsupervised "Behavioral DNA" framework to understand **why** they default and to find **hidden opportunities** that standard predictive models miss.

By moving from reactive scoring to proactive behavioral intelligence, this phase introduces an **Early Warning System (EWS)** capable of flagging risk long before a default event occurs.



---

## 🚀 Executive Summary
This report details Phase II of the behavioral risk analysis for a portfolio of 2.2 million P2P lending records. By deploying unsupervised machine learning, we successfully mapped the "Behavioral DNA" of the entire portfolio into five distinct archetypes.

**Strategic Impact:**
* **Identified "Invisible Risk"**: Discovered that high-income "Affluent Spenders" (Cluster 3) default 60% more often than their peers due to lifestyle inflation and revolving debt traps.
* **Captured "Safe Unicorns"**: Isolated high-utilization borrowers who are 56% less likely to default than the cluster average, representing a **$0.5B opportunity** in untapped loan volume.
* **Explainable Intelligence**: Leveraged SHAP Global Importance to provide transparency to "Black Box" anomaly detection.

## 🛠️ Technical Architecture
Designed for massive scale (2.2M records), the pipeline ensures high performance without sacrificing signal integrity.

* **Feature Engineering**: 13-feature "Behavioral DNA" framework (Solvency, Commitment, Utilization, and Credit Velocity).
* **The Transformation Pipeline**:
    * **Stabilization**: Winsorization (99.5% cap) and Log Transformations to normalize high-skew financial data.
    * **Compression**: Principal Component Analysis (PCA) reduced 13 variables to 7, retaining 90% of total variance.
    * **Scalability**: Utilized **MiniBatchKMeans** for memory-efficient clustering of 2.2M records.



## 🔍 Key Findings & Archetypes
We established a robust Early Warning System by triangulating unsupervised clusters with actual financial outcomes.


<img width="700" height="360" alt="newplot-3" src="https://github.com/user-attachments/assets/99bfa0d9-66e6-490d-a666-a0510e8a7cfc" />


| Persona | Risk Profile | Key Characteristic |
| :--- | :--- | :--- |
| **Cluster 0: Prime Elites** | Ultra-Low | Highest income ($110k+), lowest interest rates (10.8%). |
| **Cluster 1: Stable Middle** | Low/Baseline | The "Average" P2P borrower; moderate income (~$67k). |
| **Cluster 2: High-Lev Starters** | Critical | Lowest income (~$44k) with massive DTI pressure. |
| **Cluster 3: Affluent Spenders** | Moderate/High | High income but trapped by $31k+ revolving debt. |
| **Cluster 4: Credit-Dependent** | Highest | Maxed-out utilization (61.5%) and high interest (15.3%). |

## 📉 Explainable AI (XAI)
To bridge the gap between "Black Box" algorithms and business trust, we integrated **SHAP (Shapley Additive exPlanations)**.

* **The Contextual Paradox**: "Being weird" is a positive signal in high-risk groups (Cluster 4), where anomalies are 56% less likely to default than their peers.
* **Red Flags**: In elite groups (Cluster 0), an anomaly increases default risk from 7.6% to 12.2%.
* **Drivers**: SHAP identified low revolving balances and exceptionally low DTI as the primary triggers for an "Anomaly" label.



## 🚀 Operational Roadmap
This analysis transitions from theoretical mapping to a live **RiskScanner** decision engine:

1.  **Unlocking Growth**: Targeted approval of anomalies in Cluster 4 to capture $0.5B in "safe" loan volume missed by traditional models.
2.  **Proactive Monitoring**: Automated tagging of Cluster 3 ("Affluent Spenders") for financial wellness interventions.
3.  **Model Evolution**: Quarterly retraining of centroids to adapt to shifting macroeconomic "Behavioral DNA."

---
*Developed by: Seiha Vat | March 2026*

*LinkedIn Profile* www.linkedin.com/in/seiha-vat-49014b242
