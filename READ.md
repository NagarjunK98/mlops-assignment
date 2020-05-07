Welcome to automation world

<h1>About the project<h1>
Automating the website deployment using jenkins,docker,git and gihub
  
<h3>Step-1 Creation of web pages<h3>
  1. using git terminal web pages are created for deployment in the website using docker container
  2. Create a repository in the github to upload files from local repo to remote repo
  3. upload pages to github
<h3> Creation of jobs in jenkins<h3>
  <h5>1. job to development<h5>
  create a job in jenkins and add repository url:
  Add poll scm trigger for monitoring the github for code changes
  if any changes in the code appeared then copy the code to redhat directory to launch new docker container
  <h5>2. job to deployment<h5>
  create job in jenkins and add repository url:
  add poll scm trigger for monitoring 
  if all the testing are checked then it will be deployed to final deploymemt docker container
