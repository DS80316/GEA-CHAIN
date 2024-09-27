#基伊埃
绿色地球行动(GEA)链是一个模块化的区块链开源软件，旨在推动全球环境保护工作。它基于结合了授权证明(PoA)和利益证明(PoS)的双重共识机制运行，并在其之上建立了一个对等(P2P)网络。还包括基于该模块化区块链框架的P2P网络的构建。

##开始

```
点燃链式发球
```

`服务`命令安装依赖项，构建、初始化并启动开发中的区块链。

###安装ˌ使成形

您正在开发的区块链可以配置为`config.yml`。要了解更多信息，请参阅[Ignite CLI文档](https://docs.ignite.com).

###Web前端

Ignite CLI在中搭建了一个基于Vue.js的web应用程序`某视频剪辑软件`目录。运行以下命令安装依赖项并启动应用程序:

```
CD 视图
npm安装
npm运行服务
```

前端应用程序是使用`来源:starport/vue`和`来源:starport/vuex`包裹。有关详细信息，请参见[用于Ignite前端开发的monorepo](https://github.com/ignite/web).

##释放；排放；发布
要发布您的区块链的新版本，请创建并推送一个新标签`v`前缀。将创建一个包含已配置目标的新发布草稿。

```
git tag v0.1
git push origin v0.1
```

After a draft release is created, make your final changes from the release page and publish it.

### Install
To install the latest version of your blockchain node's binary, execute the following command on your machine:

```
curl https://get.ignite.com/username/gea-poa@latest! | sudo bash
```
`username/gea-poa` should match the `username` and `repo_name` of the Github repository to which the source code was pushed. Learn more about [the install process](https://github.com/allinbits/starport-installer).

## Learn more

- [Ignite CLI](https://ignite.com/cli)
- [Tutorials](https://docs.ignite.com/guide)
- [Ignite CLI docs](https://docs.ignite.com)
- [Developer Chat](https://discord.gg/ignite)
