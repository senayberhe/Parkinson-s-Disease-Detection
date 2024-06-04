# Parkinson's Disease Detection

## Overview
This project aims to develop a machine learning model using the `RandomForestClassifier` from the `sklearn` module in Python to detect Parkinson's Disease (PD). Our model achieves an accuracy of 97.43%, which is noteworthy given the limited dataset size.

## Table of Contents
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Description
### What is Parkinson’s Disease?
Parkinson’s Disease is a central nervous system disorder characterized by low dopamine levels in the brain, leading to symptoms such as tremors, rigidity, slow movement, and balance problems. Currently, there is no cure, and treatment focuses on alleviating symptoms.

### Detecting Parkinson’s Disease
In this project, we use the `RandomForestClassifier` to predict if an individual has Parkinson’s Disease based on biomedical voice measurements. The dataset consists of features extracted from voice recordings of individuals with and without Parkinson's Disease.

### How Random Forest Works
A Random Forest classifier uses multiple decision trees to make predictions based on majority voting. For example, if three trees predict "The Shawshank Redemption" as a favorite movie and one predicts "Forrest Gump," the final prediction is "The Shawshank Redemption" due to majority voting.

## Dataset
The dataset is sourced from the UCI Machine Learning Repository and contains biomedical voice measurements from 31 people, 23 with Parkinson's Disease.

- [Dataset Source](https://archive.ics.uci.edu/ml/datasets/parkinsons)

## Installation
To run this project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Parkinsons-Disease-Detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Parkinsons-Disease-Detection
    ```
3. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Place your dataset in the `data` directory.
2. Run the following command to preprocess the data and train the model:
    ```bash
    python train_model.py
    ```
3. Use the trained model to make predictions:
    ```bash
    python predict.py --input <path_to_input_data>
    ```

## Model Training
The model is trained using the `RandomForestClassifier`. Key steps include loading the dataset, extracting features and targets, splitting the data into training and testing sets, and fitting the model for prediction.

## Results
Our model achieved an accuracy of 97.43% on the test dataset. Detailed performance metrics and visualizations are available in the `results` directory.

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries or feedback, please contact:

Senay Berhe  
Email: [tsionberhe@gmail.com](mailto:tsionberhe@gmail.com)  
LinkedIn: [Senay Berhe](https://linkedin.com/in/senayberhe)  
GitHub: [Senay Berhe](https://github.com/senayberhe)

---

Feel free to adjust any sections to better fit your project's specifics!
