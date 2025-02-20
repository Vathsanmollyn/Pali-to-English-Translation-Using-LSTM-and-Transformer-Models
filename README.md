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

## File Structure
```
Project/
│── notebooks/            # Jupyter notebooks with model training
│── data/                 # Dataset files (not uploaded if too large)
│── README.md             # Project documentation
```

## Model Details
The project leverages Transformer models, inspired by state-of-the-art architectures in NLP.
- Model Architecture: Transformer-based Sequence-to-Sequence
- Training: Supervised learning on parallel corpus
- Evaluation Metrics: BLEU Score, Perplexity

## Contributions

### Code Contributions
- Improved model performance with hyperparameter tuning and architectural changes.
- Enhanced preprocessing techniques for better text cleaning and normalization.

### Performance & Evaluation
- Benchmarked model performance against other translation approaches.
- Fine-tuned the model for higher accuracy.

## Future Work
- Improve the model with larger datasets
- Fine-tune on domain-specific Pali-English texts
- Deploy as an API for real-time translation

## License
This project is licensed under the MIT License.

