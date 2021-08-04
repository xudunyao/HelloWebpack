1:安装
    1.1可以通过npm安装，webpack提供了两个包第一个包为webpack,第二个为webpack-cli.
2:使用
    shell命令 webpack 
    webpack 会以./src/index.js作为入口文件分析依赖关系，打包到./dist/main.js
    --mode 可以控制webpack的打包结果的运行环境
    --mode development 开发环境
    --mode production  上线环境