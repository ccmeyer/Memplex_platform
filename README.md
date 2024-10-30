# Memplex Platform

This repository contains all code associated with the Memplex platform

## Prerequisites

Before you can run the code for the Memplex platform, make sure you have the following software installed:

- [Python](https://www.python.org/downloads/): Python is a programming language used by the LabCraft Printer project.

## Getting Started - Python

To get started with the Memplex platform, follow these steps:

1. Clone the Git repository to your local machine:

    ```bash
    git clone https://github.com/ccmeyer/Memplex_platform.git
    ```

2. Open the project folder in VSCode:

    ```bash
    cd Memplex_platform
    ```

3. Create a virtual environment for the project:

    ```bash
    python -m venv analysis_env
    ```

4. Activate the virtual environment:

    - On Windows:

      ```bash
      analysis_env\Scripts\activate
      ```

    - On macOS and Linux:

      ```bash
      source analysis_env/bin/activate
      ```

5. Install the project dependencies:

    ```bash
    pip install -r requirements.txt
    ```


## Organization of the repository
This repository contains all the code required to recreate all the figures of the manuscript along with the code to implement the active learning reaction selection. All the data is available in the supplementary files of the manuscript located here: _______. This data file must be downloaded, extracted, and added to the `all_data` directory. The code will search this folder for the required files to complete the analysis.
