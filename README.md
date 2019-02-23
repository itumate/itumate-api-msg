# keeper-api-msg

keeper-app-msg 客户端 Api；

当前版本 `v0.0.1-SNAPSHOT`，该版本号与 `keeper-app-msg` 版本同步对应

使用该 api 需要在 pom 中引入：

```xml
<dependency>
    <groupId>${parent.groupId}</groupId>
    <artifactId>keeper-api-msg</artifactId>
    <version>${keeper.msg-api.version}</version>
</dependency>
```

**注意：** `groupId` 不需要该变，该 `groupId` 即为项目 `parentId`，会自动注入变量。只需要修改对应 `version` 即可`;

主在配置文件中若不增加 `keeper.app.msg` 配置会默认使用 `msg-v1` 服务（当前 `keeper.app.msg` 服务最新版本为 `v1`）。