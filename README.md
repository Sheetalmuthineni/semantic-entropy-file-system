# semantic-entropy-file-system
# Semantic-Entropy-File-System

Content-Based Document Clustering System using Machine Learning


## 📌 Project Overview

Smart File Organizer is an intelligent document management system that automatically organizes files based on their content.  
Unlike traditional file systems that rely on manual sorting or file names, this system reads the actual content inside documents and groups similar files together.

The application supports PDF and TXT files and dynamically creates subject-based folders using Machine Learning techniques.


## ❗ Problem Statement

Managing a large number of documents manually is time-consuming and inefficient.  
Traditional file systems:

- Do not analyze file content  
- Require manual categorization  
- Become unorganized as file count increases  
- Make searching for related documents difficult  

There is a need for an automated system that can analyze document content and group similar files together without human intervention.

## 💡 Proposed Solution

This project provides a Smart File Organizer that uses Natural Language Processing (NLP) and Machine Learning to automatically cluster documents based on their content.

The system:

1. Extracts text from uploaded files (PDF/TXT)
2. Cleans and preprocesses the text
3. Converts text into numerical form using TF-IDF vectorization
4. Applies K-Means clustering to group similar documents
5. Dynamically creates folders based on detected topics
6. Automatically moves related files into the same folder

This eliminates manual sorting and improves document organization efficiency.

## ⚙️ How the System Works

1. User logs into the system.
2. User uploads TXT or PDF files.
3. The system extracts text from each document.
4. Text is cleaned and preprocessed.
5. TF-IDF converts text into numerical vectors.
6. K-Means clustering identifies similar documents.
7. The system generates folder names using top keywords.
8. Folders are created dynamically.
9. Files are automatically moved into their respective folders.
10. The organized structure is maintained inside the root directory.

## 🧠 Technologies Used

- Python  
- Streamlit (User Interface)  
- Scikit-learn (TF-IDF & K-Means)  
- PyMuPDF (PDF text extraction)  
- SQLite (User Authentication)  
- OS & Shutil (File Handling)

- 📂 Key Features

Secure Login & Registration
PDF and TXT file support
Content-based document clustering
Automatic folder creation
Automatic file organization
Clean and simple interface

🔮 Future Enhancements
Use advanced semantic models (BERT embeddings)
Add document search functionality
Support additional file formats
Deploy to cloud environment

📌 Conclusion
Smart File Organizer provides an automated and intelligent solution for document management.
By leveraging TF-IDF and K-Means clustering, the system groups documents based on their actual content, reducing manual effort and improving productivity.
