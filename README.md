# AI Mem like Human

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Giving AI long-term memory through human-like recall**

AI Mem like Human 是一个受人类记忆机制启发的智能对话记忆系统。它不只是一个简单的数据库，而是通过模仿人类"按需提取"和"标记索引"的记忆方式，让AI能够真正"回忆"起过去的对话。

## 🌟 核心思想

人类如何记忆？
- 我们不会存储所有细节，只记住关键标记
- 需要时，沿着这些标记的路径追溯
- 回忆是一个动态的、按需的过程

AI Mem like Human 正是这样工作的：
- **标记化存储**：将对话按主题分割，提取特征标记
- **分层检索**：先通过标记快速定位，必要时深度扫描
- **渐进式回忆**：从近期到远期，从精确到模糊
- **自进化标记**：每次使用都为相关对话添加新标记

## 🚀 主要特性

- **🧠 类人类记忆路径** - 模仿人类"标记-追溯-回忆"的完整过程
- **🏷️ 智能标记系统** - 自动从对话中提取结构化标记 [domain:xxx][entity:xxx]...
- **⚡ 分层检索策略** - 先标记索引，后向量匹配，最后全量扫描
- **📅 时间衰减机制** - 默认优先检索近期记忆，需要时自动回溯
- **📊 上下文智能管理** - 自动处理超长记忆，分段总结再合并
- **🔍 向量相似度检索** - 支持模糊匹配和语义理解
- **🔄 自学习标记库** - 标记体系随使用而丰富

## 🏗️ 系统架构

```
用户输入
    ↓
[需求分析] → 提取特征短语
    ↓
[标记检索] → 命中？→ 是 → [打包记忆] → AI回答
    ↓ 否                    ↓
[向量匹配] → 命中？→ 是 → [添加新标记] 
    ↓ 否                    ↓
[全量扫描] ← 用户确认需要深度搜索
    ↓
[结果返回]
```
## 🤝 贡献指南

欢迎贡献！无论是新功能、bug修复还是文档改进：

1. Fork 项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 📄 开源协议

MIT License - 详见 [LICENSE](LICENSE) 文件

## 🙏 致谢

- 灵感来源于人类认知心理学和记忆研究
- 感谢所有贡献者的想法和建议

## 📮 联系方式

- GitHub Issues: [报告问题](https://github.com/bdangel1984/AI-Mem-like-Human/issues)
- 讨论区: [GitHub Discussions](https://github.com/bdangel1984/AI-Mem-like-Human/discussions)

---

**让AI像人类一样记忆，一次一个痕迹** 🧠✨
