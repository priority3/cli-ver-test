## npm 本地发布包

#### verdaccio
[npm地址](https://www.npmjs.com/package/verdaccio)
```sh
// 全局安装
npm install -g verdaccio
```
将自己的npm 仓库设置到启动的本地仓库上
```sh
nrm add  local http://localhost:4873/
nrm use local
```
之后去执行 npm publish 即可


#### release-it
传统的更新包之后需要commit打一个tag然后推送到github然后远端再手动release一下

