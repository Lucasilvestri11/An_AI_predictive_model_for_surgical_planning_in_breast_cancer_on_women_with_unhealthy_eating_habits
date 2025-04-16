# An_AI_predictive_model_for_surgical_planning_in_breast_cancer_on_women_with_unhealthy_eating_habits
It is known that the goal of medical research is to optimize diagnostic and therapeutic procedures, enabling professionals to provide increasingly personalized treatments. In the case of breast cancer, this objective translates into the improvement of decision-making processes that guide the choice of the most suitable surgical intervention (mastectomy or conservative) for the patient. Nevertheless, clinical information extracting is a challenging task due to the highly heterogeneous nature of data. In this context, the analysis of clinical data related to this neoplasm plays an increasingly significant role and predictive model based on Artificial Intelligence (AI) techniques, specifically Machine Learning methods (ML), can assist medical personnel in selecting the most suitable surgical treatment for breast cancer patients. In this study data from 5100 patients with breast carcer were enrolled, with ages ranging from 18 to 96 years, The results obtained proved significant for accurately classifying the surgical intervention as either conservative or mastectomy.

Daniela Evangelista*, Luca Silvestri, Monica Franzese, Mario Zanfardino, Massimiliano D’Aiuto, Vasuk Gautam

1.	Institute of Food Science, Italian National Research Council, via Roma 64, 83100, Avellino
2.	University of Rome Tor Vergata
3.	IRCCS SYNLAB SDN, Via E. Gianturco, 113, 80143 Naples, NA
4.	Breast Unit Aziendale, Presidio Ospedaliero di Boscotrecase, ASL Napoli 3 Sud, Italy
5.	Department of Computing Science, Department of Biological Sciences, University of Alberta, Edmonton, AB, Canada T6G 2E8

∗corresponding author

Keywords: Breast cancer, Mastectomy, Breast conserving surgery, Machine learning, Predictive model.

This project covers a complete data preparation, modeling, and evaluation pipeline using two main tools: Python (Jupyter Notebook) and WEKA(Waikato Environment for Knowledge Analysis).

The data preprocessing phase—including cleaning, transformation, and exploratory analysis—was carried out using Python within a Jupyter Notebook. This results in a cleaned dataset ready for model training.

The most significant features, selected from the preprocessed dataset, were used to train a machine learning model with the AdaBoost algorithm in WEKA. The trained model is provided as a .model file.

The performance metrics, including accuracy, confusion matrix, and other evaluation results, are saved in a text file.
