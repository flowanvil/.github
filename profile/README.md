# ⚒️ Flow Anvil

> **代码在此淬火，构建由此成型。**  
> 专为我的开源项目打造的集中式 CI/CD 基础设施与构建流水线。

欢迎来到 **Flow Anvil**。本组织作为后端工厂，负责自动化处理各类仓库的构建、测试、发布及部署流程。我们不只是运行脚本，更是在锻造可靠的二进制成品。

## 🎯 使命

提供一个健壮、安全且高效的环境，以实现：
- **持续集成 (CI)**: 每次推送时的自动化测试与代码规范检查。
- **持续交付 (CD)**: 跨平台工件构建（Linux, Windows, macOS）。
- **版本管理**: 签名、打包并发布稳定版本。

通过将工作流集中于此，我们可以保持源码仓库专注于业务逻辑，同时将运维层面的复杂性隔离在专门的生产线中。

## 🏗️ 当前项目与流水线

本组织托管共享动作（Actions）以及以下项目的特定流水线配置：

| 项目 | 仓库链接 | 平台 | 状态 | 描述 |
| :--- | :--- | :---: | :---: | :--- |
| [**Open Design**](https://github.com/nexu-io/open-design) | [`open-design`](https://github.com/flowanvil/open-design-builder) | GitHub | 🟢 活跃 | 基于 Rust + egui 的 Git 镜像管理工具。<br>*流水线:* Linux x86_64/aarch64 构建, AppImage 打包。 |
| [**DevEco Code**](https://atomgit.com/openharmony-sig/deveco-code) | [`deveco-linux`](https://atomgit.com/flowanvil/deveco-linux) | AtomGit | 🟢 活跃 | DevEco Code 的 Linux 版本构建仓库（仅含 CI 流水线与文档，源码运行时拉取上游）。<br>*流水线:* Woodpecker 文档构建部署、Nightly 上游补丁构建 Linux x64 二进制并发布 AtomGit Release。 |
| *(未来计划)* | *(敬请期待)* | — | ⚪ 规划中 | 即将加入的其他工具链。 |

