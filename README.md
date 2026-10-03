# CX RAI

<a href="https://get.microsoft.com/installer/download/xpdc6f1c8pjbl2?referrer=appbadge" target="_self">
  <img src="https://get.microsoft.com/images/zh-cn%20dark.svg" width="200" alt="从 Microsoft Store 获取 CX RAI" />
</a>


CX RAI UWP 客户端。

## 下载

- [公开正式版 1.6.7.16：桌面安装器与 Windows Phone/ARM 包](https://github.com/Master-Tea/CX-RAI/releases/latest)
- [源码仓库与更新说明](https://github.com/Master-Tea/CX-RAI-Core)

桌面版使用签名的 `Setup.exe`；Windows Phone/ARM 请先安装 ARM 依赖，再安装 ARM bundle。安装前请确认发行包的签名与 SHA-256 校验值。

## 1.7.10 发布候选（2026-09-30）

- 模型目标更新为 **GPT 6.1 Sol**；DeepSeek 仅保留 Flash，兼容迁移旧模型 ID。
- 冷启动侧边栏先显示本地对话缓存，再后台同步新对话。
- 三架构 Release、签名、移动/桌面能力隔离和原生回归已验证。
- 候选包保留为发布草稿；完成上游模型可用性验证后再正式发布，不把尚不可用的新模型当作已上线功能。
