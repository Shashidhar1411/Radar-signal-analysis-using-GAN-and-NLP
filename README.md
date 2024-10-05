# Radar Data Synthesis

This repository contains code and resources for the Radar Data Synthesis project, which utilizes Generative Adversarial Networks (GANs) for synthesizing radar data. The project includes training data, results, and related resources.

## Project Structure

- **report Images/**: This folder contains images showing the accuracy of the model with each parameter.
- **radar.csv**: The CSV file used for training the GAN model.
- **synthetic.csv**: The CSV file showing the results of the synthesized radar data.
- **GAN_paper.pdf**: The seminal GAN paper by Ian Goodfellow.

## Getting Started

### Prerequisites

To run this project, you will need:

- Python 3.x
- Libraries: TensorFlow or PyTorch, Pandas, NumPy, Matplotlib

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/radar-data-synthesis.git
   cd radar-data-synthesis
   ```

2. Install the required libraries:
   ```sh
   pip install -r requirements.txt
   ```

### Usage

1. **Training the Model**:
   - Place `radar.csv` in the root directory.
   - Run the .ipynb file.
   - The results will be saved in `synthetic.csv`.

### Results and Evaluation

- Accuracy images for each parameter are located in the `report_images/` folder.
- Compare the synthetic data (`synthetic.csv`) with the original training data (`radar.csv`) to evaluate the model's performance.

## References

- [Generative Adversarial Networks (GANs) by Ian Goodfellow](GAN_paper.pdf)

## Acknowledgments

- Ian Goodfellow for the foundational GAN paper.
