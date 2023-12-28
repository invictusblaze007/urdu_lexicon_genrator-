# Welcome to Urdu Lexicon Generator

- `main.py` - This is a summarized inference code implementation.

- `app.py` - This is a complete Flask app and an API to generate lexicons.

    - **Web App:**
      - You can run this app by executing the command `python app.py`. This will open a nice web UI for you.

    - **API Endpoint:**
      - The API is also defined in `app.py` and runs concurrently with the web UI. You can access the API at [http://localhost:5000/g2p](http://localhost:5000/g2p) using a POST request. The API requires a JSON object like this: `{"text": "رکوا\nایران\nخرید"}`. Each word is separated by a newline character (`\n`).

## Steps to Run this Model

1. Create an Anaconda environment with Python 3.6.

2. Navigate inside this directory and activate the conda environment using the command `conda activate env_name`.

3. Run the command below to install `tensorflow-1.0.0-cp36-cp36m-win_amd64.whl`:
   ```bash

    echo "pip install tensorflow-1.0.0-cp36-cp36m-win_amd64.whl"
    ls -l
   ```
4. Run the command below to install the requirements from `requirements.txt`:
  **cmd-->**pip install -r requirements.txt

5. Now you are ready to go. Run the command python app.py.

  Feel free to customize the content and formatting based on your specific preferences.
   
