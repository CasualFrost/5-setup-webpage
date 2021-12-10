# 5-setup-webpage
Copy and paste this into Notes for checkmark
5 Step Setup Guide
 https://gist.github.com/jim-clark/9f9bd19d60d9ce2ec57be8242b6aee96

- [ ] Move into /code folder or where your project folder needs to be in
- [ ] Install Express in the folder you need to have your project in 
> express -e (name of project ex: mongoose-flights)
- [ ] Move into Project Folder
> cd (name of project ex: mongoose-flights)
- [ ] Install Node Modules 
> npm i
- [ ] Install .env 
> npm i dotenv
- [ ] Install mongoose 
> npm i mongoose
- [ ] Open in VSCode 
> code .
- [ ] Start Git Repo Process 
> git init
- [ ] Add changes for Repo 
> git add -A
- [ ] Commit changes to Repo 
> git commit -m “repo setup”
- [ ] Make repo on github and add local to remote 
> git remote add origin (link of github remote repo)
- [ ] Push to remote repo 
> git push -u origin main
- [ ] Add .env file
> touch .env

OR

Add through vscode “.env”

- [ ] Rename “app.js” to “server.js”
- [ ] In bin/www update line 7 to require “server” instead of “app”

![routes](https://i.imgur.com/IvNxOxC.png)

TO

![server](https://i.imgur.com/E2990JD.png)

- [ ] Test server if working 
> npm start

OR

> nodemon
- [ ] Add FOLDERS “models” and “controllers”
- [ ] Add FILE to models and controllers folders  
models/flight.js 
controllers/flights.js
- [ ] Add FOLDER “views”
- [ ] Add FILES to views folder 
views/error.ejs 
views/index.ejs
- [ ] Change Routes in Server.js folder

![image](https://i.imgur.com/QYX8FVJ.png)

TO

![image](https://i.imgur.com/CcJcroV.png)

- [ ] In routes/flights

![image](https://i.imgur.com/LlZKKIs.png)

TO

![image](https://i.imgur.com/zWXGxXf.png)

- [ ] In routes/flights

![image](https://i.imgur.com/bN0ar2H.png)

TO

![image](https://i.imgur.com/DXgULKG.png)

- [ ] Fill out lines below commments in routes/flights (Do each one individually fully onward, don’t add them all at same time)

![image](https://i.imgur.com/lAEBe99.png)

- [ ] IN “controllers/flights” file , Add module exports

![image](https://i.imgur.com/1Eep0Mn.png)

- [ ] IN “controllers/flights” file , Fill it out with “new,create,index,show” functions

![image](https://i.imgur.com/QjP2TdJ.png)

- [ ] IN “controllers/flights” file , Add blank functions of each one in module.exports

![image](https://i.imgur.com/uZV7Ulk.png)

Comment functions/exports not in use and test working ones with console.log(“Hello”) or console.log(req.params);
From this point on, modify each function with what you need and proceed to focusing on custom feature.
