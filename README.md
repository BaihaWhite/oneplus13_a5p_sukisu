# OnePlus Ace2 Pro / Pad Pro SukiSU Ultra 内核

为 OnePlus Ace2 Pro 与 OnePlus Pad Pro 打造的**每日自动构建**内核，每日更新 SukiSU Ultra，内置 SUSFS 系统隐藏框架。

## 🌟 核心特性

| 功能模块 | 说明 |
|---------|------|
| **SukiSU Ultra** | 基于 KernelSU 的增强版 root 方案，提供更强的系统权限管理能力 |
| **SUSFS v1.5.6** | 内核级系统修改隐藏框架，支持魔法挂载、路径隐藏与挂载点伪造 |
| **HMBird GKI 补丁** | 绕过 OPLUS HMBird 内核检测机制，确保系统兼容性 |
| **LZ4K/LZ4KD 压缩** | 高性能 zram 压缩算法，提升内存效率 |
| **BBR TCP 加速** | 替代 CUBIC，默认启用 BBR 拥塞控制算法 |
| **sched_ext 调度扩展** | 来自 HanKuCha 的调度器优化补丁 |
| **KernelPatch 加固** | 增强内核完整性保护 |

## 📱 支持设备

- ⚠️ **OnePlus Ace2 Pro** (尚未支持)
- ✅ **OnePlus Pad Pro** - 已支持 ColorOS 16

## 📦 构建与发布

- **自动构建**：每日 06:00 GMT+8 触发
- **手动触发**：可fork之后在 Actions 页面自定义构建参数
- **构建产物**：AnyKernel3 刷机包，支持 KernelSU Manager 在线更新

## 🔧 技术参数

- **源码分支**：`oneplusoss`
- **编译方式**：O2+O3，性能卓越，丝般顺滑
- **Rust 工具链**：1.73.0b
- **维护者**：BaihaWhite (酷安@白桦白)

## 📲 安装方式

1. 从 [Releases](../../releases) 下载最新Ak3刷机包
2. 进入SukiSU Ultra，在有root的前提下点击刷入Ak3刷机包
3. 点击确定，选择跟随内核，点击下一步。
4. 等待进程全部执行完之后，重启系统。

## ⚠️ 注意事项

- 需解锁 Bootloader
- 已集成 SUSFS，无需过多额外配置隐藏
- 刷机有风险，请做好数据备份
- 建议配合 SukiSU Ultra Manager 使用

## 🤝 致谢

- GitHub@HanKuCha（酷安@FutabaWa）
- GitHub@44C38B8（酷安@骁龙8至尊版）
- KernelSU 官方团队
- SUSFS 项目 (sidex15)


**项目状态**：✅ 积极维护中 | 最后更新：请参考 Releases 页
