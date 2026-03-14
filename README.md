**online version**: https://udify.app/workflow/e9V0ffJVzFuHajtG

#  AI職位匹配程度估算器 (AI Job Match Analyzer)

這是一個基於**Dify**工作流引擎開發的高精度求職輔助系統。

## 核心功能
- **全格式 JD 抓取**：整合 Firecrawl 技術，自動解析動態網頁與各種格式的職位描述。
- **異構 AI 整合**：協同 LLM (Gemini/GPT) 與 Hugging Face 開源 Reranker 模型進行深度比對。
- **精準匹配報告**：產出量化的匹配分數與具體的職能缺口建議。

## 技術架構
- **Workflow Engine**: Dify
- **Core LLM**: Gemini 1.5 Pro / GPT-5
- **Reranking Model**: BAAI/bge-reranker-v2-m3 (via Hugging Face API)
- **Data Scraping**: Firecrawl (SCRAPE node)

## 使用說明
1. 下載本倉庫的 `.yml` DSL 檔案。
2. 匯入至您的 Dify 環境中即可運行。
