# SupervisedGRN

Abstract:

The construction of gene regulatory networks (GRNs) is vital for understanding the regulation of metabolic pathways, biological processes, and complex traits during plant growth and responses to environmental cues and stresses. The increasing availability of public databases has facilitated the development of numerous methods for inferring gene regulatory relationships between transcription factors and their targets. However, there is limited research on supervised learning techniques that utilize available regulatory relationships of plant species in public databases.
This study investigates the potential of machine learning (ML), deep learning (DL), and hybrid approaches for constructing GRNs in plant species, specifically Arabidopsis thaliana, poplar, and maize. Challenges arise due to limited training data for gene regulatory pairs, especially in less-studied species such as poplar and maize. Nonetheless, our results demonstrate that hybrid models integrating ML and artificial neural network (ANN) techniques significantly outperformed traditional methods in predicting gene regulatory relationships. The best-performing hybrid models achieved over 95% accuracy on holdout test datasets, surpassing traditional ML and ANN models and also showed good accuracy on lignin biosynthesis pathway analysis.
Employing transfer learning techniques, this study has also successfully transferred the known knowledge of gene regulation from one species to another, substantially improving performance and manifesting the viability of cross-species learning using deep learning-based approaches. This study contributes to the methodology for growing body of knowledge in GRN prediction and construction for plant species, highlighting the value of adopting hybrid models and transfer learning techniques. This study and the results will help to pave a way for future research on how to learn from known to unknown and will be conductive to the advance of modern genomics and bioinformatics.

# Install using pip
```
python3 -m pip install SupervisedGRN
```
Execution Instruction:

1. Move the training and testing data sets into same folder.
2. Import all the modules of SupervisedGRN using ```from SupervisedGRN import ml, cnn, ann, hybrid```
3. To run cnn models use ```cnn.train()``` and for inference ```cnn.infer()```
4. Similarly run other models using commands ```ml.train()```
