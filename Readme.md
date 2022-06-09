## 安装Node.js

1、到node官网下载node.js，网址：https://nodejs.org/download/release/ ，下载需要的版本（本项目使用的是16.15）
 
2、下载完成后，双击“node-v11.5.0-x64.msi”，开始安装Node.js

3、配置环境变量。在安装的文件夹`D:\Develop\nodejs`下创建两个文件夹`node_global`及`node_cache`，执行命令

```
npm config set prefix "D:\Develop\nodejs\node_global"
npm config set cache "D:\Develop\nodejs\node_cache"
```

打开“我的电脑”-右键-“属性”-“高级系统设置”-“高级”-“环境变量”，进入环境变量对话框，在`系统变量`下新建`NODE_PATH`，输入`D:\Develop\nodejs\node_global\node_modules`，将`用户变量`下的`Path`修改为`D:\Develop\nodejs\node_global`

4、测试。配置完后，安装最常用的express模块进行测试，打开cmd窗口输入如下命令进行模块的全局安装：

```
npm install express -g     # -g是全局安装的意思
```

## 下载安装ganache
下载地址https://trufflesuite.com/ganache/

