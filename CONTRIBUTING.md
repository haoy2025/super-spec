# Contributing to super-spec

首先，感谢您有兴趣为 super-spec 做出贡献！🎉

我们欢迎各种形式的贡献：

- 🐛 报告 Bug
- ✨ 提出新功能建议
- 📖 改进文档
- 💻 提交代码修复
- 🎨 改进设计
- 🧪 添加测试

---

## 行为准则

### 我们的承诺

为了营造开放和友好的环境，我们承诺：

- 尊重不同的观点和经验
- 优雅地接受建设性批评
- 关注对社区最有利的事情
- 对其他社区成员表示同理心

### 不可接受的行为

- 使用性化的语言或图像
- 恶意评论或人身攻击
- 公开或私下骚扰
- 未经许可发布他人的私人信息
- 其他不专业或不恰当的行为

---

## 如何贡献

### 报告 Bug

如果您发现了 Bug，请通过 [GitHub Issues](https://github.com/haoy2025/super-spec/issues) 报告，并提供：

1. **清晰的标题** - 简短描述问题
2. **复现步骤** - 详细说明如何重现问题
3. **预期行为** - 您期望发生什么
4. **实际行为** - 实际发生了什么
5. **环境信息** - Claude Code 版本、操作系统等
6. **截图（如果适用）** - 帮助说明问题

### 提出新功能建议

我们欢迎新功能建议！请在 [GitHub Issues](https://github.com/haoy2025/super-spec/issues) 中提出，并提供：

1. **功能描述** - 清晰描述您想要什么
2. **使用场景** - 这个功能解决了什么问题
3. **建议的实现方式** - 如果您有想法，请分享
4. **替代方案** - 您考虑过的其他解决方案

### 提交代码

1. **Fork 此仓库**
   ```bash
   git clone https://github.com/haoy2025/super-spec.git
   cd super-spec
   ```

2. **创建特性分支**
   ```bash
   git checkout -b feature/AmazingFeature
   ```

3. **提交更改**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```

4. **推送到分支**
   ```bash
   git push origin feature/AmazingFeature
   ```

5. **开启 Pull Request**

### 改进文档

文档改进也是非常重要的贡献！您可以：

- 修正错别字或语法错误
- 改进说明的清晰度
- 添加更多示例
- 翻译文档到其他语言
- 添加教程或使用指南

---

## 开发指南

### 项目结构

```
super-spec/
├── README.md              # 项目说明文档
├── LICENSE                # MIT 许可证
├── CHANGELOG.md           # 变更日志
├── CONTRIBUTING.md        # 贡献指南（本文件）
├── .gitignore             # Git 忽略文件
└── super-spec/            # Claude Code 技能文件夹
    └── SKILL.md          # 主要的技能文件
```

### 技能开发

技能文件位于 `super-spec/SKILL.md`，它是一个 Claude Code 技能文件。

#### 技能文件格式

Claude Code 技能使用 YAML frontmatter + Markdown 正文的格式：

```markdown
---
name: "skill-name"
description: "技能描述"
compatibility: "兼容性说明"
metadata:
  author: "作者"
  source: "来源"
  version: "版本号"
user-invocable: "true"
disable-model-invocation: "true"
argument-hint: "参数提示"
---

技能的 Markdown 正文内容...
```

#### 测试您的更改

1. 将修改后的技能复制到 Claude Code 项目的 `.claude/skills/` 目录
2. 在 Claude Code 中重新加载或重启会话
3. 测试 `/super-spec` 命令

---

## Pull Request 指南

### PR 标题格式

请使用清晰的标题格式：

- `feat: 添加新功能 X`
- `fix: 修复 Bug Y`
- `docs: 改进文档 Z`
- `refactor: 重构代码`
- `test: 添加测试`
- `chore: 构建/工具相关更改`

### PR 描述

请在 PR 描述中包含：

1. **更改的内容** - 简要描述您做了什么
2. **原因** - 为什么需要这些更改
3. **影响** - 这些更改会影响什么
4. **测试** - 您如何验证这些更改
5. **截图（如果适用）** - 展示更改的效果

---

## 获取帮助

如果您有任何问题或需要帮助，请：

- 开启一个 [GitHub Issue](https://github.com/haoy2025/super-spec/issues)
- 在相关 Issue 中评论
- 联系维护者

---

## 认可贡献者

我们会在项目中认可所有贡献者！每一个贡献，无论大小，都是有价值的。

---

再次感谢您对 super-spec 的兴趣！🙏

<div align="center">
  <strong>让我们一起让开发变得更好！</strong> 🚀
</div>
