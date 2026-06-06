# 🗄️ AI Vector Tools

AI向量工具，支持向量数据库、嵌入、相似度搜索。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🏗️ 向量数据库设计
- 🔵 ChromaDB配置
- 🔍 相似度搜索设计
- 🔎 RAG管道生成
- ⚡ 向量搜索优化
- ⚖️ 数据库比较

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_vector_tools import create_tools

tools = create_tools()

# 向量数据库设计
db = tools.design_vector_db("RAG应用", "中型")

# ChromaDB配置
chroma = tools.generate_chroma_config("知识库", documents)

# 相似度搜索
similarity = tools.design_similarity_search("电商")

# RAG管道
rag = tools.generate_rag_pipeline("知识库", "GPT-4")

# 搜索优化
optimized = tools.optimize_vector_search(config, metrics)

# 数据库比较
comparison = tools.compare_vector_databases(["高性能", "低成本"])
```

## 📁 项目结构

```
ai-vector-tools/
├── tools.py       # 向量工具核心
└── README.md
```

## 📄 许可证

MIT License
