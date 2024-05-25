# Deploying RAG application using AWS(AWS lambda, AWS ECR, ), LangChain, Huggingface, Docker
Creating conda environment
'''
conda create -p venv python==3.7 -y
'''
use command prompt to use below command
conda activate venv/ or conda activate venv

pip install -r requirements.txt

git status

Create a repository on GitHub
Delete existing .git file in your local directory
git init
git add .
git commit -m"My first commit"
Now check your branch name. It will be master in your local project
git remote add origin <remote repository URL past here from the GitHub repository>, 
git remote -v
git push -f origin main
Now check the GitHub repository. You will see two branch 1. main 2. master
In your local repository create a new branch and the branch name will be main
git checkout main
git merge master
git pull origin main
git push -f origin main
