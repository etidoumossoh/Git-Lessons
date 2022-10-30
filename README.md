# Git-Lessons
Utiva Cloud Developers Git Lessons 
## Introduction on  How to Push From  Local Environment to Github  
Downloaded Gitbash (https://git-scm.com/downloads)  
# Configure gitbash  
git config --global user.name "name"  
git config --global user.email "email"  
# Working with the configured environment  
mkdir website  
cd website  
git init  
touch .index.html  
# Clone your Github repository  
git remote add origin URL (this should be the URL from your created repo and use HTTPS)  
# Push to Github  
git add index.html  
git commit-m "description"  
git push origin master  
