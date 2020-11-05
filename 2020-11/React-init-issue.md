# React init issus

* 无法使用 create-react-app 初始生成项目：
    * 主要原因是 node 版本过低，造成初始化失效。这里忘记截图了。
      解决方案 - 升级 node 至 10.14.2 后使用 npx create-react-app

* npx create-react-app 后无 src 目录：
    * create-react-app 脚手架版本过低，需要升级版本。需要先删除旧版的create-react-app，再重新安装。
        1. 删除旧版
            npm uninstall -g create-react-app          yarn global remove create-react-app
        2. 重新安装create-react-app
            npm i -g create-react-app
        3. 使用官网提供的脚手架工具创建React App
            npx create-react-app test 

