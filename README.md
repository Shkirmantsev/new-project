# Steps:

- ```git init```
- ```git config user.name "Shkirmantsev"```
- ```git config user.name "Shkirmantsev"```
- ```git config user.email "shkirmantsev@gmail.com"```
-  generate token in developer settings of GitHub account
- ```touch README.md```
- change content of README.md
- ```curl -H "Authorization: token MY_GITHUB_TOKEN" https://api.github.com/user/repos -d '{"name":"new-project"}'``
- ```git remote add origin git@github.com:shkirmantsev/new-project```
- ```git add README.md```
- ```git commit -m "init"```
- ```git push -u origin master```
- ```git checkout -b development```
- change content of README.md
- ```git add  README.md```
- ```git push -u origin development```
- ```git commit -m "save changes in develop"
- ```git push```
- ```git checkout master```
- ```git status```
- ```git merge development```
- ```make changes in README.md```
- ```git add README.md```
- ```git status```
- ```git commit -m "Commit final changes in master"```
- ```git push```


