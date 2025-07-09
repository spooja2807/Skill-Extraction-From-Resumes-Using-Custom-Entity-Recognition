This project demonstrates the development of a system that automatically extracts technical and soft skills from resumes using Amazon Comprehend’s Custom Entity Recognition (NER) feature. It aims to improve the efficiency and accuracy of resume parsing in recruitment processes by automating the extraction of relevant information.

### Key Features
- Trained a custom NER model to identify entities such as programming languages, tools, certifications, and soft skills  
- Utilized Amazon Comprehend and Amazon S3 for scalable and secure model training and data handling  
- Implemented IAM roles to manage access to S3 buckets and Comprehend services  
- Validated the model using test documents, with results stored and visualized from JSON outputs  

### Tools and Technologies
- Amazon Comprehend  
- Amazon S3  
- IAM (Identity and Access Management)  
- Python (for data preprocessing and file conversion)  
- Dataset: Resume Entities for NER (Kaggle)  

### Dataset Preparation
- Downloaded the JSON dataset from Kaggle  
- Converted resume content into plain text files  
- Created an entity list CSV for model training  
- Uploaded all training and testing data to an Amazon S3 bucket  
