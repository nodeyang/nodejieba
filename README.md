# NodeJieba Jieba中文分词的node版本

## 概述

NodeJieba只是[CppJieba]简单包装而成的node扩展，用来进行中文分词。

## 安装和使用

`npm install nodejieba`

## 使用实例

```sh
mkdir nodejieba_test
cd nodejieba_test
npm install nodejieba

echo "var segment = require(\"nodejieba\");
segment.loadDict(\"./node_modules/nodejieba/dict/jieba.dict.utf8\", \"./node_modules/nodejieba/dict/hmm_model.utf8\");
console.log(segment.cut(\"你好世界\"));" > index.js

node index.js
```

## 测试

在`node v0.10.2`下测试通过

## 演示

http://cppjieba-webdemo.herokuapp.com/

## 鸣谢

[jieba中文分词](https://github.com/fxsjy/jieba)

## 客服

wuyanyi09@gmail.com

[blog1]:http://aszxqw.github.io/jekyll/update/2014/01/23/nodejs-chu-ti-yan.html
[CppJieba]:https://github.com/aszxqw/cppjieba.git
