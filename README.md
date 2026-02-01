# ESG Standards Mapping - GRI Criteria List
# ESG 準則對照表 - GRI 指標清單

This repository contains a structured `full_gri.json` file that defines the comprehensive framework of the **GRI (Global Reporting Initiative)** standards. This data serves as the backbone for the **ESG_Systemctl** product's indicator management and data collection.

本倉庫包含一個結構化的 `full_gri.json` 檔案，詳細定義了 **GRI (全球永續報告協會)** 準則的完整架構。此資料作為 **ESG_Systemctl** 產品中指標管理與資料採集的核心基礎。

---

## 📄 File Overview / 檔案概述

The `full_gri.json` uses a hierarchical tree structure to categorize GRI standards into three main series:
`full_gri.json` 採用階層式樹狀結構，將 GRI 準則分為三大系列：

1.  **GRI 200 (Economic / 經濟)**: Economic performance, procurement practices, and anti-corruption.
    (經濟績效、採購實務、反貪腐等)。
2.  **GRI 300 (Environmental / 環境)**: Energy, water, biodiversity, emissions, and waste.
    (能源、水資源、生物多樣性、排放與廢棄物等)。
3.  **GRI 400 (Social / 社會)**: Occupational health and safety, training, human rights, and customer privacy.
    (職業安全衛生、訓練教育、人權評估、客戶隱私等)。

---

## 🏗️ Data Structure / 資料結構

Each node in the JSON contains:
JSON 中的每個節點包含：

- `id`: The standard name or specific disclosure ID (e.g., `GRI 302` or `302-1`).
  (準則名稱或具體揭露編號，例如：`GRI 302` 或 `302-1`)。
- `group`: An identifier for UI categorization or visual styling.
  (用於 UI 分類或視覺化樣式的群組代碼)。
- `children`: Specific sub-indicators or data points required for disclosure.
  (具體的子指標或揭露所需的細項資料點)。

---

## 🚀 Use Cases / 應用場景

- **ESG RAG Knowledge Base**: Used as structured context for the **ESG RAG** system to improve AI retrieval accuracy.
  (**ESG RAG 知識庫**：作為 RAG 系統的結構化上下文，提升 AI 檢索準確度)。
- **SaaS Dashboard**: Acts as the data source for the dark mode dashboard in **ESG_Systemctl**.
  (**SaaS 儀表板**：作為 **ESG_Systemctl** 深色模式儀表板的資料來源)。
- **Report Generation**: Serves as a compliance checklist for generating sustainability reports.
  (**報告生成**：作為生成永續報告書時的合規查核清單)。

---

## 🛠️ Development / 開發備註

This project is built with **React and Vite**. For UI rendering, it is recommended to use recursive components to handle the nested nature of the GRI indicators.
本專案基於 **React 與 Vite** 開發。在 UI 渲染方面，建議使用遞迴組件（Recursive Components）來處理 GRI 指標的巢狀特性。