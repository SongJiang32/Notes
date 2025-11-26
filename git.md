# How to use git upload your files?

1.首先在github个人主页创建自己的仓库，然后克隆到本地

```
git clone https://github.com/your-username/your-repo.git
```

2.把需要上传的代码放入刚才克隆的仓库，然后添加当前目录下所有变更的文件

```
git add .
```

3.提交更改并写入提交信息

```
git commit -m "你的提交描述"
```

4.推送更改到 GitHub 仓库,-u 参数表示将本地的 main 分支与远程仓库的 main 分支进行关联

```
git push -u origin main
```

5.输入 GitHub 用户名和 Token

> 生成 GitHub Personal Access Token (PAT)：
>
> 登录 GitHub 后，点击右上角的头像，选择 Settings。
>
> 在左侧菜单选择 Developer settings，然后选择 Personal access tokens。
>
> 点击 Generate new token，并设置你需要的权限（例如 repo 权限用于访问私有仓库）。
>
> 生成后，复制这个 Token 并保存在安全的地方。
