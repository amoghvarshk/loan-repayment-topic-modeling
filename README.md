# loan-repayment-topic-modeling
Used BERTopic to extract latent themes from 126K LendingClub loan descriptions and predict loan repayment using logistic regression.
# Loan Repayment Prediction with Topic Modeling

This project applies BERTopic to 126,053 LendingClub loan descriptions to extract latent topics and enhance loan repayment prediction models.

## 📌 Project Highlights
- Generated 649 topics from loan descriptions using BERTopic; 52% of documents were assigned to a confident topic.
- Combined topic labels with structured loan data to predict loan repayment using logistic regression.
- Achieved an AUC improvement from 0.698 (baseline) to 0.717 by including topic features.
- Reclassified 3,281 “major_purchase” loans into interpretable subcategories to enhance risk segmentation.

## 🛠 Technologies Used
- Python
- BERTopic
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook
