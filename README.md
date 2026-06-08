# Xe Grap — 金币拾取游戏

## 🎮 游戏简介

一款使用 Godot 引擎制作的 2D 金币拾取游戏，玩家控制角色在场景中移动并收集金币。本项目跟着教程完成，适合 Godot 初学入门。

## 🕹️ 游戏玩法

- **目标**：收集所有金币，获得尽可能高的分数
- **操作方式**：
  - 左右移动：`A` / `D` 或 `←` / `→`
  - 跳跃：`Space`

## ✨ 核心功能

- 2D 横版跳跃操作
- 金币拾取系统（通过 `Area2D` 信号检测）
- 得分统计与实时显示
- 可收集金币可重复放置
- 碰撞检测与物理反馈

> 🧩 游戏使用的教程来自 `Coin Dash — Build Your First 2D Game`，该教程介绍了如何使用 Godot 常用节点完成一个小型 2D 项目。

## 📸 游戏截图

> <img width="1066" height="600" alt="image" src="https://github.com/user-attachments/assets/7e874d62-c7e1-43d7-8bbf-3b331df27961" />

*

## 🛠️ 技术栈

- **游戏引擎**：[Godot Engine](https://godotengine.org/)（推荐使用 4.x 版本）
- **脚本语言**：GDScript
- **节点类型**：`CharacterBody2D`（玩家角色）、`Area2D`（金币）、`CollisionShape2D`、`Sprite2D` 等

## 🚀 快速开始

### 环境要求

- Godot Engine 4.x
- 支持运行 Godot 的操作系统（Windows / macOS / Linux）

### 运行方式

1. 克隆本仓库
2. 打开 Godot 引擎，点击 **导入（Import）** ，选择项目文件夹中的 `project.godot` 文件
3. 点击 **运行（F5）** 开始游戏

```
git clone https://github.com/duanhuixia-qianduan/FirstGame.git
```

## 📂 项目结构

```
├── scenes/          # 游戏场景文件（主场景、玩家、金币等）
├── scripts/         # GDScript 脚本
├── assets/          # 图像、音效等资源文件
└── project.godot    # 项目配置文件
```

> 💡 建议在项目中使用 `snake_case` 命名文件和文件夹，`PascalCase` 命名节点，以避免跨平台的文件系统兼容问题。

## 🧪 后续计划

- [ ] 增加更多关卡
- [ ] 添加计时系统
- [ ] 加入音效和背景音乐
- [ ] 增加障碍物和敌人
- [ ] 添加分数排行榜

## 🙏 致谢

- Godot 官方文档与社区
- 教程作者提供的学习路径和示例代码

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源许可。
