# Cordova 开发整理(基于macOS)

##安装Node.js
1. 下载和安装：[Node.js](https://nodejs.org/en/download/)，安装完成后即可在终端（Windows 为命令行）中使用*node* 和 *npm*；

2. 由于Node.js 镜像在国内访问较慢，故我们将Node.js 设置为阿里源：
    ```
    npm config set registry https://registry.npm.taobao.org --global
    npm config set disturl https://npm.taobao.org/dist --global
    ``` 
3. 安装Cordoba CLI：

    ```
    sudo npm install -g cordova
    ```
   
##创建一个新项目
 1. 初始化项目：
    
    ```
    cordova create cordovademo com.demo.cordova CordovaDemo
    ```
 2. 添加平台：
    
    ```
    cd cordovademo
    cordova platform add android --save
    ```
    检查平台是否添加：
    
    ```
    cordova platform ls
    ```
 3. 编译工程并运行：
    
    ```
    cordova build android
    cordova run android
    ``` 
    
##调用原生模块    
    
    

    

