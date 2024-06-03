# Automatic Speech Recognition (ASR) Project

This repository contains Jupyter notebooks for processing and transcribing audio files. 

## Setup Instructions

Follow these steps to set up your environment locally on macOS:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/alastori/test-ASR.git
    cd test-ASR
    ```
    
2. **Define the virtual environment directory:**
    ```sh
    export VENVDIR=$(pwd)
    ```

3. **Set up a virtual environment:**
    ```sh
    python3 -m venv $VENVDIR
    ```

4. **Activate the virtual environment:**
    ```sh
    source bin/activate
    ```

5. **Upgrade `pip`:**
    ```sh
    python -m pip install --upgrade pip
    ```

6. **Install JupyterLab:**
    ```sh
    pip install jupyterlab
    ```

7. **Install additional Jupyter dependencies:**
    ```sh
    pip install ipywidgets
    ```


## Running the Notebook

1. Activate the virtual environment (if not already activated):
    ```sh
    source bin/activate
    ```

2. Start JupyterLab (if not already running):
    ```sh
    jupyter lab
    ```

3. Open and run the notebook `test-ASR.ipynb` in JupyterLab.

### Notes

- Ensure your audio files are placed in the `data/` directory.
- The transcriptions will be saved in the `data/` directory.


## Project Structure

```
test-ASR/
│
├── .gitignore # Git ignore file
├── README.md # Project README file
├── test-ASR.ipynb # Jupyter notebook with ASR script
├── data/ # Directory to store audio files
└── temp/ # Directory to store temporary files
```


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
