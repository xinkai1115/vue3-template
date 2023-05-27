# vue3 template

一个 Vue3 + TS + Vite + Element-Plus 开箱即用的企业级开发模板。


## 🎉有点用的小特性

1. 这个是 **Vue3.2**的模板
2. 支持 **Vite**
3. UI框架是 **Element-Plus** 它已经支持暗黑模式
4. CSS框架是 **TailwindCSS**
5. 状态管理是 **Pinia**
6. **ESlint+Prettier** 已经配置完成
7. Git **提交前验证**以及**提交规范**已做好
8. 封装的**比较完善**的 axios，有一丢丢的学习成本
9. Vue 和 VueRouter 的 API 自动引入，你还可以配置更多的 API 自动引入
10. 封装了一个 `useRequest`，让接口请求变得更加简单
11. 自带一个基础版本的动态路由，可以用作参考
12. 这个模板比较干净，需要你删除的的东西很少，也就是说需要自己编写的很多

## ✨启动项目

这里我使用的包管理工具时npm，node版本大于 `16.9.0`。使用 npm 的主要原因是适应大多数人，毕竟 yarn 和 pnpm 需要安装，也是有些学习成本的；如果介意可以自行更换包管理工具。

现在开始正式启动这个项目

1. 安装依赖
```bash
npm install # 或者 npm i 或者 yarn
```
2. 开发过程
```bash
npm run dev # 运行

npm run dev:open # 自动打开浏览器
npm run dev:host # 添加 --host

npm run dev:host:open # 自动打开浏览器并添加 --host

```
3. 打包编译

```bash
npm run build
```
4. 预览

```bash
npm run preview
```
5. lint代码并格式化

```bash
npm run lint
```