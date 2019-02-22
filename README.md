# zhwl
a cli for zhwl

## Develop
```shell
node -v
#v8.9.3
npm -v
#5.6.0
```

## Installation

Using npm:

```shell
npm install -g zhwl-cli
zhwl init <project name>
# 指定初始化仓库
zhwl init <project name> -r huomarvin/react-koa2-ssr
# 针对公司内网情况，增加-t参数，可配置初始化仓库为gitlab
zhwl init <project name> -t gitlab -r <gitlab address>
# 项目更新功能
zhwl update
```

Update zhwl:

```shell
npm update -g zhwl
```
参考[如何更新全局安装的包](https://www.npmjs.com.cn/getting-started/updating-global-packages/)









