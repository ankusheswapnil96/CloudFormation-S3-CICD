This template creates an EC2 instance with Apache HTTP server installed and running, serving a basic HTML page. Additionally, it creates a CodeCommit repository with the specified name. <br>


Connect to EC2 instance which is created by cloudformation tempelet @cf-s3-cicd.yaml<br>

Run below to push into codecommit repository

git config --global user.name "user"<br>
git config --global user.email "email-id"<br>
git init<br>
git add .<br>
git commit -m "1st commit"<br>
git remote add origin "your codecommit http link"<br>
git push origin master<br>
