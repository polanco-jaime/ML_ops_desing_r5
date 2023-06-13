# Implementing Machine Learning in a Production Environment with Google Cloud Platform (GCP)

This repository contains the implementation of a machine learning (ML) pipeline in a production environment using Google Cloud Platform (GCP). The pipeline leverages GCP's services and tools to automate retraining and deployment of new ML models.

To explore the case of study of the ML Ops Designing  of a company that deploy more than 20 models and has more than 100.000 users monthly, please refer [Jupyter Notebook](notebooks/MLOps_Continuous_delivery_and_automation_pipelines_in_machine_learning.ipynb)to the in the `notebooks` directory

To explore the implementation details and code, refer to the [Jupyter Notebook](notebooks/Vertex_AI_custom_train_pipeline.ipynb) in the `notebooks` directory. The notebook provides step-by-step instructions and code examples for setting up the ML pipeline on GCP.

## Continuous Integration and Continuous Deployment (CI/CD) with GCP

To streamline the development and deployment process, we have established a CI/CD system using GCP services such as Cloud Build, Cloud Source Repositories, and Cloud Functions. These services enable automated testing, version control, and seamless integration of new pipeline implementations. By automating the testing and deployment stages with GCP, we ensure the reliability and efficiency of our ML system.

## Gradual Implementation on GCP

The implementation of the automated ML pipeline on GCP has been done gradually, following an iterative approach. We started by selecting specific components or stages of the pipeline to automate using GCP services like Cloud AI Platform, Cloud Storage, and BigQuery. As we gained confidence and experience, we expanded the automation coverage to encompass the entire ML system.

## Benefits of an Automated ML Pipeline on GCP

By leveraging GCP's capabilities for ML operations (MLOps), our automated ML pipeline offers numerous benefits:

1. **Efficiency:** GCP's services automate repetitive tasks, saving time and resources in retraining and deployment processes.

2. **Adaptability:** With GCP, we can easily integrate data pipelines and implement feature engineering to handle changes in data and the business environment, ensuring our models remain accurate and up-to-date.

3. **Consistency:** Automation eliminates manual errors and ensures consistent deployment and execution of ML models using GCP's standardized tools and frameworks.

4. **Scalability:** GCP provides scalable infrastructure to handle increasing data volumes and model complexity, allowing for seamless scaling of our ML system.

5. **Collaboration:** GCP's collaboration features enable team members to work together effectively, utilizing version control, shared repositories, and collaborative development environments.

By implementing an ML pipeline with CI/CD practices on GCP, we have enhanced the efficiency, reliability, and adaptability of our ML system in a production environment.

> Source: 
>- [Google Cloud Architecture for MLOps](https://cloud.google.com/architecture/architecture-for-mlops-using-tfx-kubeflow-pipelines-and-cloud-build?hl=es-419)
>- [Guidelines for Developing High-Quality ML Solutions](https://cloud.google.com/architecture/guidelines-for-developing-high-quality-ml-solutions)
>- [MLOps Continuous Delivery and Automation Pipelines in Machine Learning](https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning)
>- [ML Ops Best Practices on Google Cloud (Cloud Next '19)](https://www.youtube.com/watch?v=20h_RTHEtZI&ab_channel=GoogleWorkspace)

