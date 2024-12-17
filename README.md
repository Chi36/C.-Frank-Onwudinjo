# Prediction of Catalysis Performance during Dry reforming of Methane

**Problem Statement**: 
### Problem Statement: Prediction of Catalysis Performance during Dry Reforming of Methane

The Dry Reforming of Methane (DRM) is a process for converting methane (CH₄) and carbon dioxide (CO₂) into syngas, a mixture of hydrogen (H₂) and carbon monoxide (CO). In the manufacturing industry, this method is used for the production of fuels and chemicals mitigating the impact of greenhouse gases through reduction and utilization. Nonetheless, the sustainability of DRM  depends on the catalyst performance which affected by factors like deactivation resulting from coking, particle sintering, and catalyst poisoning. Catalyst performance is affected by operating conditions such as temperature, pressure, feed gas composition, GSHV and many other catalyst properties. To improve the efficiency and sustainability of the DRM process, consistent metrics concerns have to be addressed (e.g. scalability) required for catalysis performance prediction regardless of reaction condition.

The goal of this project is to  develop a predictive model that forecasts the catalytic performance during the Dry Reforming of Methane process. Leveraging machine learning techniques, key performance indicators (KPIs) such as reaction rate, catalyst, coke formation, and syngas yield, based on a set of input parameters, including catalyst type, reaction conditions, and feed composition. By addressing these challenges, this project will contribute to optimizing the DRM process, reducing catalyst deactivation rates, improving syngas production efficiency, and ultimately supporting sustainable industrial practices in methane utilization and carbon dioxide mitigation.

**Input and Output Variables**: 
The features (inputs) of the dataset include Reaction Temperature, Ratio of CH₄ in Feed, Ni Loading, Surface Area, GHSV, Reaction Time, Pore Size, Pore Volume, H2-TPR Peak Temperature , Ni Particle Size, Ni Dispersion, Modifier Electronegativity. The targets (output) are  Syngas Ratio, CO₂ Conversion, or CH₄ Conversion

**Machine Learning Algorithm(s)**: 
Regression models such as Support Vector Regression (SVR), Random Forest, Linear Regression and KNN were applied. The classification models used are RandomForestClassifier, Logistic Regression, SVC and KNN Classifier.

**Ethics Considerations**: https://github.com/Chi36/C.-Frank-Onwudinjo/blob/main/C_Frank_Onwudinjo__Catalysis_Performance_Prediction_Ethics_DataCard_and_Deon_Checklist.ipynb

**Graphical User Interface (GUI)**: https://huggingface.co/spaces/Frankie89/Catalysis_Performance_1

**Dataset**: Datasets were provided by the course instructor. Data preprocessing done include checking for missing values, summary statistics and correlation matrix obtained using heatmaps. 

**Project Details**: 
This predicts forest fires in a given region based on the available datasets.Load datasets, separate numerical and categorical variables. Next, handle missing values and perform One-Hot Encoding for categorical variables. Drop original columns and concatenate encoded ones. Now, split datasets into inputs (x) and targets (y). Perform one-Hot encoding on the output variables if categorical (ensure that features are numeric). Define the models used, train and select the best model. Define Gradio app and interface. Finally push to Hugging Face and move to GitHub. 


**The names of the author and the instructor**:                  Chimezie Frank Onwudinjo,  Dr. Jude A. Okolie                                                                                                                     
**Your department and university information**:                  Chemical Engineering Departmnent, Bucknell University

**Course Code**:                                                        CHEG 672 (Data Science in Chemical Engineering)

This app predicts catalysis performance during methane dry reforming. Here is the link to the user interface 
https://huggingface.co/spaces/Frankie89/Catalysis_Performance_1
