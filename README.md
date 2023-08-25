# Test git
## 创建git仓库
![Alt text](image.png)
```
git config --global user.name "xxxx"
git config --global user.email "xxxx@emal.com"
git init
git add .
git commit -m "first commit"
git branch -M develop
git remote add origin https://github.com/xxxx/YYYY.git
git push -u origin develop
```

## 创建新的分支
```
git branch release/1.0
git checkout release/1.0
git add .
git commit -m "create release branch"
git push origin release/1.0
```