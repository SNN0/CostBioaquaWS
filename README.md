# Water Quality Analysis and Prediction

This project is dedicated to analyzing and predicting water quality through the implementation of various machine learning and deep learning models. The analysis is documented in two separate Jupyter Notebooks, each focusing on a different modeling approach.

## Prerequisites

Before you begin, ensure you have a Conda environment manager installed on your system. If you don't have it, you can download and install it from one of the following sources:
* [Anaconda Distribution](https://www.anaconda.com/products/distribution) (Includes Python and many packages)
* [Miniforge](https://github.com/conda-forge/miniforge) (A minimal Conda installer)

## Installation

Follow these steps to set up the project environment on your local machine.

1.  **Clone the Repository**

    First, clone this repository to your local machine (if it's on a platform like GitHub).
    ```bash
    # Replace <repository-url> with the actual URL of your repository
    git clone <repository-url>
    cd <repository-directory>
    ```

2.  **Create the Conda Environment**

    Use the provided `environment.yml` file to create a new Conda environment with all the necessary dependencies. This file ensures that you have the exact versions of the packages used in this project.
    
    Run the following command in your terminal:
    ```bash
    conda env create -f environment.yml
    ```
    This command will create a new environment named `bioaqws`.

3.  **Activate the Environment**

    Once the installation is complete, activate the newly created environment:
    ```bash
    conda activate bioaqws
    ```
    You must have this environment activated anytime you work on the project.

## Usage

After setting up and activating the environment, you can run the project notebooks.

1.  **Launch Jupyter Notebook**

    Start the Jupyter server by running the following command in your terminal:
    ```bash
    jupyter-lab
    ```
    This will open a new tab in your default web browser with the Jupyter file explorer.

2.  **Run the Analysis**

    Navigate to the project directory and open the following notebooks to explore the analysis:
    * `session1_ML.ipynb`: Contains the analysis and implementation of classical machine learning models for water quality classification.
    * `session2_DL.ipynb`: Contains the analysis and implementation of a deep learning model.

## Recommended Development Tools

For a more integrated and efficient development experience, it is recommended to use [Visual Studio Code](https://code.visualstudio.com/) with the official **Python** and **Jupyter** extensions. It allows you to run and debug notebooks directly within the editor.
