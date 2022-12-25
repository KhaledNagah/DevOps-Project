
READ.ME
To test a successful scenario:
-Open your browser and navigate to the website by typing http://20.15.232.36 to find the current version of the website.

-Commit a code change:
1- Navigate to the repository at https://github.com/KhaledNagah/DevOps-Project .

2- Commit a code change (e.g. navigate to ./src/index.html and change line 34 to “This is the new version” instead of “This is the current version”).

3-As we are using Github actions as a CI/CD tool, go to actions tab in github and navigate to the latest workflow run to monitor the CI/CD pipeline progress.

4- When the CI/CD pipeline completes progress, refresh the website to see the change.

5- You can go to actions tab in github and navigate to the latest workflow run to see the uploaded artifacts.

6- You can go to actions tab in github to see the previous history of the workflow runs.

7- You can navigate to my docker hub account at https://hub.docker.com/repository/docker/khalednagah/khaleddockerrepo to find the docker image that encapsulates the latest build. You can also see the history of the previous docker images for the previous builds.
login credentials :
email: khaled.nagah.99@gmail.con
password: P@ssw0rdP@ssw0rd 


To test a failure scenario:
-Open your browser and navigate to the website by typing http://20.15.232.36 to find the current version of the website.

-Commit a code change with a syntax error:
1- Navigate to the repository at https://github.com/KhaledNagah/DevOps-Project .

2- Commit a code change with a syntax error (e.g. navigate to ./src/main.ts and in line 29, write “This is a syntax error”).

3-As we are using Github actions as a CI/CD tool, go to actions tab in github and navigate to the latest workflow run to monitor the CI/CD pipeline progress.

4-You will find that the build job has failed, refresh the website to see that there is no change and the website is still working.
