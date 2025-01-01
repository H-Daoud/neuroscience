# _neuroscience_project
# Title: Abnormality detection and monitoring  in vascular networks using mobile nanosensors project:
Nanobot Localization Using Machine Learning Techniques Overview This repository contains the code, datasets, and documentation for the research project titled "Abnormality Detection and Monitoring in Vascular Networks Using Mobile Nanosensors". The project explores advanced machine learning techniques to improve the accuracy of nanobot localization within human vascular networks. The goal is to enhance precision in detecting abnormalities for targeted medical interventions.

**Key Features**
Machine Learning Models:
Random Forest: Achieved 60% accuracy for localization tasks and demonstrated superior performance compared to K-Means.
K-Means Clustering: Used as a baseline for evaluating unsupervised learning approaches.

**Data Framework:**
Utilized the Blood Voyager Simulator (BVS) dataset generated using the n3-simulator network system from prior research.
Features like concentration averages (conc-avg), crossing concentration (conc-cross), and delay were used for analysis.
Metrics: Accuracy, Precision, Recall, and F1-score were employed to evaluate the models.

**Research Contributions**
Introduced a novel framework combining supervised and unsupervised ML techniques for precise abnormality detection in biological environments. Validated the effectiveness of Random Forest for handling high-dimensional biological datasets, achieving higher reliability and accuracy over K-Means. Addressed challenges in handling imbalanced data and detecting anomalies in dynamic environments.

**System Architecture**
The system comprises: Mobile Nanosensors: Simulated sensors deployed within the vascular network.
Data Collection and Preprocessing: Cleaning and normalizing high-dimensional data for ML models.
Machine Learning Analysis: Integration of Random Forest and K-Means to evaluate abnormalities.
Result Validation: Rigorous testing using performance metrics.


# Repository Structure
Code kopieren
├── data/
│   ├── BVS_training_data.mat       # Preprocessed dataset from prior research
│   ├── class0.png                  # Visualization of normal cases
│   ├── class1.png                  # Visualization of abnormal cases
├── notebooks/
│   ├── ATU_Msc_Dissertation_v12.ipynb  # Jupyter notebook with analysis and results
├── diagrams/
│   ├── Arch-Diagramm.drawio.png    # Architecture diagram
├── results/
│   ├── evaluation_metrics.csv      # Performance metrics for models
├── src/
│   ├── preprocessing.py            # Scripts for data preprocessing //ATU_Msc_Dissertation_v12.ipynb//
│   ├── random_forest_model.py      # Random Forest implementation //ATU_Msc_Dissertation_v12.ipynb//
│   ├── kmeans_model.py             # K-Means implementation //ATU_Msc_Dissertation_v12.ipynb//
├── README.md                       # Project overview and instructions

# Usage
**1-Code copy:**
Clone the repository:
git clone https://github.com/your_username/nanobot-localization.git

**2- Install dependencies:**
pip install -r requirements.txt

**3- Run the Jupyter notebook:**
jupyter notebook notebooks/ATU_Msc_Dissertation_v12.ipynb


# Key Results
Random Forest:
Class 0 (Normal): F1-Score 0.67
Class 1 (Abnormal): F1-Score 0.51
K-Means:
Class 0 (Normal): F1-Score 0.59
Class 1 (Abnormal): F1-Score 0.11

# Future Work
Expand the dataset to include diverse physiological conditions.
Explore hybrid approaches combining clustering and supervised techniques.
Optimize computational efficiency for real-time applications.

# Acknowledgements
This research is based on prior datasets and frameworks provided by [Jorge Torres Gómez et al.] and the Blood Voyager Simulator. Special thanks to the Atlantic Technological University for their guidance and resources.

# Citation
If you use this code or dataset in your research, please cite:
Daoud, H. (2025). "Abnormality Detection and Monitoring in Vascular Networks Using Mobile Nanosensors." Atlantic Technological University.

