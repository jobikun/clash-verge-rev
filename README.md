<h1 align="center">
  <img src="./src-tauri/icons/icon.png" alt="Clash Verge" width="128" />
  <br>
  Clash Verge
</h1>

<p align="center">
  无广告、无推广、无应用内更新跳转的桌面代理管理工具。
</p>

## 功能

- 基于 Rust 与 Tauri 2 的桌面应用
- 代理配置、节点、代理组和规则管理
- 系统代理与 TUN 模式
- 配置文件合并、脚本处理和语法提示
- 自定义主题、托盘图标和界面样式
- WebDAV 配置备份与同步
- 可视化节点、连接和规则信息

## 支持平台

- Windows x64
- Windows ARM64
- macOS Intel
- macOS Apple Silicon

## 自动构建

每次向仓库推送代码后，自动构建 Windows 与 macOS 安装包。构建产物由仓库的 Actions 页面提供。

## 本地开发

安装 Tauri 所需环境后执行：

```shell
pnpm install
pnpm run prebuild
pnpm dev
```

生产构建：

```shell
pnpm build
```

## 当前版本

2.5.4

## 许可证

GPL-3.0-only。许可证正文保存在 `LICENSE` 文件中。
