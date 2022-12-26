# GIT COMMANDS

## Connecting project to repository
   ###
   ```
   git init
   git add .
   git commit -m "Add existing project files to Git"
   ```
  ### Adding private repository
    git remote add origin git://github.com/username/Web-App.git
  ### Public repository
    git remote add origin https://github.com/username/web-app.git
  ###
  ```git push -u origin main
  ```
  ### Changing repository url
    git remote set-url origin git://github.com/username/Web-App.git
    
  ### checking out pr
     ```
         git fetch origin pull/$prId/head
         git switch branch-name
     ```
