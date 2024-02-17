# AI-ML-Engineering-Portfolio
This repository showcases some of my work and projects in the fields of Artificial Intelligence and Machine Learning.

**Project Concept: Genomic Variant Classifier for Neurodegenerative Diseases (PD, AD, MS)**

Overview

The goal of this project was to develop a sophisticated AI-driven tool capable of classifying genetic variants as indicative of Parkinson’s Disease (PD), Alzheimer’s Disease (AD), or Multiple Sclerosis (MS). The emphasis was on leveraging advanced machine learning techniques to interpret complex genomic data, thereby aiding in the early detection and understanding of these neurodegenerative diseases. 

Why a Random Forest Classifier? 

The Random Forest algorithm was chosen due to its robustness and efficiency in handling large datasets with multiple features. This ensemble learning method is particularly adept at reducing overfitting, thereby ensuring more reliable predictions. Its ability to handle the intricacies of genomic data, such as allele changes and gene impacts, makes it an ideal choice for this kind of analysis. 

Dataset and Feature Selection:

The project involved creating a dataset of over 1,200 instances, each meticulously curated to ensure high-quality and relevant genetic information. Key features included: 

Allele Change: Critical in understanding genetic variations. 
Allele Frequency: Provides insights into the commonality of the variants. 
Conservation Score: Indicates the evolutionary preservation of genetic sequences, shedding light on their importance. 
Gene Affected: Essential for linking variants to specific diseases. 
Functional Impact: Helps determine the actual effect of the variant on the gene function. 
Performance Metrics: 

The classifier achieved an accuracy and F1 score of 80%, demonstrating its impressive effectiveness in genomic variant classification. These metrics were chosen as they provide a balanced view of the model’s performance, accounting for both precision and recall. This level of accuracy is particularly significant and difficult to accomplish in the context of genomic research, where the correct identification of disease-associated variants is highly complex and multifaceted. 

Visualizations: 

To illustrate the model’s decision-making process and performance, several visual aids are used: 

Application in R&D: 

This proprietary technology is currently being utilized in-house at SensusGen AI for advanced genomic research. Its application is crucial in exploring new correlations between genetic markers and neurodegenerative diseases, paving the way for potential therapeutic breakthroughs. 


Significance and Impact: 

This classifier’s ability to accurately predict disease associations based on genomic variants represents a significant advancement in the field of bioinformatics. It opens new avenues for personalized medicine, where treatments can be tailored based on an individual’s genetic makeup, and contributes to the broader understanding of neurodegenerative diseases. 

Future Directions: 

Going forward, the methodologies and learnings from this project can be applied to other complex genomic analysis tasks. There is potential to expand the model’s application to include other diseases and to integrate it with other forms of biomedical data for more comprehensive insights.  ![download (1)](https://github.com/andrewalbertand/AI-ML-Engineering-Portfolio/assets/71141011/451c4b91-d09b-4117-9288-ded591ad3714)

Figure 1. This bar chart displays the relative importance of each feature used in predicting the neurodegenerative diseases—Alzheimer’s disease (AD), Multiple Sclerosis (MS), and Parkinson’s disease (PD). The length of the bar represents the significance of the feature, with ‘Conservation Score (GERP)’ being the most influential, followed by ‘Allele Frequency (GNOMAD)’, ‘Gene Affected (NCBI)’, ‘Functional Impact (NCBI)’, and ‘Allele Change (NCBI)’. This means that even if you have to enter “unknown” a given category, the model can still use the other information provided to make its best prediction for disease association.

<img width="319" alt="ATL" src="https://github.com/andrewalbertand/AI-ML-Engineering-Portfolio/assets/71141011/5cc200d6-28f1-451a-8a12-3dd9a90acefe">

Figure 2. The classifier achieved an accuracy and F1 score of 80%, demonstrating its effectiveness in genomic variant classification. These metrics were chosen as they provide a balanced view of the model’s performance, accounting for both precision and recall. This level of accuracy is particularly significant in the context of genomic research, where the correct identification of disease-associated variants is crucial. 

<img width="582" alt="confusionmatrix" src="https://github.com/andrewalbertand/AI-ML-Engineering-Portfolio/assets/71141011/d3126f69-594f-48b1-b2d9-761b47dac473">

Figure 3. The confusion matrix illustrates the performance of the classifier. Each cell in the grid corresponds to the number of predictions made by the model, where the rows represent the actual diseases and the columns represent the predicted diseases. For example, the model correctly predicted 160 instances of PD (Parkinson’s disease), while it confused MS (Multiple Sclerosis) with AD (Alzheimer’s disease) in 27 cases. The darker the shade of blue, the higher the number of predictions, indicating a strong predictive accuracy in those areas. 

<img width="566" alt="class" src="https://github.com/andrewalbertand/AI-ML-Engineering-Portfolio/assets/71141011/58a0d87f-5d3b-4d32-95fc-74a8c8b171d3">

Figure 4. This bar chart illustrates the precision, recall, and F1 score for each class — AD, MS, and PD — showcasing the model’s well-rounded performance across different neurodegenerative diseases. PD shows particularly high precision, indicating a strong likelihood of correct predictions when a PD variant entry is submitted. It should be emphasized that the scores for AD and MS are also robust, reflecting the model’s competence in these more challenging classifications. The scores displayed highlight the model’s substantial utility for research in the complex field of genomic variant classification. Significantly surpassing the baseline of 0%, which is a common starting point in this cutting-edge field of genomic variant classification, the model’s achievements are a testament to its value and effectiveness.

![download](https://github.com/andrewalbertand/AI-ML-Engineering-Portfolio/assets/71141011/3c87d808-4dbd-466a-865f-83fbefba191f)

Figure 5. The feature correlation heatmap provides a visual representation of the relationships between key genomic variables: ‘Allele Change’, ‘Allele Frequency’, ‘Gene Affected’, ‘Functional Impact’, ‘Disease Association’, and ‘Conservation Score’. Dark red squares indicate a strong positive correlation, dark blue squares indicate a strong negative correlation, and lighter colors represent weaker correlations. This heatmap is essential for recognizing interdependencies in genomic data, which can inform feature selection and the development of predictive models in bioinformatics research. 
