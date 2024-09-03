<!--StartFragment-->

Unsupervised Learning in Cancer:

Authors(@slack):Nourhan Mahmoud (@NourhanM1)

Unsupervised learning is a machine learning technique that uses unlabeled data to identify patterns and structures. It is particularly useful in cancer research for identifying cancer subtypes, which are distinct molecular characteristics of related diseases. This helps in personalized medicine, as each subtype has different prognoses and treatment responses. In breast cancer research, unsupervised learning classifies tumors into molecular subtypes, such as Luminal A, Luminal B, HER2-enriched, and Basal-like. It also helps in identifying biomarkers, which can distinguish cancerous from non-cancerous tissues and predict patient outcomes. This helps in early detection and prognosis, enhancing cancer understanding and patient care.

Breast cancer subtype classification is crucial for personalized treatment due to the heterogeneity of tumors. Immunohistochemistry (IHC) has been used for surrogating gene expression profiling, but early identification is limited by false negatives and invasiveness. Rapid advances in radio genomics have led to the increased use of imaging in genotype research, including magnetic resonance imaging (MRI) as potential biomarkers for genotypic association studies and prediction models for neoadjuvant chemotherapy. Deep learning algorithms are being developed to provide second opinions for precision medicine, but their performance is often dependent on training datasets. Transfer learning, which allows for the acquisition of prior knowledge or features from specific source domains, is being explored for its potential in breast cancer subtype classification from dynamic contrast-enhanced MRI. 

This study proposes two unsupervised deep representation learning strategies, M\_EL and B\_EL, for identifying breast cancer luminal and non-luminal subtypes using malignant and benign breast lesion datasets. The goal is to preserve as many reconstruction features as possible using encoders, but maximizing the benefit value of redundant reconstruction features can be challenging. The proposed model can retain important information during unsupervised pre-training by maximizing the mean square error (MI) and constraining it from a prior distribution instead of mean square error or cross entropy. The experimental results show that M\_EL and B\_EL are superior to CLSTM when training data from scratch and take full advantage of dynamic information across DCE-MRI post-contrast images. The cross-domain capability between similar domains also represents the generalization capability of the model. The study emphasizes the importance of rational model design and similarity shared by source and target domains when improving transfer learning performance. Future research can achieve the same model generalization ability and considerable effect of transfer learning as a small-scale malignant source domain.

**Conclusion**

Unsupervised learning is a machine learning method that is applied in cancer research to determine subtypes of cancer, which are different molecular traits shared by cancers that are related. Personalized medicine requires this because the prognoses and treatment responses of each subtype vary. Unsupervised learning is used in breast cancer research to uncover biomarkers for early diagnosis and prognosis and to classify tumors into molecular subtypes such as Luminal A, Luminal B, HER2-enriched, and Basal-like. The use of imaging, such as magnetic resonance imaging (MRI), as possible biomarkers has been made possible by developments in radiogenomics. This work uses datasets of malignant and benign breast lesions to propose two unsupervised deep representation learning algorithms, M\_EL and B\_EL, for the identification of luminal and non-luminal subtypes of breast cancer.

**References**

[Ro Xiao D, Qin C, Yu H, Huang Y, Liu C. Unsupervised deep representation learning for motor fault diagnosis by mutual information maximization. _J Intell Manuf_ 2021; **32**(2): 377-391.ng Sun PhD](https://onlinelibrary.wiley.com/authored-by/Sun/Rong)

Hjelm RD, Fedorov A, Lavoie-Marchildon S, et al. Learning deep representations by mutual information estimation and maximization. 2018; arXiv preprint arXiv:1808.06670

 ****

[**https://doi.org/10.1002/jmri.27955**](https://doi.org/10.1002/jmri.27955)

\


<!--EndFragment-->
