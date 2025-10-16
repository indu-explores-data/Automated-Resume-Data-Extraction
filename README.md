# 🧠 Automated Resume Data Extraction Project

## 📘 Overview
This project focuses on automating the extraction of key information from resumes using Natural Language Processing (NLP) techniques. It streamlines the process of identifying candidate details such as name, email, and phone number, while demonstrating how NLP can convert unstructured data into structured, analyzable information.  
The ultimate goal is to make resume screening faster, more accurate, and scalable for real-world recruitment workflows.

---

## 🎯 Objectives
- Extract essential information such as Name, Email, and Contact Number from resume files.  
- Support multiple file formats including **TXT**, **DOCX**, and **PDF**.  
- Convert unstructured text into structured formats like JSON or CSV.  
- Demonstrate the real-world use of NLP in recruitment systems.  

---

## 🧩 Key Methods
- **Text Extraction:** Reading resumes across formats using libraries like `PyMuPDF`, `pdfminer`, and `docx2txt`.  
- **Named Entity Recognition (NER):** Leveraging `spaCy` to identify entities such as names, emails, and phone numbers.  
- **Regex Matching:** Extracting specific entities using regular expression patterns.  
- **Data Structuring:** Organizing extracted data into tabular formats for easy analysis or integration.  

---

## 📊 Visualizations

### 🧾 Extracted Resume Data
![Extracted Resume Data](images/Extracted%20Resume%20Data.png)

*DataFrame displaying names, phone numbers, and emails extracted from resumes across formats.*

---

## 🔍 Key Insights & Outcomes

### 🔹 Automated Information Extraction
The NER model successfully extracted **Name**, **Email**, and **Phone Number** from resumes across formats.  
This validates the ability of NLP to convert unstructured resume data into structured information.

### 🔹 Format Independence
The pipeline performed consistently across multiple file types (**TXT**, **DOCX**, **PDF**), demonstrating robustness and adaptability to real-world resumes.

### 🔹 Improved Efficiency
Manual resume screening is time-intensive.  
Automation reduces effort, minimizes errors, and accelerates candidate filtering.

### 🔹 Scalability
The system can process large volumes of resumes with minimal additional effort.  
It also provides a strong foundation for future extraction of **skills**, **education**, and **work experience**.

### 🔹 Practical Applicability
This project highlights how NLP can be applied in recruitment systems.  
It can be integrated into **Applicant Tracking Systems (ATS)** to enhance hiring efficiency.

---

## 🛠️ Technologies Used
- **Python** 🐍  
- **Jupyter Notebook**  
- **spaCy / NLTK** for NLP  
- **pandas** for data manipulation  
- **re (Regex)** for pattern-based extraction  
- **PyMuPDF / pdfminer / docx2txt** for text parsing  

---

## ⚙️ Setup & Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Resume-Extraction.git
   cd Resume-Extraction

2. pip install -r requirements.txt
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the Jupyter notebook:
   ```bash
   jupyter notebook "Automated Resume Data Extraction.ipynb"
   ```

## ▶️ **Usage Instructions**

- Upload or specify resume files (TXT, DOCX, or PDF).
- Run each notebook cell to extract and clean the data.
- View structured output and sample visualizations.
- Export the results to CSV/JSON for analysis or ATS integration.

## 🔗 **Connect with Me**

For feedback, collaboration opportunities, or related queries:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/indu-r-3a3767170/)

---
