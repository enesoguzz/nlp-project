# Turkish Spell Checker Project
This project aims to develop a system that detects and corrects Turkish spelling errors using natural language processing (NLP) techniques.

## Project Overview
- Uses Zemberek NLP for word analysis and root extraction.
- Utilizes the BERTurk model for context-based word correction.
- Develops a RESTful API with FastAPI.
- Implements a Chrome extension for a web-based user interface.

## Project Directory Structure
turkish-spell-checker/
│── data/                   # Text data for processing
│── models/                 # NLP models (BERT, Zemberek, etc.)
│── api/                    # FastAPI-based REST API
│── extension/              # Chrome extension files
│── tests/                  # Test scenarios
│── README.md               # Project documentation
│── requirements.txt        # Required Python libraries

## Team and Task Distribution
Team Member | Task | Branch Name
// sallama örnekledim.
Miray Köksal | Data processing & Zemberek integration | feature/data-preprocessing
Metin Can Kiser | Spell error detection (Noisy Channel Model & Levenshtein) | feature/spell-checking
Meryem Çanga | Context-based correction using BERTurk | feature/context-analysis
Emin Enes Oğuz | API development with FastAPI & Web integration | feature/api
Miray & Metin | Chrome extension development | feature/chrome-extension

Each team member will work on their designated branch.  
Once a feature is completed, a Pull Request (PR) should be opened and merged into the main branch.

## GitHub Workflow
1. **Clone the repository:**
   ```
   git clone https://github.com/enesoguzz/turkish-spell-checker.git
   cd turkish-spell-checker
   ```

2. **Create a new branch:**
   
   git checkout -b feature/branch-name
   

3. **Add changes and commit:**
   
   git add .
   git commit -m "Describe the feature added"
   

4. **Push the branch to GitHub:**
   
   git push origin feature/branch-name
  

5. **Create a Pull Request (PR) on GitHub and merge the changes into the main branch.**

6. **Update your local repository with the latest main branch:**
   git checkout main
   git pull origin main
   git checkout feature/branch-name
   git merge main
  

All team members should frequently commit their code, keep their branches up to date, and resolve any conflicts in collaboration with the team.
