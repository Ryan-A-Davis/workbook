# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
For loading in dependencies into your application, as well as certain settings or addons.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
You need it at the top level, because if it is not, it won't run when your code is compiled.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run serve
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
environment variables
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
$ heroku logs, and filter with --source appname, or on the website in the dropdown menu
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Download the heroku client, and initialize a git repository tied to the app. Make changes then commit them and push to heroku.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching is important for version control, because if you are working as a team, it is possible that one push can break another persons, code, and make it impossibly difficult to resolve the isssue.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Before you push to the git.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merging branches
```
