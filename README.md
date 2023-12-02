# YOLOv5 Fire & Smoke Detection

## Introduction
This repository contains a YOLOv5-based algorithm designed for the detection of fire and smoke. The models are trained with a dataset comprising over 4000 images of fire and smoke under various conditions and from different locations.

## Models
There are three models included in the `\models` folder:
1. **Fire-only Detection Model**: Specifically trained to detect fire.
2. **Fire and Smoke Detection Model A**: Trained to detect both fire and smoke.
3. **Fire and Smoke Detection Model B**: Another variant for detecting both fire and smoke.

### Performance
- Fire-only Model: Accuracy - 91.1%
- Fire and Smoke Models: 
  - Model A: Accuracy for Fire - 91.1%, for Smoke - 75.1%
  - Model B: Similar performance with slight variations (details in model descriptions).

Each model has been trained for 300 epochs.

## Dataset
The dataset includes a diverse collection of fire and smoke images under different lighting conditions and from various locations. This diversity helps in enhancing the detection accuracy in real-world scenarios.

## Usage
### Running in Google Colab
The `train.ipynb` notebook is provided for easy running and testing of the models in Google Colab.

#### Steps:
1. Open `train.ipynb` in Google Colab.
2. Ensure that the path to the model directory is correctly set.
3. Follow the instructions in the notebook to load and test the models.

### Local Setup
To run the models locally, follow these steps:
1. Clone this repository.
2. Install the necessary dependencies (listed below).
3. Run the model using the provided scripts or the Jupyter notebook.

## Dependencies
- Python 3.x
- PyTorch
- Other dependencies are listed in the `requirements.txt` file.

## Contributing
Contributions to improve the model or extend its capabilities are welcome. Please follow the standard pull request process.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
Thanks to the contributors of the YOLOv5 project and the dataset providers.
