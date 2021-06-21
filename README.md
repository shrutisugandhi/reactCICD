### CICD Pipeline Demo For React Application 
### https://dev.to/preethamsathyamurthy/introduction-to-setting-up-a-ci-cd-pipeline-for-react-apps-34ha

1.  create a new react app

2. Create SSH keys to connect to GitHub account
 a. Create an ssh key in the system using ssh-keygen command. In windows, use PowerShell to run this command

PS C:\react\reactcicd> ssh-keygen
 

 b. github_sshKey -> privateKey
 github_sshKey.pub ->public key


3. Add the public key in Github  ->profile icon -> settings->SSh & GPG Key -> ADD SSH Key -> open github_sshkey.pub (public key) and paste in key textbox -> Add

## Now we will be able to access your Github repositories from our machine.

4. Create a new repository in Github

### https://github.com/shrutisugandhi/reactCICD.git


5. GO to project folder ->git init

6. git add .