# V2Ray Heroku

**若需部署 V2Ray VLESS，请转到 [vless](https://github.com/bclswl0827/v2ray-heroku/tree/vless) 分支。**

## 概述

## 部署

### 步骤

 1. Fork 本专案到自己的 GitHub 账户（用户名以 `example` 为例）
 2. 修改专案名称，注意不要包含 `v2ray` 和 `heroku` 两个关键字（修改后的专案名以 `demo` 为例）
 3. 修改 `README.md`，将 `bclswl0827/v2ray-heroku` 替换为自己的内容（如 `example/demo`）

> [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/bandtom/v2ray-heroku)

 4. 回到专案首页，点击上面的链接以部署 V2Ray

### 变量

对部署时需设定的变量名称做如下说明。

| 变量 | 默认值 | 说明 |
| :--- | :--- | :--- |
| `ID` | `ad806487-2d26-4636-98b6-ab85cc8521f7` | VMess 用户主 ID，用于身份验证，为 UUID 格式 |
| `WSPATH` | `/` | WebSocket 所使用的 HTTP 协议路径 |


