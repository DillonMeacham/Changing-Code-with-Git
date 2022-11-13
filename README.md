<h1>Changing Code with Git</h1>

<h2>Description</h2>
In this project, we are making code changes for a train-schedule app. We are a developer working with a dev team who uses feature branches to manage changes. 
<br />
<br />
'Feature Branches' are a very common standard for dev teams. Whenever code changes are made, a branch is used in source control to make changes to the code and later merge the branch through a pull request. This is useful to mantain multiple versions of the code with different changes simultaneously. 
<br />
<br />
Instead of the app's main page header reading "Train Schedule," the customer wants it to read “Find your train!”

Let’s get started.
<br />
<h2>Environments Used </h2>
</b>- Git</b>
<br />
</b>- GitHub.com</b>
<br />
</b>- Local Command Prompt CLI</b>

<h2>Project walk-through:</h2>

<p align="center">
First we have to SSH into the CentOS Cloud Server we will be working in. <br/>
<img src="https://imgur.com/lfKREUO.png" height="80%" width="80%" />
<br />
<br />
We also need to install Git.  <br/>
<img src="https://imgur.com/3dpbu59.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/8hn5BBK.png" height="80%" width="80%"/>
<br />
<br />
Then we need to set the name and email for commits on the system and configure for ssh authentication with GitHub.com. <br/>
<img src="https://imgur.com/UzJeTzc.png" height="80%" width="80%"/>
<br />
<br />
We now have to create a key pair with the following command 'ssh-keygen -t rsa -b 4096' and associate our public key with our GitHub account so that our current system can authenticate with GitHub.com.
<img src="https://imgur.com/0NkFaqv.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/ZdGqqSc.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/mxwOfR0.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/UdBGr31.png" height="80%" width="80%"/>
<br />
<br />
We are now going to create a personal fork (or copy) of the sample repository provided by the Linux Academy repo and clone it to our system. "https://github.com/linuxacademy/cicd-pipeline-train-schedule-git"
<img src="https://imgur.com/6xu2E9V.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/g36crE6.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/3EFYmLf.png" height="80%" width="80%"/>
<br />
<br />
Now time to change up the code. We need to create a feature branch to contain the changes we are making to the existing code in index.jane. I'm going to open the file in Vim to make the header change the customer desires.
<img src="https://imgur.com/4hIyPKE.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/eR2Q8uV.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/VxQYJgL.png" height="80%" width="80%"/>
<br />
<br />
Git has noticed the file has been changed, but now we need to STAGE the changes for Commit, and then Commit.
<img src="https://imgur.com/eWy6ukx.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/pOpmidS.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/GsyIECm.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/huSByoR.png" height="80%" width="80%"/>
<br />
<br />
We now need to push the change to the remote scm repository, create a pull request to merge the feature branch into the master branch, then finally merge the pull request.
<img src="https://imgur.com/yCkJD9P.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/OXFkSnz.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/2ercLFB.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://imgur.com/4UuFwMD.png" height="80%" width="80%"/>
<br />
<br />
DONE! We have now successfully made a change to a source file, managed that change within a branch, and put that change through a merge process using a pull request in order to merge the change into the master branch. 
<br />
Thank you for following along if you did. :)
