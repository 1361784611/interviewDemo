* Echarts的基本了解
```
Echarts底层依赖轻量级的Canvas类库ZRender,zRender这个库使用的是mvc结构,分别对应三个js
```
* esLint规范
```
https://calpa.me/2017/11/08/you-dont-know-javascript-eslint-config/
https://github.com/AlloyTeam/eslint-config-alloy#react

esLint规范分为下面这几种：
1、Airbnb,它差不多包含所有javaScript的角度.如果众多的项目是基于React,
  那么可以选择安装eslint-config-airbnb(包含ECMAScript 6 + React代码检查规范),
  或者选择最基本的eslint-config-airbnb-base(这个是通用的包含ECMAScript代码检查规范)
2、standard,选择安装eslint-config-standard
```
*javascript中的require、import和export人区别
```
 nodejs就遵循CommonJS规范 使用module.exports和exports暴露模块 使用require加载模块
  function hello() {
    console.log('Hello, world!');
  }

  function world(name) {
    console.log('Hello, ' + name);
  }
  //区别
  module.exports = {
      hello: hello,
      world: world
  };

  exports.hello = hello;
  exports.world= world;

---------------------

 ES6标准 使用exprot导出 import引入
```