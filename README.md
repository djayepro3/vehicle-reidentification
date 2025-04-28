# Vehicle Re-Identification for Urban Mobility

![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

The main idea is to re-identify vehicles at different checkpoints or camera points to monitor the flow of traffic.

Developed an image retrieval system using the VeRi dataset to re-identify vehicles to enhance urban mobility:
- Trained an embedding network with a pre-trained CNN and implemented triplet loss and mining strategy.
- Ranked test images by Euclidean distance in feature space and evaluated performance with mAP

## Usage

To run the model, follow these steps:

1. Clone the repository:
    ```bash
    git clone [https://github.com/djayepro3/vehicle-reidentification]
    ```
2. Navigate to the project directory:
    ```bash
    cd vehicle-reidentification
    ```
