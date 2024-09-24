<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Tor relay

[![集成程度](https://dash.yunohost.org/integration/torrelay.svg)](https://ci-apps.yunohost.org/ci/apps/torrelay/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/torrelay.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/torrelay.maintain.svg)

[![使用 YunoHost 安装 Tor relay](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=torrelay)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Tor relay。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

The Tor network relies on volunteers to donate bandwidth. The more people who run relays, the better the Tor network will be. The current Tor network is quite small compared to the number of people who need to use Tor, which means we need more dedicated volunteers like you to run relays.

**分发版本：** 0.4.8.12~ynh1
## 文档与资源

- 官方应用网站： <https://www.torproject.org/>
- 官方管理文档： <https://community.torproject.org/relay/setup/bridge/debian-ubuntu/>
- 上游应用代码库： <https://github.com/torproject/tor>
- YunoHost 商店： <https://apps.yunohost.org/app/torrelay>
- 报告 bug： <https://github.com/YunoHost-Apps/torrelay_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing --debug
或
sudo yunohost app upgrade torrelay -u https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
