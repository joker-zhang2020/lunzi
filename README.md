# 轮子 -  一个 Vue UI 组件

[![Build Status](https://travis-ci.org/joker-zhang2020/lunzi.svg?branch=master)](https://travis-ci.org/joker-zhang2020/lunzi)

## 介绍
    此款 UI 框架由 Vue 制作完成，并不断扩充，经常更新。
## 开始使用
1. 添加 CSS 样式
使用本框架前，请在CSS中开启 border-box
```css
*,*::before,*::after{box-sizing:border-box}
```
IE 8 及以上浏览器都支持此样式

你还需要设置默认颜色等变量（后续会改为SCSS变量）
```scss
html{
     --button-height:32px;
     --font-size:14px;
     --button-bg:white;
     --button-active-bg:#eee;
     --border-radius:4px;
     --color:#999;
     --border-color:#999;
     --border-color-hover:#666;
}
```
IE 15 及以上浏览器都支持此样式
2. 安装 lunzi
```
npm i --save lunzi
```
3. 引入 lunzi
```js
import {Button,ButtonGroup,Icon} from 'lunzi-2020.8.9'
import 'lunzi-2020.8.9/dist/index.css'

export default{
    name:'app',
    components:{
    'g-button':Button,
    'g-icon':Icon    
    }
}
```

## 文档

## 提问

## 变更记录

## 联系方式

## 贡献代码

