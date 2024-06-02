# Automatic Speech Recognition (ASR) Project

This repository contains Jupyter notebooks for processing and transcribing audio files. 

## Setup Instructions

Follow these steps to set up your environment locally on macOS:

1. **Create a directory for the project:**
    ```sh
    mkdir test-ASR
    ```

2. **Set up a virtual environment:**
    ```sh
    export VENVDIR=~/test-ASR
    python3 -m venv $VENVDIR
    ```

3. **Activate the virtual environment:**
    ```sh
    cd $VENVDIR
    source $VENVDIR/bin/activate
    ```

4. **Upgrade `pip`:**
    ```sh
    python -m pip install --upgrade pip
    ```

5. **Install JupyterLab:**
    ```sh
    pip install jupyterlab
    ```

6. **Install additional Jupyter dependencies:**
    ```sh
    pip install --upgrade jupyter ipywidgets
    ```

7. **Launch JupyterLab:**
    ```sh
    jupyter lab
    ```

8. **Install required Python packages:**
    ```sh
    pip install pydub torch transformers soundfile
    ```

## Running the Notebook

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/test-ASR.git
    cd test-ASR
    ```

2. Activate the virtual environment (if not already activated):
    ```sh
    source bin/activate
    ```


3. Start JupyterLab (if not already running):
    ```sh
    jupyter lab
    ```

4. Open and run the notebook `test-ASR.ipynb` in JupyterLab.

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

## Notes

- Ensure your audio files are placed in the `data/` directory.
- The transcriptions will be saved in the `data/` directory.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.