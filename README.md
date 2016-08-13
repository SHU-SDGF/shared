
# 前后端开发人员都需要安装
## npm
 npm 是目前最流行的程序依赖集管理。在隧道股份的项目中，无论前端还是后端都会用到npm作为辅助开发的重要部分。但是同学们不需要了解npm的细节的内容，但是干嘛用的还是要需要有个概念的。下面第一个链接是简介，第二个链接是下载地址。请同学自行选择适合自己操作系统的版本下载。
    
    npm主页：https://www.npmjs.com/（安装完成npm以后，nodejs也会附带安装完成）

在npm安装完成之后，在命令行中输入node -v的指令查看版本号。请使用5以上的版本的nodejs。


上述过程如果没有遇到问题，请在命令行中输入下列指令``安装淘宝镜像``：
```
alias cnpm="npm --registry=https://registry.npm.taobao.org \
--cache=$HOME/.npm/.cache/cnpm \
--disturl=https://npm.taobao.org/dist \
--userconfig=$HOME/.cnpmrc"
```

如果有问题请查阅下列资料：

    npm介绍： http://www.runoob.com/nodejs/nodejs-npm.html
    淘宝镜像：https://npm.taobao.org/

# 前端人员请阅读
## ES6
老版本的javascript写法我就不细说了，请自行百度搜索W3C javascript
ES6是最新的JavaScript版本，我们在项目当中会使用ES6的语法进行开发。
es6的coding style 详细资料请阅读 https://github.com/elierotenberg/coding-styles/blob/master/es6.md


## Typescript
Typescript是ES6版本的JavaScript的超集，是我们在项目中的主要开发语言。详细介绍请见http://tslang.cn/docs/tutorial.html

## Ionic 2
Ionic 2是使用JavaScript开发移动端应用的框架。它能给JavaScript访问本地硬件的接口。它最大的特点是一套代码可以在网页上跑，也可以打包成APP跑在任何移动端。
    
    官方网站： http://ionic.io/2
    
    安装请详见： http://ionicframework.com/docs/v2/getting-started/installation/
    
    详细开发文档： http://ionicframework.com/docs/v2/components/#alert

## Angular 2
Angular 2是一个前端组件化开发的库。Ionic 2全面使用Angular 2作为组件化引擎。

官方网站https://angular.io/

## SCSS
SCSS是css的超集，语法类似于css。SCSS经过解释器tranpile后会输出css。比如：
```css
/* scss */
.main-component{
    .sub-component-1{
        background: red;
    }
    .sub-component-2{
        background: black;
    }
}
/* 编译后 */
.main-component .sub-component-1{
    background: red;
}
.main-component .sub-component-2{
    background: black;
}
```

# 后端人员请阅读
安装请见：http://installrails.com/
