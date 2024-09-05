# 基于决策级模型融合的脑胶质瘤和淋巴瘤的术前鉴别模型
论文DOI: 10.1007/s00234-024-03451-7       

Objective: 研究基于MRI的深度学习网络和放射组学及其融合模型对于鉴别Primary central nervous system lymphoma (PCNSL)和Glioblastoma (GBM)的效果和应用价值。
Materials and Methods: 回顾性地收集了两个医学中心的261例患者的MRI影像和临床资料, 将患者分为训练集（n=153，医学中心1）和外部测试集（n=108，医学中心2）。由两名放射科医生分割整个肿瘤区域作为volume of interest (VOI), 然后基于最新的nnU-Net网络训练得到一个高效的3D脑肿瘤自动分割模型。使用Pyradiomics提取放射组学特征并建立Radiomics Model，采用基于transformer架构和Convolutional Neural Networks (CNN)架构的深度学习网络训练得到MobileVIT Model和ConvNeXt Model。根据“决策级融合”理论对放射组学模型和深度学习模型进行融合得到DL-Radiomics Model。此外，本研究创新性地使用Shapley Additive exPlanations(SHAP)和Grad-CAM两种方法对模型进行可解释性分析。
Results: 分割模型在外部测试集上的Dice Similarity Coefficient (DSC)为0.88。在肿瘤鉴别的外部测试任务上，Radiomics Model的Area under the receiver operating characteristic curve(AUC)为0.86(95% CI:0.77,0.92; P<0.001); ConvNeXt Model的 AUC为0.89 (95% CI:0.81,0.94; P<0.001); MobileVIT Model的 AUC为0.91 (95% CI:0.84,0.95; P<0.001)；DL-Radiomics Model的AUC为0.92(95% CI:0.85,0.97; P<0.001)。Delong检验表示DL-Radiomics Model与Radiomics Model的AUC有显著性差异(P=0.02).
Conclusion: 放射组学模型和深度学习模型对于术前无创鉴别PCNSL和GBM均具有较好的诊断价值。相对而言，MobileVIT Model展现出更好的效果。此外，DL-Radiomics Model展现出了最优的性能，这说明不同类型的模型可以有效互补以提高任务的决策水平。

Clinical Relevance Statement: PCNSL和GBM之间的无创鉴别有助于选择合适的治疗方案和临床管理策略。由于这两种肿瘤经常表现出不典型的影像学特征，仅根据MRI的影像学特征无法准确进行区分，研究更加准确便捷的术前无创鉴别方法具有重要的临床价值。

