# 暗夜记录本 Night Lantern Notes

为 Kiroween 2026 参赛而建的新项目，报 Costume Contest（任何应用，界面精致难忘）。

## 是什么

一个单页离线记录本，暗夜灯笼风：
- 新增、删除、搜索记录
- 数据只存在浏览器本地存储，断网也能用
- 一键导出 CSV，方便事后整理

## 怎么跑

直接打开 `index.html`，或访问 GitHub Pages：

https://longyanwang4-cell.github.io/night-lantern-notes/

不需要后端、不需要账号、不需要安装。

## Kiro 使用说明

本仓库按 Kiro 的 spec 驱动流程准备：
- `.kiro/specs/night-lantern-notes/requirements.md`：需求与验收标准
- `.kiro/specs/night-lantern-notes/design.md`：设计（本地存储 + 单页结构）
- `.kiro/specs/night-lantern-notes/tasks.md`：任务清单
- `.kiro/steering/`：产品与技术约束（离线优先、零后端、零版权素材）

注意：`.kiro` 目录没有被加入 `.gitignore`，按参赛规则保留在仓库根目录。

## 参赛信息

- 类别：Costume Contest
- 演示视频：YouTube 公开视频，3 分钟以内（提交时填链接）
- 许可证：MIT，见 `LICENSE`

## 目录

```
index.html
README.md
LICENSE
.kiro/
  specs/night-lantern-notes/
  steering/
```
