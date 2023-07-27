# SupervisedGRN

Abstract:

The construction of gene regulatory networks (GRNs) is vital for understanding the regulation of metabolic pathways, biological processes, and complex traits during plant growth and responses to environmental cues and stresses. The increasing availability of public databases has facilitated the development of numerous methods for inferring gene regulatory relationships between transcription factors and their targets. However, there is limited research on supervised learning techniques that utilize available regulatory relationships of plant species in public databases.
This study investigates the potential of machine learning (ML), deep learning (DL), and hybrid approaches for constructing GRNs in plant species, specifically Arabidopsis thaliana, poplar, and maize. Challenges arise due to limited training data for gene regulatory pairs, especially in less-studied species such as poplar and maize. Nonetheless, our results demonstrate that hybrid models integrating ML and artificial neural network (ANN) techniques significantly outperformed traditional methods in predicting gene regulatory relationships. The best-performing hybrid models achieved over 95% accuracy on holdout test datasets, surpassing traditional ML and ANN models and also showed good accuracy on lignin biosynthesis pathway analysis.
Employing transfer learning techniques, this study has also successfully transferred the known knowledge of gene regulation from one species to another, substantially improving performance and manifesting the viability of cross-species learning using deep learning-based approaches. This study contributes to the methodology for growing body of knowledge in GRN prediction and construction for plant species, highlighting the value of adopting hybrid models and transfer learning techniques. This study and the results will help to pave a way for future research on how to learn from known to unknown and will be conductive to the advance of modern genomics and bioinformatics.

Execution Instruction:

1. Move the training and testing data sets into same folder.
2. .
3. Run the Data_Transformation.py to clean and transform the data.
4. Next, check Finaldata folder which stores the transformed data for future computations.
5. Run the Training_models_and_exporting.py script to train and test on gene expression data.
6. Savedmodels/accuracy_table.csv shows the accuracy of the models.
7. Figures folder shows any training and validation accuracy curves if available.
8. Finaldata/Predictions folder holds the predictions of the data
