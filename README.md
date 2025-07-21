# 🏀 UCSD Basketball XML → Smartabase CSV (JupyterLite)

This JupyterLite site converts NCAA box score XML files into **Smartabase-compatible CSV files** for **UCSD players only**.

## 🔗 Purpose of This Link

This site allows users (e.g. coaches, analysts) to:
- Upload raw XML files from NCAA game data
- Convert and download a CSV formatted to match UCSD's Smartabase form fields
- Run everything **in-browser** — no installation needed

## ⚙️ Powered by Pyodide

This JupyterLite environment runs Python entirely in your browser using [Pyodide](https://pyodide.org/).  
That means:
- No need to install Python, pandas, or any packages
- All processing happens locally in your browser

## 🧪 How to Use It

1. **Open the site**:  
   [https://judemariadas.github.io/jupyterlite-ucsd-basketball-scores](https://judemariadas.github.io/jupyterlite-ucsd-basketball-scores)

2. **Upload your XML file**:  
   Click the folder icon (📁) in the left sidebar → drag in your `.XML` file.

3. **Open the notebook**:  
   `UCSD_XML_to_Smartabase.ipynb`

4. **Follow the instructions** in the notebook:  
   - Select the uploaded XML file by index  
   - Run the code cells  
   - Download the generated CSV

---

This tool ensures UCSD basketball stats are correctly formatted for Smartabase uploads.
