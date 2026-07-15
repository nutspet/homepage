# 寻狗企业官网

这是一个纯静态 Vue 企业网站，主题围绕科技、宠物与 AI，包含首页、关于我们、我们的产品、团队成员模块，并已加入备案号 `沪ICP备18044132号-1`。

## 本地预览

```bash
npm install
npm run dev
```

浏览器访问：

```text
http://localhost:801
```

## 构建静态资源

```bash
npm run build
```

构建结果会输出到 `dist` 目录。

## Docker 部署

```bash
docker build -t ai-nutspet-site .
docker run -d --name ai-nutspet-site -p 801:801 ai-nutspet-site
```

部署后访问：

```text
http://localhost:801
```
