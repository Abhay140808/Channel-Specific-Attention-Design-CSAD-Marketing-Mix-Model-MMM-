# Channel-Specific-Attention-Design-CSAD-Marketing-Mix-Model-MMM-
CSAD is an experimental deep learning framework for marketing mix modeling that captures channel-wise impact, temporal patterns, and uncertainty to improve sales attribution and decision-making by providing interpretable, data-driven predicitions.


## Project Goal
The project aims to build an interpretable, uncertainty-aware, and causally robust model that:
- Learns temporal patterns in media spend.
- Estimates uncertainty in predictions using **Monte Carlo Dropout**.
- Captures contextual differences across **brands** and **regions**.
- Enables potential **counterfactual analysis** for strategic marketing insights.

## Features
- 🧩 Channel-wise temporal encoding  
- ⚙️ Learnable soft causal graph  
- 🔁 Context gating for brand & region adaptation  
- 🎯 Uncertainty estimation (MC Dropout)  
- 📊 Interpretable visualization of predicted vs actual sales  

## Training & Evaluation
- Trained using real multi-region weekly marketing data.
- Optimized with early stopping and RMSE-based checkpointing.
- Visualized results include uncertainty bands and validation performance metrics.

## Repository Structure
- Data/ Input dataset used for training the model
- CSAD Prototype 1/ The first prototype of the model that includes all the features
- README.md/ Project Documentation file
