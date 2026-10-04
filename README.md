# 梦之韵Pro 轻量 API 仓库

梦之韵Pro 启动器的静态 JSON 数据源，托管于 GitHub raw，可配 jsDelivr 加速。所有文件均为公开只读，**请勿存放任何敏感信息**（密码 / API Key / 凭据）。

## API 列表

| 文件 | 用途 | 启动器接口 |
|---|---|---|
| `changelog.json` | 更新日志 | `{ApiBase}/changelog.json` |
| `server.json` | 服务器信息 / 公告 | `{ApiBase}/server.json` |
| `launcher.json` | 启动器自身更新检查 | `{ApiBase}/launcher.json` |
| `mods/modlist.json` | 模组更新清单（带 sha256 校验） | `{ApiBase}/mods/modlist.json` |
| `packs/packs.json` | 整合包清单 | `{ApiBase}/packs/packs.json` |

## 访问地址

- GitHub raw：`https://raw.githubusercontent.com/maoxinhe/mzy-api/main/<文件>`
- jsDelivr 加速：`https://cdn.jsdelivr.net/gh/maoxinhe/mzy-api@main/<文件>`

## 更新方式

**推荐使用网页后台**（`梦之韵Pro-API后台.html`）编辑并一键提交，或直接改文件后 `git push`。

## 安全约定

- 模组 / 整合包必须附带 `sha256`，启动器下载后校验，防清单被篡改导致分发恶意文件。
- 公开仓库内容对所有人可见，严禁放入任何敏感凭据。
