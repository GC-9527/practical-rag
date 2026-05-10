# Practical RAG

RAG（Retrieval-Augmented Generation，检索增强生成）技术实战项目集合。

## 项目介绍

本项目包含多个RAG技术实战案例，涵盖了从基础的Embedding使用到完整的ChatPDF系统。

## 项目结构

```
practical-rag/
├── CASE-ChatPDF-Faiss/     # ChatPDF与Faiss向量数据库
├── CASE-embedding使用/       # Embedding模型使用
├── CASEA-Query改写/         # Query查询改写
└── 1-RAG技术与应用.pdf       # 理论文档
```

## 案例详解

### 1. CASE-ChatPDF-Faiss

基于Faiss向量数据库的ChatPDF系统。

**功能特点：
- PDF文档解析和向量化
- Faiss向量存储和检索
- RAG对话系统

**文件结构：
- `chatpdf-faiss.ipynb` - Jupyter notebook
- `chatpdf-faiss.py` - Python脚本
- `requirements.txt` - 依赖列表

### 2. CASE-embedding使用

Embedding模型使用案例。

**包含模型：
- BGE-M3
- GTE-Qwen2

**功能：
- Embedding向量生成
- 语义相似度计算
- 矩阵乘法详解

### 3. CASEA-Query改写

Query查询优化技术。

**功能：
- Query意图识别
- 多Query生成
- 联网搜索增强

## 快速开始

### 环境配置

每个案例都有独立的`requirements.txt`，可以单独安装依赖：

```bash
cd CASE-ChatPDF-Faiss
pip install -r requirements.txt
```

### 运行示例

1. **ChatPDF系统
```bash
cd CASE-ChatPDF-Faiss
python chatpdf-faiss.py
```

2. **Embedding示例
```bash
cd CASE-embedding使用
python bge-m3使用.py
```

3. **Query改写
```bash
cd CASEA-Query改写
python 1-Query改写.py
```

## 技术栈

- **向量数据库** - Faiss
- **Embedding** - BGE, GTE-Qwen2
- **LLM** - Qwen等大模型
- **框架** - LangChain等

## 学习路径

1. 先学习`CASE-embedding使用` - 理解向量表示
2. 再学习`CASEA-Query改写` - 掌握查询优化
3. 最后学习`CASE-ChatPDF-Faiss` - 构建完整系统

## 注意事项

- 向量数据库文件不会提交到git
- 大模型API密钥请配置环境变量
- PDF等文档文件也会被忽略
