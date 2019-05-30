### eslint和tslint在cocos-creator中的使用

#### 为什么需要eslint和tslint

因为js、ts的表现力强，可以采用一些工具来约束、规范代码，比如js有`jslint`,`jshint`,`eslint`等，本文只介绍`ESLint`、`TSlint`的在vscode、webstorm中安装使用。

eslint和tslint是在js、ts代码中识别和报告模式匹配的工具，目的是保证代码的一致性和避免一些陷阱。

好处有以下几点：

* 保证代码风格的统一

* 有建议提示，让你更好的理解和使用js、ts

------

#### 安装nodejs

[菜鸟教程Node.js安装配置](https://www.runoob.com/nodejs/nodejs-install-setup.html)

#### eslint的安装和配置

##### 安装

[ESLint中文网站](https://cn.eslint.org/)

在这里我推荐的使用[AlloyTeam ESLint](https://github.com/AlloyTeam/eslint-config-alloy)的配置规范

安装：

``` powershell
npm install eslint -g
```

在你的项目根目录下创建 `.eslintrc.js`，并将以下内容复制到文件中：

把该项目的`.eslintrc.js `放到项目的根目录下

#### tslint的安装和配置

[TSlint官网](https://palantir.github.io/tslint/)

在这里一样也是推荐[AlloyTeam TSLint ](https://github.com/AlloyTeam/tslint-config-alloy)的配置

安装：

```
npm install tslint -g
```

把该项目中 `tslint.json` 文件放到项目的根目录下

#### 在vscode和webstorm中使用

##### vscode

在vscode的插件中心分别搜索ESLint和TSLint

![1559187234398](assets\1559187234398.png)

##### webostrom

tslint:

![1559199239156](assets\1559199239156.png)

eslint:

![1559200269558](assets\1559200269558.png)



[AlloyTeam ESLint 规则](https://alloyteam.github.io/eslint-config-alloy/)