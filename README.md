\# Simple RAG Chatbot (OpenAI API)



\## 概要

OpenAI APIを用いて、FAQ検索型の簡易RAGシステムを実装しました。



\## 使用技術

\- Python

\- OpenAI API

\- text-embedding-3-small

\- gpt-4o-mini

\- NumPy



\## 処理の流れ

1\. FAQをEmbeddingでベクトル化

2\. ユーザー質問をEmbedding化

3\. コサイン類似度で最も近いFAQを検索

4\. 該当FAQをLLMに渡して回答生成



\## 工夫した点

\- cosine similarityによる意味検索

\- FAQのみを根拠に回答するようプロンプト設計

\- 類似度閾値による誤回答防止（※実装していれば）



\## 今後の改善案

\- 上位複数件検索

\- ベクトルDB導入

\- UI実装（Streamlitなど）

