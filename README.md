# test_easy_npm
test_easy_npm

{toc}
h2. 测试使用

h3. 创建测试项目test_easy_npm

h3. 安装依赖

h4. 手动安装指定包
{code}npm install easy_npm{code}

h4. 配置package.json 依赖

参考: {code} http://ju.outofmemory.cn/entry/130809 {code}

{code}
 "dependencies" : {
   "easy_npm":  "^0.1.0"
 }
{code}

h3. 调用

{code}
'use strict'

var NpmTest  = require('easy_npm');

console.log(new NpmTest().greet());
{code}



h2. 升级依赖包

h3. 手动升级指定包

{code}npm update easy_npm@0.1.2{code}

h3. 配置package.json 项目依赖

{code}npm update {code}

