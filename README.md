论文标题：Multicenter investigation of preoperative distinction between primary central nervous system lymphomas and glioblastomas through interpretable artificial intelligence models
论文DOI: 10.1007/s00234-024-03451-7      
 
Abstract
Objective: Research into the effectiveness and applicability of deep learning, radiomics, and their integrated models based on Magnetic Resonance Imaging (MRI) for preoperative differentiation between Primary Central Nervous System Lymphoma (PCNSL) and Glioblastoma (GBM), along with an exploration of the interpretability of these models.

Materials and methods: A retrospective analysis was performed on MRI images and clinical data from 261 patients across two medical centers. The data were split into a training set (n = 153, medical center 1) and an external test set (n = 108, medical center 2). Radiomic features were extracted using Pyradiomics to build the Radiomics Model. Deep learning networks, including the transformer-based MobileVIT Model and Convolutional Neural Networks (CNN) based ConvNeXt Model, were trained separately. By applying the "late fusion" theory, the radiomics model and deep learning model were fused to produce the optimal Max-Fusion Model. Additionally, Shapley Additive exPlanations (SHAP) and Grad-CAM were employed for interpretability analysis.

Results: In the external test set, the Radiomics Model achieved an Area under the receiver operating characteristic curve (AUC) of 0.86, the MobileVIT Model had an AUC of 0.91, the ConvNeXt Model demonstrated an AUC of 0.89, and the Max-Fusion Model showed an AUC of 0.92. The Delong test revealed a significant difference in AUC between the Max-Fusion Model and the Radiomics Model (P = 0.02).

Conclusion: The Max-Fusion Model, combining different models, presents superior performance in distinguishing PCNSL and GBM, highlighting the effectiveness of model fusion for enhanced decision-making in medical applications.

Clinical relevance statement: The preoperative non-invasive differentiation between PCNSL and GBM assists clinicians in selecting appropriate treatment regimens and clinical management strategies. 

Keywords: Deep learning; Glioblastoma; Interpretable model; Primary central nervous system lymphoma; Radiomics.
