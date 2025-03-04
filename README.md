# Generative AI 中文化

這份正體中文是翻譯自 Google 官方在 [Generative AI on Vertex AI Cookbook](https://cloud.google.com/vertex-ai/generative-ai/docs/cookbook) 列出來的範例。

## 分類
### Gemini Quickstarts
- Get Started with the Multimodal Live API ([原文](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/multimodal-live-api/intro_multimodal_live_api_genai_sdk.ipynb)) ([中文](./gemini/intro_multimodal_live_api_genai_sdk.ipynb))
- Intro to Vertex AI RAG Engine ([原文](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/rag-engine/intro_rag_engine.ipynb)) ([中文](./gemini/intro_rag_engine.ipynb))

### Featured Tutorials

## 翻譯說明

內容的翻譯經 Gemini 2.0 Flash Lite 翻譯，再由個人檢查後完成。如果和原文有出入，請以官方原文為標準。

### 名詞翻譯的原則

有些名詞會根據狀況翻譯或不翻譯
#### 有翻譯
- 會在一開始翻完後括號原文，下文會根據語意保持原文或是翻譯。舉列：
```
對話（sesseion）
```

#### 不翻譯
- 該名詞可能是伺服的名稱。舉例：Multimodal Live API
- 該名詞不翻譯比較易於了解。舉例：Prompt
 
### 不翻譯的名詞說明
1. notebook
Google Colab 是 Google 基於 Jupyter Notebook service 來架設的平臺，而 Notebook 是每份程式流程的檔案單位，雖然可以翻成筆記本，但如果把它視為這個服務上的檔案單位，不翻譯會比較容易理解。
2. Prompt
現在於大型語言模型的領域中，多翻為「提示/提示詞」。
