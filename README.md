# PDF Protection with Python

This project uses Python to read a PDF file and create a new version with password protection and disabled text copying.

## 📁 Files in this Project

- `Pythontutorial_EDIT.pdf` – Original PDF file (unprotected)
- `looking_pdf.ipynb` – Jupyter notebook with code
- `pro_new.pdf` – New PDF file with password and security restrictions

## 🧠 What This Project Does

- Opens a PDF file using `pikepdf`
- Sets a **user password** and **owner password**
- **Disables text copying** from the PDF
- Saves the protected version as `pro_new.pdf`

## 🔐 Security Settings

- **User password:** `9090ro` (needed to open the file)
- **Owner password:** `rohit` (needed to remove protections)
- **Text copying:** ❌ Not allowed

## ▶️ How to Run

1. Make sure you have Python installed
2. Install the required library:
    ```bash
    pip install pikepdf
    ```
3. Run the notebook `looking_pdf.ipynb` step by step

## 🛠 Tools Used

- Python 3
- Jupyter Notebook
- `pikepdf` library for PDF encryption

## ✍️ Author

**Rohit Sahu**
