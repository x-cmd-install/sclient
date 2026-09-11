# sclient

[中文版本](./README.cn.md)

Secure Client for exposing TLS (aka SSL) secured services as plain-text connections locally. Also ideal for multiplexing a single port with multiple protocols using SNI.

![sclient](https://repo.x-cmd.io/sclient.svg)

## Install

```sh
x install sclient
```

## Code insight

Total: **277** lines of code across **8** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 260 | 66 | 38 | 3 |
| Bitbake | 10 | 1 | 0 | 1 |
| Sh | 7 | 3 | 4 | 3 |
| Markdown | 0 | 97 | 48 | 1 |

## OpenSSF Scorecard

Overall score: **3 / 10**

Lowest-scoring checks:

- **Code-Review** (0/10) — Found 0/28 approved changesets -- score normalized to 0
- **Packaging** (-1/10) — packaging workflow not detected
- **Dangerous-Workflow** (-1/10) — no workflows found

## Source

- **Upstream**: <https://github.com/therootcompany/sclient>
- **Homepage**: <https://webinstall.dev/sclient>
- **License**: NOASSERTION

## Release

- **Latest**: `v1.5.1` (2025-09-17)
- **Last commit**: 2025-08-06
- **Assets in release**: 13

## Popularity

- **Stars**: 20 · **Forks**: 2 · **Open issues**: 3 · **Contributors**: 2

## Totals (cumulative)

- **Releases**: 6 · **Merged PRs**: 2 · **Open PRs**: 3 · **Closed issues**: 2 · **Open issues**: 1 · **Commits**: 32

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-15 | 0 | 0 | 2 | 0 | 0 | 0 |
| 360d | 2025-09-16 | 1 | 0 | 2 | 0 | 0 | 0 |
| last720d | 2024-09-21 | 1 | 1 | 3 | 0 | 0 | 2 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
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

## Improve this data

Install metadata for sclient lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `sclient` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/sclient.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T04:39:01Z._
