#Stroke-Prediction-Project

This project aims to predict the likelihood of a patient experiencing a heart stroke based on comorbidities, work, and lifestyle factors. The project encompasses data ingestion, orchestration, cleaning, visualization, and machine learning, leveraging Microsoft Fabric's capabilities.

##Architecture Overview:

1-Data Engineering: Utilized Data Factory and Synapse Engineering to extract, transform, and load the dataset into a Fabric-enabled Lakehouse using Dataflow Gen2. The Lakehouse, based on the delta storage format, was used to store and query the data via SQL endpoints.
2-Data Science: A Support Vector Machine (SVM) model was developed using Spark notebooks connected to the Lakehouse. The model achieved 95% accuracy.
3-Data Analysis: SQL views were created for fact and dimension tables. Visualization and DAX measures were initially developed in Fabric's visualization tools and later refined in Power BI Desktop using SQL endpoint connections to avoid data duplication.

The Stroke Prediction project involved several key steps using Microsoft Fabric to predict heart stroke risk based on patient comorbidities, work, and lifestyle factors. The workflow included:

###Data Ingestion and Orchestration:

Extracted, transformed, and loaded the dataset into a Fabric-enabled Lakehouse using Dataflow Gen2 and Power Query Online.
Orchestrated data ingestion with Data Factory pipelines, preparing the dataset for further analysis.

![Screenshot (719)](https://github.com/user-attachments/assets/c97bc318-70a3-4fb2-9cba-04d7caf75161)

###Data Cleaning and Transformation:

Utilized SQL endpoints in the Lakehouse to clean and structure the data.
Created SQL views for fact and dimension tables to streamline data modeling.

![Screenshot (718)](https://github.com/user-attachments/assets/0f7b8cfc-d283-497a-8cf4-73b184cfbd23)

###Exploratory Data Analysis (EDA) and Visualization:

Developed a data model with DAX measures and initial visualizations within Fabric.
Refined visualizations in Power BI Desktop using SQL endpoint connections to avoid data duplication.

![Screenshot (717)](https://github.com/user-attachments/assets/96667b15-c736-4105-976a-e4a249a2e0d5)

![Screenshot (713)](https://github.com/user-attachments/assets/0702c4fd-255b-4a70-8685-b5b45066f223)

###Machine Learning Model:

Built a Support Vector Machine (SVM) model using Spark notebooks connected to the Lakehouse, achieving 95% accuracy.

![Screenshot (714)](https://github.com/user-attachments/assets/5af6bd24-78fa-4939-b91d-f94966077650)

![Screenshot (715)](https://github.com/user-attachments/assets/b6f0981f-b8ca-407f-bd2e-7ff47a644062)

![Screenshot (716)](https://github.com/user-attachments/assets/45252ad6-37ad-4f58-8029-a30d13fa7ab0)

