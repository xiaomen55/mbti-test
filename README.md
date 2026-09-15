# MBTI 性格测评工具集

纯前端、零依赖的中文 MBTI 性格测评工具集合，全部功能在浏览器本地完成，无任何网络请求，答题数据仅保存在本地。

## 在线使用

访问 GitHub Pages：**https://xiaomen55.github.io/mbti-test/**

| 版本 | 文件 | 说明 |
|------|------|------|
| 90 题完整版 | [mbti-full.html](mbti-full.html) | 16Personalities 风格，五维度计分（E/I、S/N、T/F、J/P + A/T），深度报告、中断续答、历史对比 |
| 20 题快测版 | [mbti-quick.html](mbti-quick.html) | 四维度各 5 题，约 3 分钟，结果含四字母含义解释 |
| 交互原型 | [mbti-prototype.html](mbti-prototype.html) | 带 PRD 需求标注（FR-01~FR-11）与演示快捷键的评审原型 |

## 项目文档

- [SPEC v1.0（需求规格说明）](docs/mbti-spec-v1.0.docx)
- [PRD v1.0（产品需求文档）](docs/mbti-prd-v1.0.docx)

## 技术特点

- 纯原生 HTML/CSS/JS 单文件，零外部依赖（图标为内联 SVG）
- localStorage 本地持久化，双击即运行
- 响应式设计，桌面与手机均可使用

## 免责声明

本测评仅供娱乐和自我了解，不构成心理诊断或专业建议。
