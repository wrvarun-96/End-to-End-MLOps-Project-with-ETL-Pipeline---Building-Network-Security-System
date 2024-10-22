# End-to-End MLOps Project with ETL Pipeline - Building Network Security System

This repository contains the complete code and implementation details for an end-to-end MLOps project, focused on building a network security system. The project encompasses all aspects of machine learning operations (MLOps), from setting up the environment to deploying the final model on AWS EC2. Below is an overview of the project's key components:

## Project Structure & Environment Setup

- Structured the project using best practices for scalable machine learning projects.
- Set up the environment using VS Code, ensuring a smooth development workflow.
- Configured dependencies and environment variables for seamless integration.

## ETL Pipeline Development

- **MongoDB Atlas Setup**: Connected to MongoDB Atlas for storing and managing data.
- **Data Ingestion**: Developed Python-based scripts for data ingestion, ensuring data is ingested securely and efficiently.
- **Data Validation & Transformation**: Implemented robust data validation techniques and built data transformation pipelines to ensure data quality.

## Model Training & Experiment Tracking

- **Model Training**: Built and trained models with a focus on hyperparameter tuning to enhance accuracy.
- **MLFlow Integration**: Used MLFlow for tracking model experiments, capturing performance metrics and parameters.
- **Remote Tracking with Dagshub**: Integrated Dagshub for storing MLFlow logs remotely, enabling easy collaboration and version control.

## Deployment & Automation

- **Project Packaging**: Packaged the project using `setup.py` for easy installation and deployment.
- **Docker & CI/CD**: Built Docker images for containerization and automated deployment workflows using GitHub Actions.
- **AWS Integration**: Automated the storage of model artifacts in AWS S3 and ECR. Deployed the final model to AWS EC2 for scalable, real-time network security analysis.

## Key Features

1. Comprehensive project structure setup and environment configuration.
2. End-to-end ETL pipeline development with Python and MongoDB Atlas.
3. Efficient model training with hyperparameter optimization.
4. Experiment tracking with MLFlow and remote logging with Dagshub.
5. Deployment with Docker, GitHub Actions, and AWS EC2 integration.

## Repository Structure

├── data/
│   ├── raw/
│   ├── processed/


├── src/
│   ├── data_ingestion.py
│   ├── data_validation.py
│   ├── model_training.py
│   ├── batch_prediction.py

├── logs/

├── models/

├── setup.py

├── Dockerfile

├── .github/
│   └── workflows/
│       └── ci-cd.yml
└── README.md


## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
2. Set Up the Environment: Follow the instructions in setup.py to install required dependencies.
3. Run the ETL Pipeline: Use the following command to start the data ingestion process:
    python src/data_ingestion.py
4. Train the Model: Run the following command for training with tuned hyperparameters:
   python src/model_training.py
5. Deploy the Model: Build and deploy Docker containers using docker-compose and GitHub Actions.




