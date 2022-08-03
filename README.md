### 分支

分支仅仅是提交对象(提交指针)，当你创建一个新的分支时，git没有重新创建所有文件或者文件夹，仅仅创建了一个新的指针

#### 创建分支

```bash
git branch future-plans
```

该命令仅仅创建分支，并没有切换到该分支

仓库的历史记录没有改变，

#### 切换分支

```bash
git checkout future-plans
```

