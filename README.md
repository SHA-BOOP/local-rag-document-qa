# 本地大模型文档智能问答系统

## 项目简介
基于本地开源大模型Qwen2.5-7B构建的企业内部文档智能问答系统，支持PDF、Word、Excel多格式文档上传与智能问答，无需联网，完全本地运行，保护企业数据安全。

## 技术栈
- 编程语言：Python 3.10
- 大模型框架：LangChain
- 本地大模型部署：LM Studio
- 大模型：通义千问Qwen2.5-7B-Instruct
- 文档解析：PyPDF2、python-docx、pandas

## 功能特点
- ✅ 支持PDF、Word(.docx)、Excel(.xlsx)多格式文档
- ✅ 完全本地运行，无需联网，数据安全
- ✅ 精准问答，基于文档内容回答，无幻觉
- ✅ 支持任意长度文档（受限于大模型上下文窗口）

## 使用方法
1.  安装依赖：`pip install langchain-openai langchain-community python-docx pandas`
2.  启动LM Studio，加载Qwen2.5-7B模型，开启API服务
3.  运行代码：`python proof.py`
4.  输入文档路径，开始提问

## 运行效果
![运行截图](screenshot.png)
