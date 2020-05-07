# mlops-assignment
Welcome to automation world

<h1>About the project<h1>
Automating the website deployment using jenkins,docker,git and gihub
  
<h3>Step-1 Creation of web pages<h3>
  1. using git terminal web pages are created for deployment in the website using docker container<br>
  2. Create a repository in the github to upload files from local repo to remote repo<br>
  3. upload pages to github
 <h3> Step-2 Launching the hpptd, jenkins services<h3>
   1. First start the service of httpd by command #systemctl start httpd<br>
   2. start the service of jenkins by command # systemctl start jenkins<br>
<h3>Step-3 Creation of jobs in jenkins<h3>
  <h5>1. job to development<h5>
  1.create a job in jenkins and add repository url:<br>
  2.Add poll scm trigger for monitoring the github for code changes<br>
  3.if any changes in the code appeared then copy the code to redhat directory to launch new docker container<br>
  <h5>2. job to deployment<h5>
  1.create job in jenkins and add repository url:<br>
  2.add poll scm trigger for monitoring <br>
  3.if all the testing are checked then it will be deployed to final deploymemt docker container 
