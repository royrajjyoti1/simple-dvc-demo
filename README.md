create env
 '''bash
 conda create -n wineq python=3.7 -y
 '''

 activate env
 '''bash
 conda activate wineq
 '''
  
created a requirements file
install the requirements
'''bash
pip install -r requirements.txt
'''


Download Data

Initiate git,dvc
git init

dvc init

dvc add data_given/winequality.csv


git init

dvc init

dvc add data_given/winequality.csv

git add .
git commit -m "first commit"

#Update again and again
git add . && git commit -m "update Readme.md"

git remote add origin https://github.com/c17hawke/simple-dvc-demo.git
git branch -M main
git push origin main