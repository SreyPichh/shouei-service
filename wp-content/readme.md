Clone the project to your local machine

cd to your project directory (this is master branch)

before developing switch branch to your own branch 
EX: branch name : jonh
- git checkout -b jonh

To check which branch you are in : git branch

Now you are ready to develop

when you make changes in your local code, please push the code to your worked branch in order to avoid conflict
> git push origin "branch name"

after that you can make pull request to master branch to merge the code together 


you can refer this commit message to make it easy to understand every commit as a best practice, (This is optional)
##Github commit message 
Commit message:
* feat: A new feature
* fix: A bug fix
* docs: Documentation only changes
* style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
* refactor: A code change that neither fixes a bug nor adds a feature
* perf: A code change that improves performance
* test: Adding missing or correcting existing tests
* chore: Changes to the build process or auxiliary tools and libraries such as documentation generation