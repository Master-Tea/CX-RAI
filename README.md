# CX RAI

<a href="https://get.microsoft.com/installer/download/xpdc6f1c8pjbl2?referrer=appbadge" target="_self">
  <img src="https://get.microsoft.com/images/zh-cn%20dark.svg" width="200" alt="从 Microsoft Store 获取 CX RAI" />
</a>

CX RAI UWP 客户端，支持 Windows 桌面与 Windows 10 Mobile/ARM。

## 下载

- [公开正式版 1.8.26：桌面安装器与 Windows Phone/ARM 包](https://github.com/Master-Tea/CX-RAI/releases/latest)
- [1.8.26 更新说明、校验值与验证证据](https://github.com/Master-Tea/CX-RAI/releases/tag/v1.8.26)
- [官网：Web 体验与 Windows 下载](https://rick.sarl)
- [源码仓库（维护者访问）](https://github.com/Master-Tea/CX-RAI-Core)

桌面版使用签名的 `Setup.exe`；Windows Phone/ARM 请先安装 ARM 依赖，再安装 ARM bundle。安装前请确认发行包的签名与 SHA-256 校验值。GitHub 侧载版与 Microsoft Store 版的上架版本可能不同，以各渠道页面为准。

## 最近更新（1.8.20–1.8.26）

- 中英界面与跟随系统语言设置；453 条双语 XAML 资源，Helper 与桌宠同步语言，不改写用户内容或模型 ID。
- 输入框内的 @ 技能候选不抢走输入焦点；统一技能设置、菜单、侧栏搜索与窄窗口布局。
- 原生流式渲染与 Markdown/表格选择复制；缓存优先的对话和侧栏、受内存与交互预算约束的设置预加载。
- 常驻关闭即时通知 Helper，隐藏主窗口任务栏预览，重开恢复；保留移动端和旧版 Windows 的兼容边界。
- 模型策略包含 **GPT 6.1 Sol**，并保持 Web/客户端的额度、推理档位与旧模型 ID 迁移一致。

1.8.25 未单独公开发布，英文化改动包含在 1.8.26。桌面安装器、ARM 与 x86/x64 bundle 均为原始签名资产，不在同一版本号下重建。

## 发布验证边界

1.8.26 的签名包审计 334/334、打包预检 33/33、定向回归 19/19。原 `build-verification.json` 因 PowerShell 数组统计错误写成 3/3；附加的 `build-verification-correction.json`、回归证据 ZIP 与 `CORRECTION-SHA256SUMS.txt` 说明更正，原资产和原 SHA256SUMS 保持不变。

构建、签名和合成回归不能替代真实设备的安装、中文输入、关闭/重开、任务栏和视觉验收；Windows Phone/旧系统请结合目标设备验证。
