# ZodiacAuto — FF14 古武（黄道武器）全自动助手

Dalamud 插件，用于自动完成上古武器 → 黄道武器（iLvl 125）全流程。
目标止于 **黄道武器 iLvl 125**，不做 iLvl 135「本我」和复制品。

> **本项目为「闭源的公开项目」**：仓库公开用于发布与下载编译好的插件，
> **源代码不公开**。版本更新记录见 [CHANGELOG.md](CHANGELOG.md)。

- 插件内名：`ZodiacAuto`
- 显示名：`ZodiacAuto`
- 游戏内命令：`/zodiacauto` 或 `/zauto`

## 安装

1. 在本仓库 `release/` 目录下载：
   - `ZodiacAuto.dll`
   - `ZodiacAuto.json`
   - `ZodiacAuto.deps.json`
   - `images/icon.png`
2. 放到 `%APPDATA%\XIVLauncherCN\devPlugins\ZodiacAuto\`（国服）
   或 `%APPDATA%\XIVLauncher\devPlugins\ZodiacAuto\`（国际服）
3. 游戏内 `/xlplugins` → Dev Tools → Scan Dev Plugins，启用 **ZodiacAuto**

## 功能概览

- 古武全阶段自动化：魂晶 → 星极 → 镇魂 → 黄道（iLvl 125）
- 九卷黄道文书：击杀 / 副本 / FATE / 理符 每项独立按钮
- 自动寻路（vnavmesh）、自动传送（Lifestream）、自动战斗（RotationSolver）
- 副本走 AutoDuty（解限/剧情辅助器，不排本）
- 自动切换职业与武器（直接检索兵装库）
- 运行日志持久化到磁盘，状态栏实时显示当前动作

## 更新记录

见 [CHANGELOG.md](CHANGELOG.md)。
