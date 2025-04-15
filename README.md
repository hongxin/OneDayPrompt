

<h1 align="center">老张的一天：简易AI提示词教程</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue" alt="Python">
  <img src="https://img.shields.io/badge/Transformers-4.28.1-orange" alt="Transformers">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/github/last-commit/hongxin/OneDayPrompt" alt="Last Commit">
</p>

# One Day Prompt: an AI prompt tutorial 

## 🚀 项目简介
"老张的一天"是一个面向AI新手用户的提示词实战教程，通过模拟使用者"老张"从早到晚的工作场景，将复杂的提示词知识拆解为生活化案例。项目采用"学-练-测"三位一体设计，帮助普通人在48小时内掌握构建智能对话系统的核心技能。

## 📦 核心功能
1. **零基础入门模板**  
   提供开箱即用的提示词模板库，覆盖文本生成、代码补全、数据分析等7大应用场景，支持GPT-3/4、文心一言等主流大模型接入

2. **交互式学习系统**  
   ```bash
   # 启动Jupyter教学环境
   pip install -r requirements.txt
   jupyter notebook ./tutorials/DayInLife.ipynb
   ```
   通过可视化调试面板实时观察提示词调整对输出的影响，内置30+个常见错误案例库

3. **企业级工程实践**  
   • 基于OpenAI官方指南的提示词评估体系
   • 支持RAG增强的文档问答模板
   • 自动生成API文档的提示词优化工具

## 📚 文档体系
| 模块 | 内容 | 在线演示 |
|------|------|---------|
| 早晨开始 | 需求分析框架 | [Demo](...) |
| 白天工作 | 代码生成模板 | [Demo](...) |
| 晚间闲暇 | 效果评估指南 | [Demo](...) |

完整文档包含：
• 提示词设计六要素检查表
• 温度系数与Top-P参数调优手册
• 企业级应用案例集（含医疗、金融、教育领域）

## 🤝 贡献指南
我们欢迎以下类型的贡献：
1. 提交新的提示词模板（参考`/examples`目录格式）
2. 完善测试用例（使用pytest框架）
3. 翻译文档（目前支持中英双语）

请在提交PR前签署[贡献者协议](CLA.md)，详细流程参见[贡献者指南](CONTRIBUTING.md)

## 📜 开源协议
本项目采用 [MIT License](LICENSE)，允许商业用途但需保留版权声明。引用第三方模型时请遵守对应许可条款

---

> 📞 **联系我们**：issue区优先处理带`[BUG]`/`[FEATURE]`标签的问题，紧急事务请邮件至 hongxin.zhang@gmail.com
