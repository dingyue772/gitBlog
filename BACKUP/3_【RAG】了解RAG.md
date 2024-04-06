# [【RAG】了解RAG](https://github.com/dingyue772/gitBlog/issues/3)

# RAG
![image](https://github.com/dingyue772/gitBlog/assets/90541495/20a0c03d-a036-41c6-ac5b-2e00a04cc04c)
## InternLM+LangChain搭建RAG应用
**工具包**
开源词向量模型：Sentence Transformer（相对轻量、支持中文且效果较好）
NLTK相关资源

**搭建向量知识库**
知识库文件——FileLoader对象加载文件——分块、向量化、数据库存储

**将LLM接入LangChain**
基于本地部署的LLM自定义LLM类，即继承LangChain.llms.base.LLM 类
模型优化：使用混合模型——本地模型和云端模型API相结合

**检索问答链构建**
加载向量数据库——实例化自定义LLM和Prompt Template——构建检索问答链
检索优化：使用图检索、网页搜索进行优化