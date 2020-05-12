# DataStructuresAndAlgorithms
学习《极客时间》王争的《数据结构与算法》的代码记录



#### Git全局设置
```shell
git config --global user.name  "***"
git config --global user.email "*****s@git.weixin.qq.com"
```

#### 创建一个新的版本库
```shell
git clone git@git.weixin.qq.com:minitest/minium-issue.git
cd minium-issue
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
```


#### 现有的文件夹或Git版本库
```shell
cd existing_folder
git init
git remote add origin git@git.weixin.qq.com:minitest/minium-issue.git
git add .
git commit
git push -u origin master
```

