# mail list 

## 前言
> 最近在学习vue，就写了一个简易的SPA通讯录项目，该项目用了
> - vue 
> - vue-router
> - vuex
> - axios
> -  localStorage
> - sessionStorage
> 
> 写这个项目之前我用vue写过很多小的页面部件，比如选项卡、路由跳转之类的，但毕竟这些涉及的知识是零散的，当系统的学习了之后我就想做一个整体性的项目，一方面巩固知识一方面打通经脉，所以就写了这个通讯录。
>
> 目前这个项目只是实现了大概结构，其实它的可扩展性很高，比如后期可以用node写一个后台与之交互，用vuex状态管理等等，后期我会一直维护，完善以及优化项目，也会根据需求增添个别功能，学vue的朋友也可以clone下来练练手。
>
>从零出发完成一个SPA。


## 动图展示
![](https://github.com/windlany/mail_list/blob/master/static/img/mailList.gif)

## 运行项目
```bash
# clone项目到本地
git clone https://github.com/windlany/mail_list.git

# 安装项目依赖
npm install

# 将项目部署在localhost:8080，运行一下命令打开浏览器的localhost:8080查看
npm run dev 
```

## 后期完善的地方
> 由于该项目耗时较短只是写了大概的功能，很多细节需要完善与修正，我也会持续跟进完善的
> - vuex状态管理
> - 添加node后台与之交互
> - sessionStorage

## v.1
#### 2017.12.21
- vue
- vue-router
- localStorage
- axios

## v.2
#### 2017.12.23
- 登录注册界面vuex
- <del>localStorae</del>
- <del>axios</del>
- sessionStorage缓存用户信息以及已登录用户信息
- 仅支持单用户注册

## v.3
#### 2017.12.24
- 完善登录注册界面的vuex
- localStorage缓存用户信息，sessionStorage缓存当前登录用户信息
- 支持多用户注册
