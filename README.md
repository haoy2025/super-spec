# ⚡ super-spec

**Superpowers × Spec-Driven Development 融合开发流程**

> superpowers + spec-kit 双剑合璧，让开发既有流程又有质量！

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.1.0-blue.svg)](https://github.com/haoy2025/super-spec)
[![GitHub stars](https://img.shields.io/github/stars/haoy2025/super-spec?style=social)](https://github.com/haoy2025/super-spec/stargazers)

---

## 🎯 什么是 super-spec？

super-spec 是一个将 **spec-kit**（规格驱动开发）和 **superpowers**（质量保障技能）完美融合的开发流程。

- **spec-kit**: 提供结构化的 SDD 流程（规格 → 计划 → 任务 → 实现）
- **superpowers**: 提供质量保障技能（头脑风暴、TDD、调试、评审、验证）

### 为什么选择 super-spec？

| 特性 | 说明 |
|------|------|
| 📋 **结构化流程** | spec-kit 提供完整的规格驱动开发流程 |
| 🛡️ **质量保障** | superpowers 提供 TDD、调试、评审、验证等技能 |
| 🔄 **灵活融合** | 可以根据项目需要灵活选择使用哪些步骤 |
| 📦 **开箱即用** | 作为 Claude Code 技能，一键启动 |
| 🌍 **开源共享** | MIT 许可证，欢迎贡献和改进 |

---

## 🚀 快速开始

### 前置要求

- [Claude Code](https://www.anthropic.com/claude-code)
- [spec-kit](https://github.com/github/spec-kit) 已安装
- [superpowers](https://github.com/obra/superpowers) 技能已可用

### 安装

1. **克隆此仓库**
   ```bash
   git clone https://github.com/haoy2025/super-spec.git
   cd super-spec
   ```

2. **将技能复制到您的项目**
   ```bash
   # 复制到您的项目的 .claude/skills/ 目录
   cp -r super-spec /path/to/your/project/.claude/skills/
   ```

3. **或者直接使用**
   - 将 `super-spec/` 文件夹复制到您项目的 `.claude/skills/` 目录下
   - 在 Claude Code 中直接使用 `/super-spec` 命令

### 使用

在 Claude Code 中，只需输入：

```
/super-spec 描述您想要开发的功能
```

或者直接启动：

```
/super-spec
```

技能会引导您完成完整的 11 步融合开发流程！

---

## 📋 完整的 11 步融合流程

### 阶段 1：创意与规划

1. **🧠 /superpowers-brainstorming**
   - 目的：头脑风暴，理清思路
   - 时机：在写规格之前

2. **📝 /speckit-constitution**
   - 目的：制定或确认项目原则
   - 时机：项目首次开发时（只需一次）

3. **✍️ /speckit-specify**
   - 目的：创建功能规格（WHAT）
   - 时机：确定要做什么时
   - 💡 提示：如果有原型图，请在这里提供！

### 阶段 2：澄清与设计

4. **❓ /speckit-clarify**
   - 目的：澄清模糊需求
   - 时机：规格写完后

5. **📋 /speckit-plan**
   - 目的：制定技术计划（HOW）
   - 时机：需求澄清后

### 阶段 3：任务与实现

6. **📝 /speckit-tasks**
   - 目的：生成可执行任务列表
   - 时机：技术计划完成后

7. **🧪 /superpowers-test-driven-development**
   - 目的：测试驱动开发实现
   - 时机：开始实现时

### 阶段 4：质量保障

8. **🔍 /superpowers-systematic-debugging**（如需要）
   - 目的：系统化调试问题
   - 时机：遇到 bug 或问题时

9. **✅ /superpowers-verification-before-completion**
   - 目的：完成前验证
   - 时机：实现完成后

10. **👀 /superpowers-requesting-code-review**
    - 目的：请求代码评审
    - 时机：验证通过后

### 阶段 5：完成

11. **🎉 /superpowers-finishing-a-development-branch**
    - 目的：完成开发分支
    - 时机：所有检查通过后

---

## 💡 使用技巧

### 有原型图？

最好在 `/speckit-specify` 阶段提供原型图！

- 直接拖拽上传图片到对话中
- 或者把图片放在项目目录中，告诉技能路径

### 不确定技术栈？

可以在 `/speckit-plan` 阶段一起讨论，技能会帮助您做出合适的技术选择。

### 遇到问题？

随时使用 `/superpowers-systematic-debugging` 来系统化地调试问题。

### 想快速验证？

使用 `/superpowers-verification-before-completion` 在完成前快速验证。

---

## 🤝 贡献

欢迎贡献！请阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 了解如何参与。

### 开发设置

1. Fork 此仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

---

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。

---

## 🙏 致谢

- [spec-kit](https://github.com/github/spec-kit) - 规格驱动开发工具包
- [superpowers](https://github.com/obra/superpowers) - Claude Code 超级技能集合

---

## 📮 联系方式

- GitHub Issues: [https://github.com/haoy2025/super-spec/issues](https://github.com/haoy2025/super-spec/issues)
- 项目主页: [https://github.com/haoy2025/super-spec](https://github.com/haoy2025/super-spec)

---

**如果这个项目对您有帮助，请给我们一个 ⭐ Star！**

---

<div align="center">
  <strong>Made with ❤️ by the open source community</strong>
</div>
