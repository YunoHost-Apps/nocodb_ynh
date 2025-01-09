<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 NocoDB

[![集成程度](https://apps.yunohost.org/badge/integration/nocodb)](https://ci-apps.yunohost.org/ci/apps/nocodb/)
![工作状态](https://apps.yunohost.org/badge/state/nocodb)
![维护状态](https://apps.yunohost.org/badge/maintained/nocodb)

[![使用 YunoHost 安装 NocoDB](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nocodb)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 NocoDB。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

NocoDB is an open source NoCode platform that turns any database into a smart spreadsheet, alternative to Airtable.

* Connect to new/existing SQL database and turn them into spreadsheet
* Create grid view, gallery view, kanban view and calendar view on top your data
* Search, sort, filter columns and rows with ultra ease
* Invite your team with fine grained Access Control
* Share views publicly and also with password protection
* Provides REST & GraphQL APIs with Swagger & GraphiQL GUI


**分发版本：** 0.260.1~ynh1

**演示：** <https://www.nocodb.com/demos>

## 截图

![NocoDB 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://www.nocodb.com>
- 上游应用代码库： <https://github.com/nocodb/nocodb>
- YunoHost 商店： <https://apps.yunohost.org/app/nocodb>
- 报告 bug： <https://github.com/YunoHost-Apps/nocodb_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
或
sudo yunohost app upgrade nocodb -u https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
