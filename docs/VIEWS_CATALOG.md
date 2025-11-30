# 企業雲端架構視圖目錄 (Architecture Views Catalog)

本文件總結了 `EA-CloudComputing` 模型中的 15 個核心架構視圖。這些視圖依照 **戰略 (Strategy)** 到 **實作 (Implementation)** 的層級進行組織，旨在協助 CIO 與各技術團隊進行溝通與決策。

## 視圖層級與導航

### 🟢 Layer 1: 戰略與治理 (Strategy & Governance)
*定義轉型目標、衡量指標與權責邊界。*

| 視圖名稱 | 檔案連結 | 簡短說明 |
| :--- | :--- | :--- |
| **01. Strategy & Motivation** | [Link](./01_strategy_motivation.md) | 展示雲端轉型的驅動力、戰略目標與指導原則。 |
| **02. Capability Map** | [Link](./02_Capability_Map.md) | 定義核心能力（如 FinOps, MLOps）及其成熟度與 KPI。 |
| **03. Governance & Ownership** | [Link](./03_governance_ownership.md) | 解決「權責不清」問題，定義角色與資產的 RACI 關係。 |
| **04. CCoE Operating Model** | [Link](./04_ccoe_operating_model.md) | 描述雲端卓越中心的運作機制與跨部門協作。 |
| **05. FinOps** | [Link](./05_FinOps.md) | 連結預算、合約與成本優化能力，實現雲端財務管理。 |
| **06. Security & Compliance** | [Link](./06_security_compliance.md) | 定義合規約束（如 GDPR）、資安控制點與法律合約。 |

### 🔵 Layer 2: 規劃與服務 (Planning & Services)
*定義實施路徑與服務目錄。*

| 視圖名稱 | 檔案連結 | 簡短說明 |
| :--- | :--- | :--- |
| **07. Implementation Roadmap** | [Link](./07_implementation_roadmap.md) | 展示從現狀 (As-Is) 到目標 (To-Be) 的遷移時間軸與作業包。 |
| **08. Service Map** | [Link](./08_Service_Map.md) | 企業內部的 IT 服務目錄，依業務、平台、數據領域分類。 |

### 🟠 Layer 3: 邏輯與技術架構 (Logical & Technical)
*展示系統構造與技術堆疊。*

| 視圖名稱 | 檔案連結 | 簡短說明 |
| :--- | :--- | :--- |
| **09. Cloud Platform** | [Link](./09_Cloud_Platform.md) | 多雲混合架構的高階技術概覽，包含運算與資料庫服務。 |
| **10. Hybrid Network Topology**| [Link](./10_hybrid_network_topology.md)| 地端與雲端的網路連接（VPN, Direct Connect）與流量分發。 |
| **11. AI Infrastructure** | [Link](./11_ai_infrastructure.md) | 支撐 GenAI 的底層算力（GPU）、向量庫與 RAG 引擎架構。 |
| **12. DevOps Platform** | [Link](./12_devops_platform.md) | 軟體交付流水線 (CI/CD)、代碼庫與自動化工具鏈。 |

### 🟣 Layer 4: 實作與維運 (Implementation & Operations)
*深入底層配置與數據落地。*

| 視圖名稱 | 檔案連結 | 簡短說明 |
| :--- | :--- | :--- |
| **13. Deployment Topology** | [Link](./13_deployment_topology.md) | 詳細展示 Dev/Test/Prod 環境的邏輯隔離與實體部署。 |
| **14. Run & Observability** | [Link](./14_run_observability.md) | Day 2 維運視角，包含監控堆疊 (APM, Logs) 與告警流程。 |
| **15. Data Physicalization** | [Link](./15_data_physicalization.md) | 將邏輯資料物件映射到物理 schema 與 table 的實作視圖。 |

---