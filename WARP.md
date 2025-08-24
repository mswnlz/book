# Warp AI 优化配置

## 项目简介
这是一个图书推荐相关的资源仓库，主要包含书籍推荐、阅读笔记和学习资源分享。

## 常用命令
```bash
# 查看最近更新的文档
ls -lt *.md | head -5

# 搜索特定内容
grep -r "关键词" *.md

# 统计文档数量
ls *.md | wc -l
```

## Git 工作流
```bash
# 添加新文档
git add 202508.md
git commit -m "Add 202508 book recommendations"
git push origin main
```

## 文档约定
- 文档命名格式：YYYYMM.md
- 内容包含图书推荐、阅读笔记、学习指南
- 每月更新相关内容
