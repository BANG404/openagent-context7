# context7 for OpenAgent

Current library documentation through Context7.

Install the release archive through OpenAgent Integrations → Plugins. This is an independent adaptation.

## Setup

- Network access to mcp.context7.com; authorize if the service requests it.

Run /context7:setup. Package state and credentials belong in the active OpenAgent home at plugin-data/context7/. Never place secrets in plugin.json or commit them. Refresh the plugin after changing credentials.

## Verification

bun test tests

Bundled tests cover immutable artifacts, config conversion and service configuration and missing prerequisites. Runtime acceptance also verifies a real staged installation, slash-command catalog and integration_status. External account authentication, real provider operations and macOS permissions require the prerequisites above; package tests do not claim those credentials are available.

## 中文

通过 Context7 查询最新的库文档。 安装发布包后运行 /context7:setup 查看配置要求。凭据和状态保存在当前 OpenAgent 数据目录的 plugin-data/context7/ 下，修改后刷新插件。

Upstream source and exact revision are recorded in provenance.json. Bundled source remains available for inspection.
