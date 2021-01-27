![Python application test with Github Actions](https://github.com/yueyang0115/CI-CD-Scaffold-for-Python/workflows/Python%20application%20test%20with%20Github%20Actions/badge.svg)

# CI-CD-Scaffold-for-Python
This is a project scaffold for python using Github Actions  

The project can be created and deployed to cloud following these steps:  
1. Create a Github Repo, open Cloud Shell  
2. Create ssh-keys in Cloud Shell, upload ssh-keys to Github  
**3. Create a python virtual environment and source it**
   python3 -m venv ~/.myrepo  
   source ~/.myrepo/bin/activate  
4. Create scaffolding for the project, including Makefile, requirements.txt, source code and test code  
5. Run make all, which will install, lint, and test code  
**6. Setup Github Actions in main.yml**
7. Commit changes and push to Github, run project in Azure Shell
8. Verify Github Actions Test Software, add status badge


