# online-recruitment-fraud-using-deep-learning-approaches
“Online Recruitment Fraud Detection using Deep Learning” flags suspicious job postings before they hit applicants. It ingests a posting’s text and metadata, learns patterns tied to scams, and outputs a fraud probability and a binary decision.
online-recruitment-fraud-detection/
├── data/
│   └── synthetic_jobs.csv              
├── src/
│   └── train.py                        
├── artifacts/                          
├── figures/                           
├── notebooks/
│   └── 01_eda.ipynb                    
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
Real-world use cases

Job boards and HR marketplaces auto-moderating new postings in real time.

Internal ATS systems screening third-party postings from vendors.

Trust & Safety teams using a queue of “high-risk” items with explanations.

Proactive takedown of accounts that repeatedly post high-risk jobs.
