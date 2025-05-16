<h1 align="center">Build-your-own-kernel</h1>

<p align="center">
  <b>基于 GKI 的 SukiSU Ultra 内核</b><br>
  <sub>参考大佬成果并在其基础上优化，自用内核工程</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/Celestials316/Build-your-own-kernel?style=flat-square">
  <img src="https://img.shields.io/github/stars/Celestials316/Build-your-own-kernel?style=social">
</p>

---

## ✨ 项目介绍

本项目是一个基于 **GKI 架构 + KernelSU（SukiSU Ultra 分支）** 的定制内核工程。  
参考了多位大佬的公开项目并结合实际需求进行了修改与整合，最终形成了当前的自用内核构建环境。

---

## ⚙️ 特性一览

- 支持 **SukiSU Ultra** 权限控制模块
- 支持 GitHub Actions 云端自动构建
- 精简 defconfig，删除多余模块
- 可通过 AnyKernel3 封装快速刷入

---

## 📦 使用方法

### 1. 克隆仓库

```bash
git clone https://github.com/Celestials316/Build-your-own-kernel.git
```
### 2. 使用 GitHub Actions 编译并刷入

---

## 🙏 鸣谢 Thanks

- [KernelSU](https://github.com/tiann/KernelSU)
- [SukiSU](https://github.com/SukiSU)
- 各位热心提供内核适配经验的大佬们！
- GitHub Actions 社区编译脚本模板贡献者

