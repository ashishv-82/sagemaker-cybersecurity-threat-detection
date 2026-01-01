# Cybersecurity Threat Detection with XGBoost

This notebook demonstrates a complete ML pipeline for detecting cybersecurity threats using the UNSW-NB15 dataset and XGBoost classifier on AWS SageMaker.

## Pipeline Overview:
1. **Data Loading**: Download raw dataset from S3
2. **Data Preprocessing**: Feature engineering, encoding, and scaling
3. **Data Preparation**: Train-test split and SageMaker format conversion
4. **Model Training**: XGBoost training on SageMaker
5. **Local Validation**: Train and evaluate model locally
6. **Deployment**: Register model and deploy to SageMaker endpoint
7. **Inference**: Test the deployed endpoint with sample data
