# Syllabus Based Automated Question Papers Generation System

This project automates the generation of university-level question papers directly from syllabus content. It extracts text from PDF or text files (such as a course syllabus and a model question paper) and uses AI (via the Groq API) to generate a structured question paper. The questions are organized by parts, with each question tagged with Course Outcomes (CO#) and Bloom’s Taxonomy levels (BL#) to ensure a balanced and syllabus-aligned assessment.

## Key Features
- **Automated Text Extraction:**  
  Utilizes PyPDF2 to parse and extract text from PDF files.
- **AI-Powered Generation:**  
  Integrates the Groq API to generate questions based on syllabus and model paper inputs.
- **Structured Format:**  
  Produces a comprehensive question paper divided into:
  - **Part A:** Short numerical problems.
  - **Part B:** Choice-based numerical problems.
  - **Part C:** Advanced problem-solving questions.
- **Bloom’s Taxonomy & CO Alignment:**  
  Each question includes markers for Course Outcomes (CO#) and Bloom’s Taxonomy levels (BL#) to ensure academic rigor and balanced coverage.
- **Reduced Manual Workload:**  
  Streamlines the assessment creation process for educators, saving valuable time and ensuring consistency.

## Prerequisites
- **Python 3.11**
- **PyPDF2:**  
  For PDF parsing  
  ```bash
  pip install PyPDF2 
- **Groq Python Client:**
  ```bash
    pip install groq
- **Groq API Key:**
A valid key is required to access the AI text generation service.

## Installation
- **Clone the Repository:**
 ```bash
    git clone https://github.com/pravinkannan18/Syllabus-Based-Automated-Question-Papers-Generation-System.git
    cd Syllabus-Based-Automated-Question-Papers-Generation-System
```
## Usage
- **Prepare Your Input Files:**
Syllabus File: e.g., Probability_Syllabus.pdf
Model Paper File: e.g., model question paper.pdf
- **Run the Main Script:**
Open and run Question paper generation.ipynb. The script will extract text from the input files and generate a complete question paper, outputting it to the console.

## Project Structure

Syllabus-Based-Automated-Question-Papers-Generation-System/
│
├── Question paper generation.ipynb   # Main script for question paper generation
├── README.md                         # Project documentation
├── Probability_Syllabus.pdf          # Example syllabus file
├── model question paper.pdf          # Example model paper file
└── ...

## Acknowledgments
Dr. Sumathi S for providing guidance and project support.
Karthikeyan S for collaboration and technical contributions.
For more details, visit the repository: [Syllabus Based Automated Question Papers Generation System](https://github.com/pravinkannan18/Syllabus-Based-Automated-Question-Papers-Generation-System)

