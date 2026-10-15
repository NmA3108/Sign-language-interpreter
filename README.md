# Sign Language Interpreter

A computer vision and machine learning project for recognizing hand signs and interpreting sign language gestures.

## Overview

**Sign Language Interpreter** is a project that explores hand sign recognition using image data and a trained machine learning model. The project includes scripts for model training and application execution, along with a Jupyter Notebook for experimentation and development.

The goal is to explore how computer vision and machine learning can help make communication more accessible.

## Features

- **Hand Sign Recognition:** Recognize hand signs from image input.
- **Model Training:** Train a recognition model using a hand sign dataset.
- **Application Interface:** Run the recognition application using the provided Python scripts.
- **Experimentation:** Explore the model and training process through a Jupyter Notebook.

*Note: The available features depend on the current implementation and model configuration.*

## Tech Stack

- **Python** — Main programming language
- **Jupyter Notebook** — Experimentation and development
- **Machine Learning / Deep Learning** — Hand sign recognition
- **Keras** — Model format and model-related workflow

## Project Structure

```text
Sign-language-interpreter/
├── run_app.py
├── run_app_static.py
├── train.py
├── tgmt-hand-signv03 (2).ipynb
├── .gitignore
└── README.md
```

Dataset files and trained model files are not included in the current repository structure.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/NmA3108/Sign-language-interpreter.git
cd Sign-language-interpreter
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate the environment on Windows:

```powershell
.venv\Scripts\activate
```

### 3. Install Dependencies

Install the Python packages required by the project:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available yet, create it from the working environment or install the required packages separately.

### 4. Prepare the Dataset and Model

Before training or running the application, make sure the required dataset and trained model files are available.

- Place the dataset in the directory expected by the training script.
- Update the dataset paths if your local directory structure is different.
- Make sure the trained model path matches the path used by the application.

### 5. Train the Model

Run the training script:

```bash
python train.py
```

Check the script configuration for the expected dataset location and output model path.

### 6. Run the Application

To start the application, try:

```bash
python run_app.py
```

An alternative application script is also available:

```bash
python run_app_static.py
```

The exact startup requirements depend on the implementation of each script.

## Dataset and Model

The dataset and trained model are not included in this repository at the moment.

If you want to reproduce the project, prepare the required dataset and model files before running the application. Large datasets and model artifacts can be distributed separately to keep the Git repository manageable.

## Future Improvements

- Improve recognition accuracy and model performance.
- Add more hand signs and training samples.
- Improve the user interface and recognition feedback.
- Provide clearer setup instructions and sample demonstrations.
- Evaluate the model using appropriate performance metrics.


GitHub: [@NmA3108](https://github.com/NmA3108)

---

*This project was developed for learning and experimentation with machine learning and hand sign recognition.*
