# 基于多模型融合的图像分类器---用于脑胶质瘤和淋巴瘤的术前鉴别

1. 模型目的：基于MRI图像数据，使用CNN、放射组学和transformer模型进行分类训练，基于不同的模型融合方法对最终的模型分类性能进行测试，最终提高术前区分PCNSL和GBM这两种恶性脑肿瘤的准确性。

2. 模型结果：在肿瘤鉴别的外部测试任务上，Radiomics Model 的 Area under the receiver operating characteristic curve(AUC)为0.86(95% CI:0.77,0.92; P<0.001); ConvNeXt Model 的 AUC 为 0.89 (95% CI:0.81,0.94; P<0.001);
MobileVIT Model 的 AUC 为 0.91 (95% CI:0.84,0.95; P<0.001)；DL-Radiomics Model 的 AUC 为0.92(95% CI:0.85,0.97; P<0.001)。Delong 检验表示 DL-Radiomics Model 与 Radiomics Model 的AUC 有显著性差异(P=0.02).
