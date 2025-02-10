# Pali-to-English Translation using Transformers

## Overview
This project focuses on translating Pali text into English using Transformer-based deep learning models. The dataset is processed, trained, and evaluated to improve translation accuracy.

## Features
- Implementation of Transformer-based models
- Preprocessing of Pali text
- Training and evaluation on custom datasets
- Model performance visualization

## Installation & Setup
To set up the environment, install the required dependencies:

```bash
pip install torch transformers pandas numpy matplotlib
```

## Dataset
- The dataset used for training is a collection of Pali-English translations.
- It is available in the `output_file.csv` file.
- Large files like `.pkl` datasets may need to be downloaded separately from [Google Drive / Cloud Storage Link].

## Usage
### Running the Model
Execute the Jupyter Notebook to train and test the model:
```bash
jupyter notebook
```
Open `Final_Transformer.ipynb` and run all cells.

Alternatively, run the script (if applicable):
```bash
python train_model.py
```

## File Structure
```
Project/
│── notebooks/            # Jupyter notebooks with model training
│── data/                 # Dataset files (not uploaded if too large)
│── models/               # Trained model checkpoints
│── scripts/              # Python scripts for training and evaluation
│── README.md             # Project documentation
│── requirements.txt      # Dependencies list
```

## Model Details
The project leverages Transformer models, inspired by state-of-the-art architectures in NLP.
- Model Architecture: Transformer-based Sequence-to-Sequence
- Training: Supervised learning on parallel corpus
- Evaluation Metrics: BLEU Score, Perplexity

## Contributions
Feel free to contribute by creating issues or pull requests!

## Future Work
- Improve the model with larger datasets
- Fine-tune on domain-specific Pali-English texts
- Deploy as an API for real-time translation

## License
This project is licensed under the MIT License.

## Contact
For any questions, reach out via email or create an issue in this repository.

