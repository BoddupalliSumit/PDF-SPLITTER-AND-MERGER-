# 📄 PDF Splitter and Merger

A Python-based GUI tool to **merge** multiple PDF files into one and **split** a PDF file into individual pages. This tool is built using `Tkinter` for the user interface and `PyPDF2` for PDF processing.

---

## 📁 Project Structure

```
├── PDF SPLITTER AND MERGER.ipynb    # Jupyter notebook with the code
├── requirements.txt                 # List of required Python packages
├── README.md                        # Project documentation
```

---

## ✅ Features

- 📂 Merge multiple PDF files into a single file
- ✂️ Split any PDF into individual pages
- 🖥️ Simple graphical interface using `Tkinter`
- 📥 Supports drag-and-drop file selection (optional in GUI)

---

## ▶️ How to Run

### 🧪 Option 1: Run in Jupyter Notebook
1. Open `PDF SPLITTER AND MERGER.ipynb`.
2. Run the cells step-by-step.
3. Use the widgets or prompts to select and process PDF files.

### 💻 Option 2: Export as `.py` and Run
1. Convert the notebook to `.py` using:
   ```bash
   jupyter nbconvert --to script "PDF SPLITTER AND MERGER.ipynb"
   ```
2. Run the script:
   ```bash
   python "PDF SPLITTER AND MERGER.py"
   ```

---

## 📦 Requirements

Install dependencies using:
```bash
pip install -r requirements.txt
```

---

## 🚀 Future Improvements

- Add preview of selected PDFs
- Support password-protected PDFs
- Progress bar for merging/splitting operations

---

## 📃 License

This project is open source and available under the [MIT License](LICENSE).
