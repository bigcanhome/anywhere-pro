# pro

在[anywhere](https://www.npmjs.com/package/anywhere)基础上可在root下创建 `.proxyrc.js` 

``` js
module.exports = {
  'proxy': {
    '/xxx': {
      target: 'http://xxx.com',
      secure: false,
      changeOrigin: true,
    }// /xxx -> http://xxx.com/xxx
  }
}
```

将 `connect` 替换成了 `express` 增加了 `http-proxy-middleware`

全局安装

```
npm i anywhere-pro -g
```

在项目中使用

```
anywhp 80
```

随便下载和提意见，一起学习