# Step-by-Step Guide to Setting Up VS Code, Python, and Jupyter Notebook

## 1. Install Visual Studio Code (VS Code)
1. Download VS Code from the official website: [VS Code Download](https://code.visualstudio.com/)
2. Run the installer and follow the setup instructions.
3. Open VS Code after installation.

## 2. Install Python
1. Download Python from the official website: [Python Download](https://www.python.org/downloads/)
2. Run the installer and **check the box** for `Add Python to PATH`.
3. Click on **Install Now** and complete the installation.
4. Verify installation by opening Command Prompt (cmd) or Terminal and running:
   ```sh
   python --version
   ```

## 3. Install Python Extension in VS Code
1. Open VS Code.
2. Go to the Extensions Marketplace (`Ctrl+Shift+X`).
3. Search for `Python` and install the extension by Microsoft.

## 4. Set Up a Virtual Environment (Optional but Recommended)
1. Open a terminal in VS Code (`Ctrl+``).
2. Navigate to your project folder:
   ```sh
   cd path/to/your/project
   ```
3. Create a virtual environment:
   ```sh
   python -m venv venv
   ```
4. Activate the virtual environment:
   - Windows:
     ```sh
     venv\Scripts\activate
     ```
   - macOS/Linux:
     ```sh
     source venv/bin/activate
     ```

## 5. Install Jupyter Notebook
1. Open a terminal and run:
   ```sh
   pip install jupyter
   ```
2. Verify installation:
   ```sh
   jupyter --version
   ```

## 6. Open Jupyter Notebook in VS Code
1. Open a Python file (`.py`) or a Jupyter Notebook (`.ipynb`) in VS Code.
2. Click on `Select Interpreter` (bottom-left) and choose the correct Python environment.
3. Run the command to start Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Alternatively, use the built-in notebook editor in VS Code by opening an `.ipynb` file.

## 7. Running Python Code in Jupyter Notebook
1. Create a new notebook (`File > New File > Jupyter Notebook (.ipynb)`).
2. Type Python code in a cell and run it using `Shift + Enter`.

## 8. Additional Tips
- Use `Ctrl+Shift+P` to open the command palette and search for `Python: Select Interpreter`.
- Use `pip install <package>` to install required libraries.
- Use `jupyter notebook --notebook-dir=path/to/your/folder` to open notebooks in a specific directory.

## 9. Troubleshooting
- If Jupyter is not recognized, restart VS Code and reopen the terminal.
- If the kernel is not found, select the correct interpreter from the Python extension.

### Now you're all set to use Python and Jupyter Notebook in VS Code!