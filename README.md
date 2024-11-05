## End to End Machine Learning Project
# Machine Learning Project

Welcome to my machine learning project! This repository showcases my end-to-end machine learning project using CatBoost, Python, and Flask, with a focus on data preprocessing, model training, and deployment.

# ML Project 

Welcome to my machine learning project ! This repository contains a machine learning pipeline using CatBoost for model training, Flask for deployment, and a variety of utility modules for error handling and logging.

## 📋 Project Sections

1. **Home**: An introduction page with a brief overview of the project and any relevant links.
2. **About**: Detailed information about the project background, purpose, and objectives.
3. **Model Training**: Includes training scripts, data preprocessing, and model evaluation.
4. **Deployment**: A Flask web application that hosts the trained model.
5. **Utilities**: Custom Python modules for error handling, logging, and other reusable code.
6. **Notebooks**: Jupyter notebooks for data exploration and analysis.

## 🚀 Getting Started

### Prerequisites

To run this project, you’ll need the following:

- **Python 3.6+**
- **CatBoost** (for model training)
- **Flask** (for web deployment)
- **Jupyter Notebook** (for data analysis)
- **Virtual environment** (optional but recommended)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/nandani537/MLProject.git


## 🚀 Getting Started

### Prerequisites

To run this project, you’ll need:

- **Python 3.6+**
- **CatBoost** (for model training)
- **Flask** (for deployment)
- **Jupyter Notebook** (for data analysis)
- **Virtual environment** (optional but recommended)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/nandani537/Nandani-Portfolio.git

2. **Navigate to the project folder**:

   ```bash
   cd MLProject

3. **Create a virtual environment**:

   ```bash
   python3 -m venv venv
  source venv/bin/activate  # On Windows use `venv\Scripts\activate

4. **Install dependencies**:

   ```bash
   pip install -r requirements.txt

5. **Run the Flask application**:

   ```bash
   python app.py


### Explanation of Key Folders and Files

- **artifacts/**: Contains model artifacts, including trained models and any serialized data required for inference.
- **catboost_info/**: Directory with CatBoost-specific training information.
- **logs/**: Log files that capture execution details for debugging and tracking.
- **notebook/**: Includes Jupyter notebooks used for data exploration and experimentation.
- **src/**: Source code for core modules, including:
  - `components/`: Contains components for data processing.
  - `pipeline/`: Scripts for model pipeline and processing.
  - `exception.py`: Module for handling exceptions.
  - `logger.py`: Logging configuration and functions.
  - `utils.py`: Utility functions to aid in data processing.
- **templates/**: HTML templates for the web application frontend.
- **venv/**: Virtual environment directory (excluded from GitHub).
- **app.py**: The main Flask application file.
- **requirements.txt**: Lists the Python packages and dependencies for the project.
- **setup.py**: Script for packaging the project if required.



## 🛠️ Technologies Used

- **Python**: Core programming language for the entire project.
- **CatBoost**: Machine learning algorithm used for training the model.
- **Flask**: Web framework for deploying the model as a web service.
- **Jupyter Notebook**: Used for data exploration and analysis.
- **HTML & CSS**: Basic styling and structure for the web application.
- **Logging and Exception Handling**: Custom modules for efficient debugging and tracking.

## 📝 Project Details

### 1. Data Preprocessing

- **Location**: `src/components/`
- **Description**: Includes scripts for data cleaning and preparation. Handles tasks such as:
  - Missing value handling
  - Feature engineering
  - Data transformations for model compatibility

### 2. Model Training

- **Location**: `src/pipeline/`
- **Description**: Contains scripts for training the CatBoost model on preprocessed data.
  - Logs training metrics for analysis
  - Saves model artifacts in the `artifacts/` directory for future use or deployment

### 3. Flask Deployment

- **Location**: `app.py`
- **Description**: Main application script that serves the model through a simple UI.
  - HTML templates (`home.html` and `index.html`) are located in the `templates/` directory.
  - Uses Flask to deploy the model as a web service with a user-friendly interface.

### 4. Logging and Error Handling

- **Location**: `src/`
  - **Logging Module**: `logger.py`
  - **Exception Handling Module**: `exception.py`
- **Description**: Provides structured logging and error management throughout the application. Ensures efficient debugging and tracking of events and errors.

### Open `index.html` in Your Preferred Web Browser

- **In Visual Studio Code**: 
  - Right-click on `index.html` in the Explorer panel.
  - Select **"Open with Live Server"** (requires the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) installed in Visual Studio Code).
  
- **Alternatively**: 
  - Open the file directly in your browser by navigating to the project directory in your file explorer.
  - Double-click on `index.html` to open it.