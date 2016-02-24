## 测试使用

### 创建测试项目test_easy_npm

### 安装依赖

#### 手动安装指定包
```
npm install easy_npm
```

#### 配置package.json 依赖

参考:

[参考文档](link "http://ju.outofmemory.cn/entry/130809")



```javascript
 "dependencies" : {
   "easy_npm":  "^0.1.0"
 }
```

### 调用

```javascript
'use strict'

var NpmTest  = require('easy_npm');

console.log(new NpmTest().greet());
```



## 升级依赖包

### 手动升级指定包

```
npm update easy_npm@0.1.2
```

### 配置package.json 项目依赖

```
npm update
```
