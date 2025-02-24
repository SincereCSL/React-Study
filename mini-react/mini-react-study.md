## mini-react 学习
基于React开发的mini版，学习React的实现原理，实现了React的核心功能，包括JSX、虚拟DOM、Diff算法、组件化、生命周期等。
开发使用React 18版本
### 学习链接
1. [React官网](https://reactjs.org)
2. [React Github](https://github.com/facebook/react)
3. [React18 新特性尝试](https://juejin.cn/post/7080854114141208612)
4. [React18 新特性免费视频教程](https://www.bilibili.com/video/BV1qS4y1m7GY/?vd_source=b557654c3937a4afce8585b5144b1526)

## 项目结构
首先创建 mini-react 的文件夹，创建 demo（测试代码）、src（mini react 源码）。
- <img src="/mini-react/images/img.png" alt="项目结构" width="510" height="254">

demo 下的測试代码基于 vite，构建过程如下：

如何基于 Vite 启动一个 React项目
```
创建一个基于vite的名称为demo项目：yarn create @vitejs/app demo --template react
进入demo目录：cd demo
在demo下安装依赖：yarn
安装 react 的最新 rc 版本：yarn add react react-dom
启动：yarn dev
浏览器端打开 http://Localhost:3908/
```

####   
