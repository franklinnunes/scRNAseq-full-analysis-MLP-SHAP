# Full scRNA-seq Breast Cancer Analysis with Scanpy + Machine learning approach (Cell type classification and model interpretability)
## This project involved a comprehensive single-cell RNA sequencing (scRNA-seq) analysis of breast cancer data, utilizing a variety of tools for each stage. The analysis pipeline included quality control (QC), highly variable gene (HVG) feature selection, cell annotation, multilayer perceptron (MLP) classification, and model interpretability using SHAP.

### Tools and Methods Used:
* Scanpy: Read h5 matrix, quality control, feature selection, and data visualization for the scRNA-seq data.
* SCSA (Single-Cell RNA-Seq Annotation): Cell type annotation.
* PyTorch Lightning: For the development of the classification model, PyTorch Lightning was employed, providing a high-level interface for streamlined deep learning research.
* Hyperopt: Bayesian optimization via the Hyperopt library was used to optimize the hyperparameters of the MLP model.
* Scikit-learn: Was utilized for SK-fold cross-validation to ensure robust model evaluation and to generate various performance metrics of the classification model.
* SHAP (SHapley Additive exPlanations): To interpret the model's predictions and understand the contribution of individual features, SHAP was used to explain the output of the first fold of the classification model.
