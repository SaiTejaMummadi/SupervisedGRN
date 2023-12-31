# SupervisedGRN

Abstract:

The construction of gene regulatory networks (GRNs) is vital for understanding the regulation of metabolic pathways, biological processes, and complex traits during plant growth and responses to environmental cues and stresses. The increasing availability of public databases has facilitated the development of numerous methods for inferring gene regulatory relationships between transcription factors and their targets. However, there is limited research on supervised learning techniques that utilize available regulatory relationships of plant species in public databases.
This study investigates the potential of machine learning (ML), deep learning (DL), and hybrid approaches for constructing GRNs in plant species, specifically Arabidopsis thaliana, poplar, and maize. Challenges arise due to limited training data for gene regulatory pairs, especially in less-studied species such as poplar and maize. Nonetheless, our results demonstrate that hybrid models integrating ML and artificial neural network (ANN) techniques significantly outperformed traditional methods in predicting gene regulatory relationships. The best-performing hybrid models achieved over 95% accuracy on holdout test datasets, surpassing traditional ML and ANN models and also showed good accuracy on lignin biosynthesis pathway analysis.
Employing transfer learning techniques, this study has also successfully transferred the known knowledge of gene regulation from one species to another, substantially improving performance and manifesting the viability of cross-species learning using deep learning-based approaches. This study contributes to the methodology for growing body of knowledge in GRN prediction and construction for plant species, highlighting the value of adopting hybrid models and transfer learning techniques. This study and the results will help to pave a way for future research on how to learn from known to unknown and will be conductive to the advance of modern genomics and bioinformatics.

# Link
https://pypi.org/project/SupervisedGRN/

# Install using pip
```
pip install SupervisedGRN
```
# SupervisedGRN: Predictive Models for Gene Regulatory Networks

SupervisedGRN is a Python package that leverages supervised machine learning and deep learning techniques to construct robust predictive models from transcriptomic data. It is designed to train on this high-dimensional data, extract key features, and make accurate predictions. The models generated can be used to uncover complex biological relationships and predict outcomes such as gene regulatory network behaviors, offering valuable insights for genomics and bioinformatics research.

## Execution Instructions

```bash
# 1. Ensure your training and testing datasets are in the same directory.

# 2. Import all the necessary modules from the SupervisedGRN package.
from SupervisedGRN import data, ml, cnn, ann, hybrid

# 3. Process your data using the data module's process function.
data.process()

# 4. Train your models. For example, to train the cnn model, use:
cnn.train()
# You can train the other models (ann, ml, hybrid) in the same manner.
ann.train()
ml.train()
hybrid.train()

# 5. Once your models are trained, you can use them to make predictions on new data. To infer using the cnn model, use:
cnn.infer()
# Similarly, you can make inferences using the other models:
ann.infer()
ml.infer()
hybrid.infer()
# 6. The predictions made by the models are saved in the "Finaldata/Predictions" folder.
```
