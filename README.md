- Doucments folder to maintain all doucments
- Source code folder contains the main website coding

# Procedure for Repo Checkout

- Install Git

    - on OSX install [home brew](http://brew.sh/) and open command prompt
    
        - type `brew install git`

    - on Windows install [Chocolety](https://chocolatey.org/install) and open terminal as administrator 

        - type `choco install git`

- Open terminal from the target folder

- Paste `git clone https://github.com/vminfra/C-Zentrix-website.git`

- To add new file to the repo, paste the file to any of the folders and run `git status`

- Type `git status` to view repo status

- Type `git diff` to view difference between local folder and the repo

- Type `git add .` to add all the file to the github repo (or) Type `git add file-path` to add a particular file to the repo

- Type `git commit -m "message"` to commit the file to the repo with commit message

- Type `git push origin master` to push the changes to the master repo

# Procedure to run & build application package

- On OSX install [home brew](http://brew.sh/)

    - On the project folder open command prompt as administrator
    
    - Type `brew install node`

- On Windows install [Chocolety](https://chocolatey.org/install)

    - open command prompt as administrator

    - type `choco install nodejs.install`
        
- On the project folder open command prompt/terminal

    - Type `npm install -g node-inspector bower gulp`
    
    - Type 'gulp-clean' to clean the code
    
    - Type 'gulp serve-dev' to run the application in the default browser (http://localhost:3000/)
    
    - Type 'gulp serve-build' to build the application package and open in the default browser (http://localhost:3000/)
    
        
        
