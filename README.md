# tech blog@**jerry**
- Our team's technology blog inherits the spirit of Admiral Yi Sun-sin of Joseon

### Connecting
- PRD - https://
- STG - https://

### Contribute guide
- Anyone can do it's possible. Let's send the PR first and make it a better team by joining.

0. created based on [vuepress](https://v2.vuepress.vuejs.org/)
1. git clone git@github.com:vhzkclq0705/jerry.github.io.git
2. edit with [vscode](https://code.visualstudio.com/)
3. install
``` bash
brew install node
brew install pnpm
```
4. run - development environment [install pnpm](https://pnpm.io/installation)
- connecting to localhost 8080
- node.js install if you have get error 'ELIFECYCLE Command failed'
```bash
$ nvm ls
$ nvm use v22.13.0
$ node -v
v22.13.0
$ pnpm install
$ pnpm docs:dev
-> Local: http://localhost:8080/
```

### build & deploy
1. STG
- [x] 배포전 작업 파일은 모두 커밋!
- [install firebase](https://v2.vuepress.vuejs.org/guide/deployment.html#google-firebase)

``` bash
$ git add .
$ pnpm docs:build
$ firebase login
$ firebase deploy
```

2. PRD
- github pages -> docs
- sh prd-build.sh -> push -> pr merge -> deploy - end
- https://oss.cashmallow.com

<img src="https://user-images.githubusercontent.com/120996497/212484360-1b212db0-5a5c-449f-8cc2-35de2126bd66.png" alt="cashmallow" style="width:600px;"/>
<img src="https://oss-cashmallow.github.io/images/hero.png" alt="cashmallow" style="width:200px;"/>
