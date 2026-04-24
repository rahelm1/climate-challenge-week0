Climate Challenge Week 0 – Exploratory Data Analysis

PROJECT OVERVIEW This project focuses on performing exploratory data
analysis (EDA) of historical climate data across five African countries.

Checking python installation mine is already created.

REPOSITORY SETUP 
1. Create GitHub repository: climate-challenge-week0 
2. Clone repository: on command prompt:- cd D:\10academy\week0\climate-challenge-week0
 git clone https://github.com/rahelm1/climate-challenge-week0
3.  Open VS code-> open the created repo-> cretae new teminal -> run the below commands on terminal
Create virtual environment: python -m venv .venv

Activate: Windows: .venv\Scripts\activate

git --version → Check if Git is installed and see the version.
git config --global user.name "rahelm1"
git config --global user.email "ritamesele3@gmail.com"

Create branch: git branch setup-task
Push branch: git push origin setup-task
Go to new branch-> git checkout setup-task
Check which branch it is-> git status
On setup-task-> create file .gitignore -> add this code 
.venv
data/
*.csv
.ipynb_checkpoints/
-> create new file -> requirements.txt->pip install pandas->pip install -r requirements.txt->pip freeze > requirements.txt
-> create new folder-> notebooks->__init__.py
-> create new folder-> src
-> create new folder ->.github/workflows/ci.yml add CI code that runs python --version or pip install -r requirements.txt on every push to the main branch.
-> Open README.txt-> add documentation
NB: add all changes and commit with commit message
publish or git push origin main
git merge setup-task
On github Create Pull Request/ Pull main locally
Run CI checks
