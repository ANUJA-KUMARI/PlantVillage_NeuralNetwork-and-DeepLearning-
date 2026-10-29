# PlantVillage: Plant Disease Classification Using Deep Learning

## Project Overview

This project explores plant disease classification using deep learning techniques on the PlantVillage dataset. It includes data analysis, preprocessing, convolutional neural network (CNN) training, and ResNet18 transfer learning.

## Models

- **Custom CNN:** A convolutional neural network trained for plant disease classification.
- **ResNet18:** A pretrained ResNet18 model fine-tuned using transfer learning.

## Repository Structure

```text
PLANT_VILLAGE/
├── models/
│   ├── custom_cnn/
│   │   ├── best_model.pth
│   │   └── training_history.csv
│   └── resnet18/
│       ├── best_resnet18.pth
│       └── training_history.csv
├── notebook/
│   ├── _dataset_analysis.ipynb
│   ├── _eda.ipynb
│   ├── preprocessing.ipynb
│   ├── model_training.ipynb
│   └── _resnet18_transfer_learning.ipynb
├── report/
├── results/
├── model_comparison_UPDATED.csv
├── requirements.txt
└── README.md
```

## Dataset

The PlantVillage dataset is not included in this repository because of its size. Download the dataset separately and place it in the appropriate location expected by the notebooks. Update dataset paths in the notebooks as needed.

## Technologies Used

- Python
- PyTorch and Torchvision
- NumPy and Pandas
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Getting Started

1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install the dependencies listed in `requirements.txt`.
4. Download the PlantVillage dataset separately.
5. Update dataset paths in the notebooks.
6. Run the notebooks in the following order, adjusting as needed for the workflow:
   - Dataset analysis and EDA
   - Preprocessing
   - Model training
   - ResNet18 transfer learning

## Trained Models and Results

The repository includes saved model checkpoints, training histories, and result files for reviewing the experiments. Refer to the notebooks and project report for implementation details and evaluation results.

## Author

Anuja Kumari
