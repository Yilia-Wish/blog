1. 报错 refusing to merge unrelated histories
    * 原因： 本地与远端本就是两个独立仓库， 故而 git 拒绝 push / pull (此处我先前做的是本地重新 git init 了一次)
    * 解决： git pull origin master --allow-unrelated-histories