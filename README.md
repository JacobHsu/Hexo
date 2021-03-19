# hexo

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
