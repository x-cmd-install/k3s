# k3s

[English version](./README.md)

Lightweight Kubernetes

![k3s](https://repo.x-cmd.io/k3s.svg?lang=zh)

## 安装

```sh
x install k3s
```

## 源代码

- **上游仓库**: <https://github.com/k3s-io/k3s>
- **官网**: <https://k3s.io>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v1.37.0-rc4+k3s1` (2026-08-27)
- **最近提交**: 2026-09-09
- **Release 含资产**: 16 个

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [k3s](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s) | 75.3 MiB | `other` |
| [k3s-airgap-images-amd64.tar](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s-airgap-images-amd64.tar) | 185.7 MiB | `other` |
| [k3s-airgap-images-amd64.tar.gz](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s-airgap-images-amd64.tar.gz) | 184.3 MiB | `native/linux/x64` |
| [k3s-airgap-images-amd64.tar.zst](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s-airgap-images-amd64.tar.zst) | 184.5 MiB | `other` |
| [k3s-airgap-images-arm.tar](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s-airgap-images-arm.tar) | 175.9 MiB | `other` |
| [k3s-airgap-images-arm.tar.gz](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s-airgap-images-arm.tar.gz) | 174.8 MiB | `native/linux/arm` |
| [k3s-airgap-images-arm.tar.zst](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s-airgap-images-arm.tar.zst) | 174.8 MiB | `other` |
| [k3s-airgap-images-arm64.tar](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s-airgap-images-arm64.tar) | 168.4 MiB | `other` |
| [k3s-airgap-images-arm64.tar.gz](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s-airgap-images-arm64.tar.gz) | 166.9 MiB | `native/linux/arm64` |
| [k3s-airgap-images-arm64.tar.zst](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s-airgap-images-arm64.tar.zst) | 167.3 MiB | `other` |
| [k3s-arm64](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s-arm64) | 68.1 MiB | `other` |
| [k3s-armhf](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s-armhf) | 68.9 MiB | `other` |
| [k3s-images.txt](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/k3s-images.txt) | 377 B | `other` |
| [sha256sum-amd64.txt](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/sha256sum-amd64.txt) | 359 B | `other` |
| [sha256sum-arm.txt](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/sha256sum-arm.txt) | 359 B | `other` |
| [sha256sum-arm64.txt](https://github.com/k3s-io/k3s/releases/download/v1.36.4+k3s1/sha256sum-arm64.txt) | 365 B | `other` |

## 流行度

- **Star**: 33,930 · **Fork**: 2,721 · **开放 issue**: 7,722 · **贡献者**: 309

## 累计统计

- **发布数**: 1033 · **已合并 PR**: 4906 · **开放 PR**: 14 · **已关闭 issue**: 7651 · **开放 issue**: 71 · **提交数**: 4298

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 10 | 54 | 7 | 13 | 24 | 33 |
| 90d | 2026-06-12 | 37 | 190 | 9 | 116 | 27 | 118 |
| 360d | 2025-09-15 | 100 | 793 | 12 | 666 | 37 | 503 |

## 代码规模

合计: **64,278** 行代码（覆盖前 5 种语言、共 **502** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 49,856 | 3,640 | 6,184 | 339 |
| Yaml | 9,680 | 123 | 101 | 107 |
| Sh | 3,080 | 479 | 534 | 29 |
| Bash | 696 | 45 | 136 | 17 |
| Hcl | 455 | 4 | 89 | 10 |

## OpenSSF Scorecard 评分

总评分: **8 / 10**

评分最低的几项:

- **Vulnerabilities** (0/10) — 20 existing vulnerabilities detected
- **Signed-Releases** (0/10) — Project has not signed or included provenance with any releases.
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…

## 改进这些数据

k3s 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `k3s` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/k3s.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T15:52:25Z._
