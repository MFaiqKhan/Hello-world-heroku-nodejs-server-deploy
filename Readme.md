# Step for Beginners: 
1.)- [x] Create a .mjs file sematically named (server or anything you like but mostly give it a server as you- [x] are deploying a server)
2.)- [x] Create a .gitignore file
3.) run ""npm init -y" in the root directory of server.mjs => file named package.json will be created
4.) add { "Start" : "node app.js"  } in package.json in the 'script' object
5.) run "npm i express" (to install express as a local dependency) => package-lock.json will be created
6.) right the code/paste in server.mjs
7.) run "npm start" for the code to run in your localhost
7.) add /node_modules in .gitignore before the repository in github
8.) Create a file named "Procfile" for heruko deployment
9.) right "web : npm start" in Procfile
10.) Push code to repository 
11.) Do your configuration in Heruko Dashboard and deploy the build on cloud.
12.) access your server from the gihub environment 

# Fin !
