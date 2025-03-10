# 🛑 **Notice** 🛑
**(We prepared Report 1 and Report 2 separately earlier, then we could only update Report 1 beacuse there were no option to upload 2 files. So here we included both Reports merged.)**

# Weather forecasting using Machine Learning

## 1. Create a Virtual Environment

To keep dependencies isolated, it is recommended to create a virtual environment.

### On macOS/Linux:
```sh
python3 -m venv .venv
source .venv/bin/activate
```

### On Windows:
```sh
python -m venv .venv
.venv\Scripts\activate
```

## 2. Install Dependencies
Ensure you have a `requirements.txt` file with necessary dependencies. Then, install them:
```sh
pip install -r requirements.txt
```

## 3. Install Jupyter Notebook
If Jupyter is not already included in your `requirements.txt`, install it manually:
```sh
pip install jupyter
```

## 4. Run Jupyter Notebook
Once all dependencies are installed, start the Jupyter Notebook server:
```sh
jupyter notebook final.ipynb
```

This will open the `final.ipynb` notebook in your browser, where you can create and run Jupyter Notebooks.

Alternatively, to run it in VS Code, install the Jupyter extension and open `final.ipynb` directly in VS Code.

## 5. Deactivate the Virtual Environment
After finishing your work, deactivate the virtual environment:
```sh
deactivate
```

## Notes
- Ensure `python` and `pip` are installed before running the commands.
- If you encounter any issues, ensure your virtual environment is activated before installing dependencies or running Jupyter.
