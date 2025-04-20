# Predictive Maintenance and Failure Detection in Manufacturing 
 
**BANA 7075 – Machine Learning Systems Design**  
_Group 2: Mike Carovillano, Aanika Garre, Sydney Ginter, Matthew Kraus, Joseph Rainford_

---

<div align="center">
  <img src="https://github.com/user-attachments/assets/7f27de6f-2089-4a9c-9c3e-e1b35a002a88" alt="Image" />
</div> 

<br>

This project implements a **predictive maintenance machine learning system** using **KNIME** to reduce unplanned equipment downtime in manufacturing environments. By leveraging sensor and operational data, the system predicts potential machine failures before they occur, helping shift maintenance strategies from reactive to proactive.

## Objective

- Predict failures of industrial equipment using real-time sensor and historical maintenance data.
- Help maintenance teams schedule repairs more efficiently.
- Reduce unplanned downtime, maintenance costs, and production losses.

##  Machine Learning Approach

We use supervised classification techniques, with a focus on:

- **Random Forests** for robustness and interpretability.
- **Gradient Boosted Trees** for high predictive performance.
- **Logistic Regression** for a baseline comparison.

<div align="center">
  <img width="922" alt="Image" src="https://github.com/user-attachments/assets/e0cfb663-2332-476c-aca6-cc987ebb02b9" />
</div>

##  Tools & Technologies

- **KNIME Analytics Platform**
  - Used to create the end-to-end workflow (shown above) for:
    - Data ingestion & validation  
    - Feature engineering (Min-max scaling, dummy encoding categorical variables, etc.)
    - Model training & evaluation
    - Visualization & alerting
- **AI4I 2020 Predictive Maintenance Dataset**
- Additional datasets:
  - Industrial Equipment Monitoring
  - Machine Failure Prediction using Sensor Data
- **DataOps**: Automated pipelines, validation checks, and data versioning
- **ModelOps**: Hyperparameter tracking and ease of monitorability of key metrics (precision/recall, Cohen's kappa, etc.)

---
