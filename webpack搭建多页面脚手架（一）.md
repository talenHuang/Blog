# 开始的开始
  步入前端已经一年多了，真心的体会到前端世界变化莫测，从jquery到vue，也算经历了一场大前端的变革。而在这几年，webapck的呼声越来越高。远超gulp，grunt等打包工具。平时使用vue-cli时用得biu顺，等到自己搭的时候就有点捉襟见肘了。
  # 项目的初始化
  使用`npm init`进行初始化操作 ，初始化界面会要求你输入对应的配置信息
```
package name: (demo-cli-blog)  //项目包名
version: (1.0.0)        //项目的版本
description: test       //项目的具体描述
entry point: (index.js) //项目的入口文件
test command:           //测试指令，默认为test
git repository:         //git的地址
keywords:               //关键词
author: talen           //作者信息
license: (ISC)          //证书号
```
填写完成后，文件目录里多出了一个json文件`package.json`：
```json
{
  "name": "demo-cli-blog",
  "version": "1.0.0",
  "description": "test",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "talen",
  "license": "ISC"
}
```
## 建立基本目录
在`demo-cli-blog`文件下建立如下目录：
![](./images/webpack目录)


  
  