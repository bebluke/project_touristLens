# TouristLens

TouristLens 是一個基於景點評論資料，結合資料分析、自然語言處理及推薦系統的專案，旨在提升台灣觀光產業的競爭力。

TouristLens is a project that leverages attraction reviews, data analysis, natural language processing, and recommendation systems to enhance the competitiveness of Taiwan's tourism industry.

## 專案目標 (Project Goals)

- 探討不同語系外籍旅客的旅遊行為與偏好。  
Explore travel behaviors and preferences of foreign tourists across different language groups.

- 分析景點評論資料，掌握旅客的需求與抱怨。  
Analyze attraction reviews to identify tourists' needs and complaints.

- 提供資料驅動的改善建議，協助旅遊業者優化景點管理與產品設計。  
Provide data-driven recommendations to assist tourism operators in optimizing attraction management and product design.

## 功能特色 (Features)

- 多語系評論的語意檢索與分析 (Multilingual semantic retrieval and analysis of reviews)
- 透過負面詞彙識別熱門景點問題 (Identify popular attraction issues through negative sentiment analysis)
- 旅客偏好與隱藏旅遊組合的挖掘 (Discover tourist preferences and hidden travel combinations)
- 整合分析成果，提供客製化推薦 (Integrate analysis results for customized recommendations)

## 技術架構 (Technical Architecture)

- **資料儲存與檢索 (Data Storage & Retrieval)**: Elasticsearch
- **語意搜尋與向量化 (Semantic Search & Embedding)**: MPNet-base, FAISS
- **自然語言處理 (Natural Language Processing)**: 
  - 負面詞彙分析 (Negative sentiment analysis): twitter-xlm-roberta-base-sentiment
  - 主題詞彙萃取 (Topic extraction): BGE-M3

## 如何使用 (Getting Started)

1. **Clone 本專案至本機端。(Clone this project to your local machine)**
2. **安裝必要套件。(Install the required packages)**
3. 執行資料分析與檢索系統，獲取推薦結果。(Run the data analysis and retrieval system to obtain recommendations)

## 聯絡資訊 (Contact)

如有任何問題或合作需求，歡迎聯繫專案團隊。

For inquiries or collaboration, feel free to contact our project team.

## 授權條款 (License)

本專案以 MIT License 授權開放使用。

This project is licensed under the MIT License.

