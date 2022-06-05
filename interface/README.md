1. npm i
2. 内容寻址 hardlink硬链和软链,软链相当于复制了一份文件，硬链接直接指向原来的文件
3. 支持monorepo（仓库）独立发包安装公用文件、packages中开发了四个项目 四个项目相互依赖 支持workspace协议 支持直接链接到私仓上的文件
4. 包的安全 A->B->C 非法访问依赖  A直接访问C  依赖提升  A依赖B装了BB依赖CB中有C

'别名':"workspace":npm:koa^3.x.x

npm alicas别名

@types/** 下的包救不出来  独立安装包pnpm i再次安装 可以将包强行拆出来

pnpm的命令和learn的命令基本一致

lerna publish  pnpm publish

pnpm i/add koa 都支持

lerna可以独立发包pnpm不可以 changes可以感知到

