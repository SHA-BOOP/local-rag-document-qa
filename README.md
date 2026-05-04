# local-rag-document-qa
基于本地开源大模型的企业内部文档智能问答系统

## ✨ 项目简介
本项目是一个**完全本地化、数据隐私安全**的RAG文档问答工具，支持加载PDF/Word/Excel多格式文档，调用本地部署的大模型实现问答，无需依赖OpenAI等第三方API。

## 🛠️ 技术栈
- Python 3.10
- LangChain（文档解析+大模型调用）
- LM Studio（本地大模型部署，使用qwen2.5-7b-instruct-uncensored）
- PyPDFLoader/python-docx/openpyxl（多格式文档加载）
- Pandas（Excel数据处理）

## 🚀 快速运行
### 1. 安装依赖
```bash
# 用你本地的Python执行
python -m pip install -r requirements.txt
