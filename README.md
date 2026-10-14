# 星际突击：五域远征 · STAR STRIKE

[![Play in browser](https://img.shields.io/badge/Play-HTML5%20Canvas-36b5ee)](./index.html)
![Five stages](https://img.shields.io/badge/Stages-5-blue)
![Bosses](https://img.shields.io/badge/Bosses-5-orange)

一款无需安装的**复古像素风太空战斗闯关游戏**。在五个星域中对抗敌机、躲避陨石与弹幕、升级飞船武器，并击败关底 Boss。

A standalone pixel-art HTML5 space shooter featuring five stages, five boss encounters, weapon upgrades, enemy formations and pulse-dodge combat.

## 立即游玩 / Play

- **本地 / Offline**：下载 `index.html`，在 Chrome、Edge 或 Firefox 中打开即可。
- **GitHub Pages**：在仓库 `Settings → Pages` 设置 `Deploy from a branch → main → /(root)` 后，可从 https://mamawen.github.io/starstrike-five-domain-expedition/ 游玩。启用并完成部署前此链接不一定可访问。
- 无须安装依赖、服务器或构建工具（No build step required）。

## 玩法与操作 / Controls

| 操作 | 电脑 | 手机 |
| --- | --- | --- |
| 移动飞船 | WASD / 方向键 | 左侧方向按钮 |
| 射击 | 自动开火 | 自动开火 |
| 脉冲闪避（短暂无敌并清除附近敌弹） | Space / K / X | PULSE 按钮 |
| 暂停/继续 | P / Esc | 使用游戏操作界面 |
| 过关选择强化 | 1 / 2 / 3 | 点击升级卡片 |

推荐手机横屏游玩。首次点击或按键后游戏会尝试启动音效（浏览器可能限制自动播放）。

## 五大关卡 / Campaign

1. 边陲警戒 · OUTER DEFENSE — 哨兵主机
2. 陨石裂隙 · METEOR RIFT — 熔核要塞
3. 离子风暴 · ION STORM — 电弧母舰
4. 失落舰城 · LOST CITADEL — 机械统帅
5. 深渊决战 · ABYSS FRONT — 深渊核心

每关消灭规定数量的敌机后出现 Boss。击败 Boss 后可选择武器、装甲或引擎的永久强化。

## 核心功能

- 精细复古像素飞船与太空场景（使用 Canvas 程序化绘制）
- 五关渐进式战斗、敌舰弹幕和五个 Boss
- 多重射击、火力提升、装甲修复和速度升级
- 火焰陨石、拾取物、爆炸粒子与音效
- 脉冲闪避与短暂无敌
- 分数及最高分本地存档、游戏暂停与重开
- 桌面键盘与手机触屏输入

## 技术栈 / Tech

- HTML5 Canvas
- Vanilla JavaScript
- CSS3
- Web Audio API
- LocalStorage

完整游戏位于单文件 `index.html`，无外部脚本依赖。

## 开发与测试

在现代浏览器打开 `index.html`。开发测试钩子仅在地址包含 `?test=1` 时暴露 `window.__starstrikeTest`，用于本地验证关卡、Boss 与技能逻辑。

> 浏览器自动化回归已覆盖五关结算等核心流程，实际设备体验、帧率与平衡性仍建议持续测试。

## 创作来源与许可

视觉方向与单文件 Canvas 形式参考了 [Meteor Dodge by CodeByArt](https://github.com/codebyartcom/meteor-dodge-codebyart)（MIT）；并未把其 README 宣传截图直接作为本游戏资源。来源与完整第三方 MIT 版权声明见 [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md)。

本仓库游戏内容按 [MIT License](./LICENSE) 发布。若后续加入外部图片、音乐或音效，请单独核对其授权。

---
Enjoy the expedition.
