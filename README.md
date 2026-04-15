# Resume-Fitment-Scoring

## Overview
This project implements an automated recruitment screening system that evaluates candidates based on predefined criteria such as skills, experience, and qualifications.

It generates a structured output dataset (`recruitment_screening_output.csv` / `resume_fitment_scoring_result.csv`) to help recruiters efficiently shortlist the most suitable candidates.

---

## Objectives
- Automate resume screening process  
- Reduce manual effort in hiring  
- Improve candidate shortlisting accuracy  
- Provide data-driven hiring insights  

---

## Project Structure
Recruitment-Screening
│── recruitment_screening_output.csv
│── resume_fitment_scoring_result.csv
│── README.md


---

## Dataset Description
The dataset contains processed candidate information where each row represents an individual candidate.

### Key Columns
- **Candidate_ID** → Unique identifier  
- **Name** → Candidate name  
- **Skills** → Relevant skills  
- **Experience** → Years of experience  
- **Education** → Qualification details  
- **Score** → Calculated fitment score  
- **Status** → Final result (Selected / Shortlisted / Rejected)  

---

## How It Works
1. Collect candidate data  
2. Apply screening criteria:
   - Skills matching  
   - Experience threshold  
   - Qualification check  
3. Generate a fitment score  
4. Classify candidates into:
   - Selected  
   - Shortlisted  
   - Rejected  

---

## Technologies Used
- Python 
- Pandas   
- CSV Data Processing  

---

## Getting Started

### 1️⃣ Clone the Repository
git clone https://github.com/... cd recruitment-screening pip install pandas import pandas as pd
cd recruitment-screening
2️⃣ Install Dependencies
pip install pandas
3️⃣ Run the Code
import pandas as pd

df = pd.read_csv("recruitment_screening_output.csv")
print(df.head())

# Use Cases
Automated resume screening
Candidate shortlisting
HR analytics & reporting
Decision support systems

# Disclaimer
This system is intended for decision support only
It should not replace human judgment in hiring
Ensure data privacy and ethical usage of candidate data

Future Enhancements
Machine Learning-based scoring model
Web-based user interface
Advanced analytics dashboard
NLP-based resume parsing

# Conclusion

This project demonstrates how automation can streamline the recruitment process, making it faster, more efficient, and data-driven.
