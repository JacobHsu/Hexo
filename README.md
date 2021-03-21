# hexo

\hexo\doc> `npm i`  
\doc> `hexo s`  

INFO  Hexo is running at http://localhost:4000 . Press Ctrl+C to stop.


## setup

```s
$ hexo init <folder>
$ cd <folder>
$ npm install
```
## _config.yml

```s
# Deployment
## Docs: https://hexo.io/docs/one-command-deployment
deploy:
  type: git
  repository: https://github.com/JacobHsu/hexo
  branch: gh-pages
```

## deploy

```js
ERROR Deployer not found: git
`npm install hexo-deployer-git --save`  

`$doc> hexo g`
`$doc> hexo d`
```

## 在Hexo使用Next Theme

Next Theme clone一份下來.`git clone https://github.com/theme-next/hexo-theme-next.git`
在/themes/ 建立一個 `next` 資料夾並把Next Theme所有檔案copy進去.
修改Hexo _config.yml檔案，把theme改成`next`

`theme: landscape`
`theme: next`