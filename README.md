# 物魄奇谭 Spirit Tales

> 当竹笛声刺破月影，盛唐的暗夜骤然苏醒。这是一场器物寄魂的诡谲之旅，用UE5的纳米级唐风建模撕裂时空，以器物为钥，揭开盛唐皮下机械般精密运转的文明暗码。

## 🌌 游戏简介

《物魄奇谭》是一款基于 **Unreal Engine 5** 和 **Gameplay Ability System (GAS)** 构建的动作冒险游戏。玩家将在盛唐长安的夜色中，通过触碰器物获得变身能力，揭开这座不夜城背后的神秘面纱。

## ✨ 核心特色

### 🔮 器物寄魂
触碰斑驳青铜酒觥，你的躯壳瞬间爬满饕餮纹，化作双目燃青焰的司祭铜人；拾起遗落市井的残破陶俑，肌肤便龟裂为兵马俑甲片，可扛起坊门石柱破解机关。

### 🎨 UE5 技术
- **Nanite**：呈现唐代建筑复杂斗拱结构
- **Lumen**：光照系统凸显夜间灯笼的冷暖光对比
- **Niagara**：粒子系统呈现传统祥云、火纹等意象

### 🏯 盛唐长安
宫阙飞檐缀满星斗，曲江水纹倒映琉璃光，朱雀大街如鎏金血脉贯通南北。十二时辰的宵禁鼓声在脑后追赶，你的每一次形态吞噬都在改写这座不夜城。

### 🎮 视角切换
按下 T 键，在第三人称与第一人称间随心切换，身临其境的盛唐冒险！

### ✨ 物品交互
任意穿梭，解锁神秘地点触发稀有剧情，在不同立体画作中，留下独一无二的墨迹。

### 🖌️ 水墨晕染
角色变形过程融入水墨晕染过渡效果，笔墨生魄，化身为人。

## 🏗️ 技术架构

### Gameplay Ability System (GAS)

本项目采用 UE5 的 GAS 系统实现核心游戏机制：

| 模块 | 说明 |
|------|------|
| **Ability System** | 自定义 ASC，支持能力等级管理 |
| **AttributeSet** | 生命值、魔法值等属性管理 |
| **Gameplay Abilities** | 玩家攻击、敌人 AI 等能力 |
| **Gameplay Effects** | 伤害、治疗、属性初始化 |
| **Gameplay Tags** | 状态管理与能力激活控制 |

### 文件结构

```
├── Config/                    # 引擎配置
├── Content/                   # 游戏资源
│   ├── THAT/                  # 核心蓝图
│   ├── Characters/            # 角色模型
│   ├── GameAnimsPack/         # 动画资源
│   └── StarterContent/        # 基础素材
└── Source/CrashCourse/        # C++ 源代码
    ├── AbilitySystem/         # GAS 系统扩展
    ├── Characters/            # 角色类
    ├── Player/                # 玩家控制器/状态
    ├── GameplayTags/          # 标签定义
    └── Utils/                 # 工具函数
```

## 🚀 快速开始

### 环境要求
- Unreal Engine 5.6+
- Visual Studio 2022+
- Windows 10/11

### 构建步骤

1. **克隆仓库**
   ```bash
   git clone git@github.com:AaronSwartz0217/UE5-SpiritTales-GAS.git
   ```

2. **打开项目**
   - 双击 `CrashCourse.uproject` 启动 Unreal Engine

3. **构建项目**
   - 在编辑器中点击 **Compile** 按钮编译 C++ 代码

4. **运行游戏**
   - 选择 `OverRide` 地图，点击 **Play** 按钮

## 🎮 操作说明

| 按键 | 功能 |
|------|------|
| `W/A/S/D` | 移动 |
| `Mouse` | 视角控制 |
| `Space` | 跳跃 |
| `Left Click` | 主攻击 |
| `Right Click` | 副攻击 |
| `T` | 视角切换 |

## 📖 学习资源

本项目同时作为 **GAS 学习教程**，覆盖以下核心知识点：

1. **AbilitySystemComponent 扩展**
2. **AttributeSet 实现**
3. **GameplayAbility 继承**
4. **GameplayEffect 应用**
5. **GameplayTag 使用**
6. **AI 与 GAS 集成**

## 👥 团队成员

| 成员 | 角色 |
|------|------|
| 李东盛 | 核心开发者 |
| 杨旭 | 开发者 |
| 司家慧 | 开发者 |
| 朱政宇 | 开发者 |

## 📄 许可证

本项目仅供学习和研究使用。

---

> 笔墨生魄，化身为人——在朦胧夜色中，探索长安奥秘，感受跨越千年的盛唐之美。

[🌐 官网](https://aaronswartz0217.github.io/Spirit-Tales/)