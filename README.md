This template creates an EC2 instance with Apache HTTP server installed and running, serving a basic HTML page. Additionally, it creates a CodeCommit repository with the specified name. 


Connect to EC2 instance which is created by cloudformation tempelet @cf-s3-cicd.yaml

Run below to push into codecommit repository

git config --global user.name "user"
git config --global user.email "email-id"
git init
git add .
git commit -m "1st commit"
git remote add origin "your codecommit http link"
git push origin master
