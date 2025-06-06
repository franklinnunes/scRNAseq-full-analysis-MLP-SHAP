# Full scRNA-seq Breast Cancer Analysis with Scanpy + Machine learning approach (Cell type classification and model interpretability)
## Personal project of data analysis of single-cell RNA sequencing (scRNA-seq) breast cancer data from 10X Genomics. The analysis pipeline included quality control (QC), highly variable gene (HVG) feature selection, cell annotation, multilayer perceptron (MLP) classification, and model interpretability using SHAP.

### Tools and Methods Used:
* Scanpy: Read h5 matrix, quality control, feature selection, and data visualization for the scRNA-seq data.
* SCSA (Single-Cell RNA-Seq Annotation): Automated cell type annotation.
* PyTorch Lightning: Development of the multilayer perceptron classifier model.
* Hyperopt: Bayesian optimization to optimize the hyperparameters of the MLP model.
* Scikit-learn: Was utilized for SK-fold cross-validation to ensure robust model evaluation and to generate various performance metrics of the classification model.
* SHAP (SHapley Additive exPlanations): To interpret the model's predictions and understand the contribution of individual features, SHAP was used to explain the output of the first fold of the classification model.
