## End to End Machine Learning Project
# Nandani's Machine Learning Portfolio

Welcome to my machine learning portfolio! This repository showcases my end-to-end machine learning project using CatBoost, Python, and Flask, with a focus on data preprocessing, model training, and deployment.

# ML Project Portfolio

Welcome to my machine learning project portfolio! This repository contains a machine learning pipeline using CatBoost for model training, Flask for deployment, and a variety of utility modules for error handling and logging.

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

  python app.py

  ### Open `index.html` in Your Preferred Web Browser

- **In Visual Studio Code**: 
  - Right-click on `index.html` in the Explorer panel.
  - Select **"Open with Live Server"** (requires the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) installed in Visual Studio Code).
  
- **Alternatively**: 
  - Open the file directly in your browser by navigating to the project directory in your file explorer.
  - Double-click on `index.html` to open it.



MLProject/
├── artifacts/                    # Stores model artifacts and serialized files
├── catboost_info/                # Directory with CatBoost training information
│   ├── learn/
│   ├── tmp/
│   ├── catboost_training.json    # JSON file with training configuration
│   ├── learn_error.tsv           # Training error logs
│   └── time_left.tsv             # Time left for training
├── logs/                         # Log files generated during execution
├── notebook/                     # Jupyter notebooks for data analysis and exploration
│   └── data/                     # Folder for raw data used in the notebooks
├── src/                          # Source code for custom modules
│   ├── components/               # Custom components for data processing
│   ├── pipeline/                 # Pipeline scripts for data and model processing
│   ├── exception.py              # Custom exception handling module
│   ├── logger.py                 # Logging configuration and functions
│   └── utils.py                  # Utility functions for data handling and processing
├── templates/                    # HTML templates for the Flask web app
│   ├── home.html                 # Home page template
│   └── index.html                # Main landing page for the application
├── venv/                         # Virtual environment files (not included in GitHub)
├── .gitignore                    # Files and directories to ignore in Git
├── app.py                        # Flask application entry point
├── README.md                     # Project README file
├── requirements.txt              # List of Python dependencies
└── setup.py                      # Setup script for packaging the project

