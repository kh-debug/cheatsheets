# the terminal

### basic terminal commands

- `ls`: list contents of current directory
- `pwd`: print the path to your current directory
- `cd`: change directory:
   - `cd cheatsheets`: enter the "cheatsheets" dir
   - `cd ../`: go up one level
- `touch FILENAME`: create a file

### npm commands

- `npm install LIBRARY --save`: to install a library locally
- `npm install -g LIBRARY`: install a global library
- `npm start`: start your app
- `npm run build`: build your app
- `ctrl-c`: will stop your app

### git

- `git init`: starts a git repo in your current directory
- `git remote add origin https://github.com/USERNAME/REPO.git`: link to the remote origin on github.com
- `git add .`: add all files in current directory
- `git commit -m "message"`: commit your changes
- `git branch -M main`: make a branch called "main"
- `git push -u origin main`: push to github.com
   - after the first push, you can simple type `git push`
 
### firebase

- `npm install -g firebase-tools` to install firebase CLI
  - (or `curl -sL https://firebase.tools | bash`)
- `firebase login` to login
- On firebase console, create a new project, and create a Firestore
- `firebase init` to initialize a firebase project
  - select "Firestore" and "Hosting"
  - "Use an existing project" (select the project from the list)
  - "What do you want to use as your public directory?" `build`
  - "Configure as a single-page app?" `y`
  - "File "build/index.html" already exist. Overwrite?" `n`
- make you sure you app is built! (`npm run build`)
- `firebase deploy` !!!!!!!!
