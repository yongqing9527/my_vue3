# my_vue3
## 创建一个vue3 文件
    npm install -g @vue/cli
    vue create hello-world
## 添加一些文件
    vue add router
    vue add vuex
## 快速原型开发
    npm install -g @vue/cli-service-global
    vue serve    不好用
## 预处理器
    npm install -D sass-loader node-sass
    npm install -D less-loader less
    npm install -D stylus-loader stylus
## index.html引用静态资源
    <link rel="icon" href="<%= BASE_URL %>favicon.ico">
    <link rel="preload"> 首先要加载的资源，如：rem.js     
    <link rel="preload" href="./publicYD.css" as="style">
    <link rel="preload" href="./rem.js" as="script">
    <link rel="prefetch"> 用来告诉浏览器在页面加载完成后，利用空闲时间提前获取用户未来可能会访问的内容。
## 打包
    npm run build
    本地预览 dist文件
    npm install -g serve
    # -s 参数的意思是将其架设在 Single-Page Application 模式下
    # 这个模式会处理即将提到的路由问题
    serve -s dist
