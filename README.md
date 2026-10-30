# alianggao2

个人工作区仓库，用于存放日常项目、笔记与实验代码。

## 目录结构

| 路径 | 说明 |
| --- | --- |
| `README.md` | 仓库说明（当前文件） |
| `skills/book-mockup-poster/` | 自营店图书电商主图生成规范（封面 760/1520 出图 Skill） |
| `resources/高考资料.md` | GitHub 开源高考辅导资源清单（真题 / 教材 / 题库 / 志愿填报） |

> 后续按实际内容补充。

## 待补依赖

`skills/book-mockup-poster/SKILL.md` 引用了以下三个文件，**当前仓库中尚未包含**，补齐前该 Skill 无法实际运行：

| 缺失文件 | 用途 | 状态 |
| --- | --- | --- |
| `skills/book-mockup-poster/scripts/make_poster.py` | 渲染脚本：填充模板 → Chrome headless 截图 → 输出 1520/760 两档并按 `--max-size` 控制体积 | 待补 |
| `skills/book-mockup-poster/assets/poster_template.html` | 已验收版式模板，含占位符说明 | 待补 |
| `skills/book-mockup-poster/assets/logo.png` | 出版社 logo（352×76，阈值 210 裁切、四周留 8px 纯白） | 待补 |

> 注意：`SKILL.md` 声明版式已逐轮验收、须以脚本出图以保证与历史图片一致。补齐时应使用原始文件，不要重写实现，否则外观可能偏离验收版本。

## 使用

```bash
git clone https://github.com/alianggao/alianggao2.git
```

## 说明

- 仓库创建于 2026-10-30
- 维护者：[@alianggao](https://github.com/alianggao)
- 个人项目，代码仅供参考
