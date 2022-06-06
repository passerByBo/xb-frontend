互相引用

pnpm add -w koa 两个包都可以使用

pnpm publish

搭建私仓  pm2 start verdaccio

私仓安装到ECS


"useWorkspaces": true, 配置完成后lerna用处就不大了

lerna和pnpm相辅相成

verdaccio 前台进程 方便调试 pm2 start -i -max

.config全局配置下找到verdaccio shared npm私仓的缓存文件 config.yaml私仓的配置文件 自己使用的一些包会缓存

4873的端口对外开放

lerna add  将私仓中的包添加到packages下

pnpm workspaces

pnpm add microboundle -W 底层使用的rollup

没上线前 调试

pnpm dev 直接执行所有的packages下的命令 只需要父级安装一次microboundle

home引入core  lerna add @xb/core packages/home

npm i bbt npm:koa 起别名

pnpm workspace

pnpm publish 的时候自动会去除workspaces

lerna add 和pnpm add的方式 都可以支持开发  publish的时候会有问题 加了workspace只能一个一个的进行publish