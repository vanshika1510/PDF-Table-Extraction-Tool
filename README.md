# PDF Table Extraction Tool

## 📝 Overview

This project provides an efficient solution to extract tabular data from **system-generated PDFs** and save them in **structured Excel sheets**, without using **Tabula, Camelot, or image conversion techniques**.

It was designed as part of a **company recruitment assessment hackathon**, focusing on:

✅ Accurate extraction of tables (bordered/unbordered/irregular)  
✅ Direct PDF processing (no image conversion)  
✅ Clean, structured Excel output  
✅ Readable formatting & scalability  
✅ Compliance with given constraints  


## 🎯 Features

- **Processes Multiple PDFs** (Batch processing)
- Handles **multi-page PDFs**
- Extracts tables with/without borders, irregular shapes
- **Adds clear table headings** (`Table: 1`, `Table: 2`, etc.)
- **5 row spacing between tables** for better readability
- Outputs clean **Excel sheets**
- No hardcoding, scalable & maintainable solution


## 🛠️ Technologies & Libraries Used

| Technology      | Purpose                             |
|-----------------|-------------------------------------|
| Python 3.x      | Core language                       |
| pdfplumber      | PDF parsing & table extraction      |
| pandas          | Data handling & Excel export        |
| openpyxl        | Excel formatting (bold headings, font size) |

## 📂 Folder Structure

```
/Hackathon_PDF_Extractor
├── /input
│   ├── test3.pdf
│   └── test6.pdf
├── /output
│   ├── output_for_test3.xlsx
│   └── output_for_test6.xlsx
├── main.py
├── README.md
```



## 🚀 How It Works

1. **Extract Tables:**
   - Uses `pdfplumber` to extract tables directly from PDFs (text-based extraction, no image conversion).
  
2. **Format Output:**
   - Each table has a heading **`Table: n`**.
   - Headings are **bold, font size 20**.
   - 10 empty rows between tables/pages for visual separation.

3. **Export:**
   - Saves output as `.xlsx` in `/output/` folder.



## 🟢 How to Run:

1. **Clone the Repo:**
git clone https://github.com/Vanshika1510/Hackathon_PDF_Extractor.git
cd Hackathon_PDF_Extractor


2. **Install Dependencies:**

pip install pdfplumber pandas openpyxl


3. **Add Input PDFs:**

Place your PDF files in the `/input` folder.

4. **Run the Extractor:**


python main.py


5. **Check `/output/` folder for results!**



## ✨ Why This Stands Out:

- **Elegantly meets all challenge requirements.**
- Clean code, maintainable, highly scalable.
- Output readability is prioritized (heading, spacing).
- No over-engineering, uses Python’s strengths well.
- Can easily be expanded (e.g., JSON/CSV outputs, GUI layer).



## 📩 Contact:

**Vanshika**  
[LinkedIn Profile](https://www.linkedin.com/in/vanshika1510/) 
