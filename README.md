项目介绍
============

一个用Node.js编写的Web安全测试框架

a Web security tool written by NodeJs.


测试方法
============
安装依赖
------------

```
npm install
```

启动环境
-----------
```
npm test
```

打开新的命令行执行测试用例
-----------

测试爬虫模块

```
npm run spider
```

测试持久型XSS扫描模块

```
npm run stored-xss
```

测试反射型XSS扫描模块

```
npm run reflected-xss
```

测试C++扩展

```
npm run cpp-addon
```

description(项目背景介绍)
------------------
[official website(官方文档)](http://www.zhuyingda.com/docs/veneno.html)

# PS：体检结果总结：
-- 1. Node 能够启动，附带一个标本页面
-- 2.XSS扫描结果不理想
-- 3. C++扩展没体验
