### 因为用html 有很多的局限，所以需要安装vue
    * 在vue 里面有一个很好的工具可以帮助我们 也就是vue-cli vue 脚手架
    * 需要安装最新版本的node.js
        1. 然后就会有npm功能 命令：npm install -g @vue/cli
        2. 看vue的版本 vue  --version
        3. 创建一个vue的项目 ： vue create hello-world 选择default 然后就会安装 vue的依赖包
        4. main.js 是入口文件
    * 在html 使用vue的缺点
        1.里面组件是全局定义的
        2. 字符串模版 template 里面的内容没有高亮，会发现不出问题
        3.不支持在里面写css
        4.没有构建的step 如build 一个项目的步骤 不能兼容低版本的浏览器
