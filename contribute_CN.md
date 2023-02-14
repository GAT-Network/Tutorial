# 参与贡献

> 若以下内容太过晦涩难懂，难以实行，请注册登陆后进入[Issues](https://github.com/GAT-Network/Tutorial/issues)界面点击[New issue](https://github.com/GAT-Network/Tutorial/issues/new/choose)绿色按钮直接提交内容。

本教程源码开源托管在 Github 上，欢迎参与维护：[GAT-Network/Tutorial](https://github.com/GAT-Network/Tutorial)。

首先，在 GitHub 上 `fork` 到自己的仓库，如 `你的用户名/Tutorial`，然后 `clone` 到本地，并设置用户信息。

```sh
$ git clone git@github.com:GAT-Network/Tutorial.git
$ cd Tutorial
$ git config user.name "你的用户名"
$ git config user.email "你的邮箱"
```

更新内容后提交，并推送到自己的仓库。

```sh
$ #对内容进行修改后
$ git commit -am "Fix issue #1: change helo to hello"
$ git push
```

最后，在 GitHub 网站上提交 pull request 即可。

另外，建议定期使用项目仓库内容更新自己仓库内容。

```sh
$ git remote add upstream https://github.com/GAT-Network/Tutorial
$ git fetch upstream
$ git checkout master
$ git rebase upstream/master
$ git push -f origin master
```
