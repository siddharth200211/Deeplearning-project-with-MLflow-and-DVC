# Chest Cancer Classification with MLOps

This project is an end-to-end deep learning implementation for chest cancer classification using the VGG16 model, integrated with MLOps practices. It utilizes MLflow for experiment tracking and DVC for data version control to ensure reproducibility, consistency, and streamlined workflow management.

## Project Overview

The primary goal of this project is to classify chest cancer images as either *normal* or *adenocarcinoma cancer*. This project employs VGG16 for image classification and follows a structured MLOps pipeline, making use of tools like MLflow and DVC.

### Features
- Data Version Control with DVC: Manages data and model versions to ensure reproducibility.
- Experiment Tracking with MLflow: Logs metrics, hyperparameters, and artifacts for each experiment, allowing easy comparison.
- Automated Pipeline: CI/CD-ready pipeline for scalable model training, testing, and deployment.



## Getting Started

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Initialize DVC and pull data:**
   ```bash
   dvc init
   dvc pull
   ```

4. **Run the main script to train the model:**
   ```bash
   python main.py
   ```

## MLOps Tools

- DVC: Manages data and models, providing version control.
- MLflow: Tracks experiments, including metrics, parameters, and model artifacts.

## Model

- Architecture: VGG16
- Task: Classify chest cancer images as either *normal* or *adenocarcinoma*.

## Future Enhancements

- Deploymen*: While deployment on AWS was initially planned, it remains a potential future enhancement.

## License

This project is licensed under the terms of the [MIT License](LICENSE).
