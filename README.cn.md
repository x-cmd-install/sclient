# sclient

[English version](./README.md)

Secure Client for exposing TLS (aka SSL) secured services as plain-text connections locally. Also ideal for multiplexing a single port with multiple protocols using SNI.

![sclient](https://repo.x-cmd.io/sclient.svg?lang=zh)

## 安装

```sh
x install sclient
```

## 代码洞察

合计: **277** 行代码（覆盖前 5 种语言、共 **8** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 260 | 66 | 38 | 3 |
| Bitbake | 10 | 1 | 0 | 1 |
| Sh | 7 | 3 | 4 | 3 |
| Markdown | 0 | 97 | 48 | 1 |

## OpenSSF Scorecard 评分

总评分: **3 / 10**

评分最低的几项:

- **Code-Review** (0/10) — Found 0/28 approved changesets -- score normalized to 0
- **Packaging** (-1/10) — packaging workflow not detected
- **Dangerous-Workflow** (-1/10) — no workflows found

## 源代码

- **上游仓库**: <https://github.com/therootcompany/sclient>
- **官网**: <https://webinstall.dev/sclient>
- **许可证**: NOASSERTION

## 发布

- **最新版本**: `v1.5.1` (2025-09-17)
- **最近提交**: 2025-08-06
- **Release 含资产**: 13 个

## 流行度

- **Star**: 20 · **Fork**: 2 · **开放 issue**: 3 · **贡献者**: 2

## 累计统计

- **发布数**: 6 · **已合并 PR**: 2 · **开放 PR**: 3 · **已关闭 issue**: 2 · **开放 issue**: 1 · **提交数**: 32

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-15 | 0 | 0 | 2 | 0 | 0 | 0 |
| 360d | 2025-09-16 | 1 | 0 | 2 | 0 | 0 | 0 |
| last720d | 2024-09-21 | 1 | 1 | 3 | 0 | 0 | 2 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [checksums.txt](https://github.com/therootcompany/sclient/releases/download/v1.5.1/checksums.txt) | 1.1 KiB | `other` |
| [sclient_1.5.1_darwin_amd64v2.tar.xz](https://github.com/therootcompany/sclient/releases/download/v1.5.1/sclient_1.5.1_darwin_amd64v2.tar.xz) | 1.7 MiB | `native/darwin/x64` |
| [sclient_1.5.1_darwin_arm64.tar.xz](https://github.com/therootcompany/sclient/releases/download/v1.5.1/sclient_1.5.1_darwin_arm64.tar.xz) | 1.5 MiB | `native/darwin/arm64` |
| [sclient_1.5.1_freebsd_amd64v2.tar.xz](https://github.com/therootcompany/sclient/releases/download/v1.5.1/sclient_1.5.1_freebsd_amd64v2.tar.xz) | 1.7 MiB | `other` |
| [sclient_1.5.1_freebsd_arm64.tar.xz](https://github.com/therootcompany/sclient/releases/download/v1.5.1/sclient_1.5.1_freebsd_arm64.tar.xz) | 1.4 MiB | `other` |
| [sclient_1.5.1_freebsd_armv7.tar.xz](https://github.com/therootcompany/sclient/releases/download/v1.5.1/sclient_1.5.1_freebsd_armv7.tar.xz) | 1.5 MiB | `other` |
| [sclient_1.5.1_js_wasm.tar.xz](https://github.com/therootcompany/sclient/releases/download/v1.5.1/sclient_1.5.1_js_wasm.tar.xz) | 1.8 MiB | `other` |
| [sclient_1.5.1_linux_amd64.tar.xz](https://github.com/therootcompany/sclient/releases/download/v1.5.1/sclient_1.5.1_linux_amd64.tar.xz) | 1.7 MiB | `native/linux/x64` |
| [sclient_1.5.1_linux_amd64v2.tar.xz](https://github.com/therootcompany/sclient/releases/download/v1.5.1/sclient_1.5.1_linux_amd64v2.tar.xz) | 1.7 MiB | `native/linux/x64` |
| [sclient_1.5.1_linux_arm64.tar.xz](https://github.com/therootcompany/sclient/releases/download/v1.5.1/sclient_1.5.1_linux_arm64.tar.xz) | 1.4 MiB | `native/linux/arm64` |
| [sclient_1.5.1_linux_armv7.tar.xz](https://github.com/therootcompany/sclient/releases/download/v1.5.1/sclient_1.5.1_linux_armv7.tar.xz) | 1.5 MiB | `native/linux/arm` |
| [sclient_1.5.1_windows_amd64v2.zip](https://github.com/therootcompany/sclient/releases/download/v1.5.1/sclient_1.5.1_windows_amd64v2.zip) | 1.8 MiB | `native/win/x64` |
| [sclient_1.5.1_windows_arm64.zip](https://github.com/therootcompany/sclient/releases/download/v1.5.1/sclient_1.5.1_windows_arm64.zip) | 1.7 MiB | `native/win/arm64` |

## 改进这些数据

sclient 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `sclient` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/sclient.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260911.yml` · 2026-09-11T20:19:11Z._
