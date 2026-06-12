# Defense Deck Generator

一个面向述职 / 晋升 / 答辩场景的 Skill，用于把零散素材自动整理为**一页纸高密度汇报**与**完整答辩报告**。

## 仓库结构

```text
defense-deck-generator-github/
├── README.md
├── .gitignore
└── skills/
    └── defense-deck-generator/
        └── SKILL.md
```

## Skill 说明

- **Skill 名称**：Defense Deck Generator（述职答辩材料生成器）
- **目录位置**：`skills/defense-deck-generator/SKILL.md`
- **核心能力**：
  - 自动理解项目背景、旧文档、数据截图、工作总结等素材
  - 产出一页纸答辩首页级白板
  - 产出完整答辩报告
  - 自动补足评委视角下的关键叙事链路

## 如何发布到你自己的 GitHub

### 1. 创建 GitHub 仓库
先在 GitHub 新建一个空仓库，例如：

- 仓库名：`defense-deck-generator`

### 2. 进入当前目录并初始化 Git

```bash
cd defense-deck-generator-github
git init
git add .
git commit -m "init: add defense deck generator skill repo"
```

### 3. 关联你的 GitHub 仓库并推送

```bash
git branch -M main
git remote add origin https://github.com/<你的 GitHub 用户名>/defense-deck-generator.git
git push -u origin main
```

如果你使用 SSH，也可以改成：

```bash
git remote add origin git@github.com:<你的 GitHub 用户名>/defense-deck-generator.git
```

## 后续建议

如果你后面准备继续扩展多个 Skill，建议继续沿用下面这种结构：

```text
skills/
  ├── defense-deck-generator/
  │   └── SKILL.md
  └── another-skill/
      └── SKILL.md
```

这样后续无论是自己维护，还是给工具链扫描，都会更清晰。
