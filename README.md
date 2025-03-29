# Dependency Sensitive CNN for Modeling Sentences and Documents

## Overview
This project implements a **Dependency Sensitive Convolutional Neural Network (DSCNN)**, which enhances traditional CNN architectures by incorporating long-term dependencies using **LSTMs** and **dependency structures** in text. The model is designed to improve performance in **text classification tasks** such as **sentiment analysis, question classification, and subjectivity classification**.

## Features
- Utilizes **LSTM** to capture long-term dependencies in text.
- Leverages **convolutional layers** to extract local features.
- Incorporates **dependency structures** to improve sentence modeling.
- Outperforms traditional CNN models in multiple NLP tasks.

## Technologies Used
- **Python**
- **TensorFlow/Keras**
- **NLP Techniques**
- **LSTM, CNN**
- **Dependency Parsing**

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/DependencySensitiveCNN.git
   cd DependencySensitiveCNN
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Prepare your dataset in a text format.
2. Train the DSCNN model:
   ```sh
   python train.py --dataset dataset_name --epochs 10 --batch_size 32
   ```
3. Evaluate the model:
   ```sh
   python evaluate.py --dataset dataset_name
   ```
4. Run inference:
   ```sh
   python predict.py --text "Sample input text here"
   ```

## Dataset
- The model is trained on text classification datasets such as **IMDb**, **SST-2**, and **20 Newsgroups**.
- Supports custom datasets with a pre-processing pipeline.

## Results
- Achieves superior accuracy compared to baseline CNN models.
- Integrates both syntactic and semantic features to improve classification performance.

## Future Work
- Implement attention mechanisms to further enhance dependency modeling.
- Extend support for multi-lingual datasets.
- Optimize computational efficiency for large-scale datasets.

## Contributing
Contributions are welcome! Feel free to submit pull requests or open issues for discussion.

## License
This project is licensed under the **MIT License**.

## Contact
For any questions, feel free to reach out or visit the project repository on GitHub.

---

Let me know if you need modifications or additional sections!

