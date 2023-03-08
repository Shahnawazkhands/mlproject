# Data science lifecycle with end to end project deployment steps
1. Create project folder in your system

2. Come inside that project in vscode or pycharm by changing the directory i.e cd paste your project folder path here

3. Create new environment
   Vs-Code terminal>conda create -p venv python==3.8 -y
   
   3.1 To activate the environment
   Vs-Code terminal>conda activate venv

4. If you are getting traceback like "Conda SSL Error: OpenSSL appears to be unavailable on this machine" then follow the below video
   "https://www.youtube.com/watch?v=hfKAV6OYaKw"
   4.1 I hope your error will get resolve then follow the step(3) again

5. Create new repository in the Github then copy and hit the commands one by one in your vscode or pycharm terminal

 5.1 To Initialize the git "git init"
 5.2 First create file then hit this command "git add README.md"
 5.3 Do changes as per the need and want to save the same "git commit -m "This is my first commit"
 5.4 In which branch you want these changes "git branch -M main"
 5.5 To sync your local and online GitHub repo "git remote add origin https://github.com/your_GitHub_user_name/Github_repo_name.git
 5.6 To push from local to online GitHub repo "git push -u origin main"
