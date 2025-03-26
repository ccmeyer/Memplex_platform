# Memplex Platform

This repository contains all code associated with the Memplex platform

## Prerequisites

Before you can run the code for the Memplex platform, make sure you have the following software installed:

- [Python](https://www.python.org/downloads/): Python is a programming language used by the Memplex project.

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
This repository contains all the code required to recreate all the figures of the manuscript along with the code to implement the active learning reaction selection. All the data is available through Zenodo at the DOI: 10.5281/zenodo.15086208. The data file will download as a ZIP file and must be extracted. Once extracted add all the directories to the `all_data` directory. The code will search this folder for the required files to complete the analysis.

## Citation
If you use this code or data in your research, please cite:
**Conary Meyer and Alessandra Arizzi, et al.** *Designer artificial environments for membrane protein synthesis.* Nature Communications, 2025. [DOI coming soon]
