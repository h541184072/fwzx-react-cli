<h1 align="center">Ant Design Pro</h1>

- 预览：http://preview.pro.ant.design
- 首页：http://pro.ant.design/index-cn
- 使用文档：http://pro.ant.design/docs/getting-started-cn
- 更新日志: http://pro.ant.design/docs/changelog-cn
- 常见问题：http://pro.ant.design/docs/faq-cn
- 国内镜像：http://ant-design-pro.gitee.io

## 代码目录
```js
+-- dist /                                  ---打包的文件目录
+-- config/                                 ---npm run eject 后的配置文件目录
+-- scripts/                                ---npm run 脚本文件
+-- src/                                    ---核心代码目录
|   +-- action                              ---action type
|   +-- assets                              ---静态文件
|   +-- components                          ---各式各样的组件存放目录
|   |    +-- Exception                      ---404组件
|   |    |    --- ...
|   |    +-- PageLoading                    ---Loading
|   |    |    --- ...
|   +-- public_store                        ---store
|   |    --- index.js
|   +-- reducer                             ---reducer
|   +-- router                              ---Router
|   +-- services
|   |    --- api.js                         ---http请求存放目录
|   +-- utils
|   |    --- request.js                     ---request方法
|   |    --- utils.js                       ---通用方法
|   --- App.jsx                             ---组件入口文件
|   --- index.js                            ---项目的整体js入口文件，包括路由配置等
--- .eslintrc                               ---自定义eslint配置文件，包括增加的react jsx语法限制
--- babel.config.js                         ---babel配置
--- package.json
```

## 模板

```
- Dashboard
  - 分析页
  - 监控页
  - 工作台
- 表单页
  - 基础表单页
  - 分步表单页
  - 高级表单页
- 列表页
  - 查询表格
  - 标准列表
  - 卡片列表
  - 搜索列表（项目/应用/文章）
- 详情页
  - 基础详情页
  - 高级详情页
- 用户
  - 用户中心页
  - 用户设置页
- 结果
  - 成功页
  - 失败页
- 异常
  - 403 无权限
  - 404 找不到
  - 500 服务器出错
- 帐户
  - 登录
  - 注册
  - 注册成功
```

## 使用

### 使用命令行
```bash
$ npm install
$ npm start         # 访问 http://localhost:8000
```

### 使用 docker

```bash
# preview
$ docker pull chenshuai2144/ant-design-pro
$ docker run -p 80:80 chenshuai2144/ant-design-pro
# open http://localhost

# dev
$ npm run docker:dev

# build
$ npm run docker:build


# production dev
$ npm run docker-prod:dev

// production build
$ npm run docker-prod:build
```

更多信息请参考 [使用文档](http://pro.ant.design/docs/getting-started)。

## 支持环境

现代浏览器及 IE11。

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Opera |
| --------- | --------- | --------- | --------- | --------- |
| IE11, Edge| last 2 versions| last 2 versions| last 2 versions| last 2 versions

