# Hi, I'm Shawn Huang 👋

**Data Engineer | Network Systems Developer | Full-Stack Engineer**

專注於 **Linux 低階網路系統開發** 與 **資料工程 / 混合檢索 (Hybrid Search & RAG) 架構設計**。具備獨立研發 DHCP 伺服器模組、非同步高效微服務管線建置，以及機房伺服器叢集運維經驗。

[![Portfolio](https://img.shields.io/badge/Portfolio-shawnhuang125.github.io-black?style=flat-square&logo=google-chrome)](https://shawnhuang125.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Shawn%20Huang-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/luchia-huang-a9ba88381/)
[![Email](https://img.shields.io/badge/Email-s0909799081%40gmail.com-red?style=flat-square&logo=gmail)](mailto:s0909799081@gmail.com)

---

### 🛠️ Core Competencies & Tech Stack

![Low-Level Networking](https://img.shields.io/badge/Low--Level%20Networking-orange?style=flat-square) 
![AI & Search Architecture](https://img.shields.io/badge/AI%20%26%20Search%20Architecture-red?style=flat-square) 
![Information Retrieval](https://img.shields.io/badge/Information%20Retrieval-navy?style=flat-square) 
![Data Engineering](https://img.shields.io/badge/Data%20Engineering-blue?style=flat-square) 
![Infrastructure & DevOps](https://img.shields.io/badge/Infrastructure%20%26%20DevOps-green?style=flat-square) 
![IoT & Embedded](https://img.shields.io/badge/IoT%20%26%20Embedded-yellow?style=flat-square)

- **Languages:** C, Python 3.12, SQL, Bash
- **Backend & Frameworks:** FastAPI, ASGI, SQLAlchemy, aiomysql, Flask
- **Data & AI/RAG:** Qdrant (Vector DB), MySQL, Redis, BGE-M3, Hybrid Search, Two-Stage Pipeline
- **System & DevOps:** Linux, Docker & Docker-Compose, XCP-ng, Git/GitHub, GCP APIs, FFmpeg

---

### 💼 Experience

#### 🔹 專題組長 & 系統架構開發 ｜ AI 美食聊天機器人 `2025.01 - Present`
- **團隊領導與資源爭取：** 領導 4 人團隊，主導開發規格文件與 Git 工作流；成功爭取獨立研究空間與兩張 RTX 4060 Ti (32,000 $NT) 算力設備。
- **混合檢索與精排架構 (Hybrid Search & RAG)：**
  - 設計「先過濾後檢索」二階段微服務 (FastAPI + aiomysql)，吞吐量顯著提升。
  - 整合 **Qdrant** 與 **BGE-M3** 實作多維向量解耦與軟性屏蔽 (Soft Masking)。
  - 研發非線性對數流形幾何精排演算法 (Weighted Geometric Mean)，根絕單項缺失店家惡性墊檔。
  - 導入 Redis 快取機制 (`search_ssid`)，降低 80%+ 重複向量運算負載。
- **內部工具與平台：** 獨立開發客製化 DBMS Console（整合 GIS 與 RBAC）與 Python GUI 標記工具，驅動完成數千筆高精準度 Ground Truth 數據入庫。

#### 🔹 軟體測試工程師實習生 ｜ 森淨科技 `2025.07 - 2025.08`
- 執行 Web 功能測試與 Postman API 自動化/手動測試，撰寫品質檢驗報告並協同團隊定位 Defect。

#### 🔹 CTF 平台運維人員 ｜ 資通安全實務人才培育計畫 `2024.02 - 2025.02`
- 維運機房 XCP-ng 虛擬化叢集與網路基礎設施，運用 Docker 快速封裝部署資安競賽靶機環境。

---

### 🚀 Featured Projects

| 專案名稱 | 技術棧 | 描述 | 相關連結 |
| :--- | :--- | :--- | :--- |
| **HROUTE** | `C` `Linux` `Networking` | 獨立開發的輕量化 Linux 路由框架，實作 DHCP 核心引擎與 NAT 轉發機制。 | [Code](https://github.com/shawnhuang125/router) · [Demo](https://www.youtube.com/watch?v=f66AXxM5Rpo) |
| **Search API for AI RAG** | `Python` `FastAPI` `Qdrant` | 混合檢索微服務，整合 RDBMS 結構化剛性篩選與向量語意召回，並採幾何重排演算法。 | [Code](https://github.com/shawnhuang125/Search_API) · [Demo](https://youtu.be/QhcSO8ZEuds) |
| **Custom DBMS Console** | `FastAPI` `AJAX` `MySQL` | 整合式管理後台，支援 MySQL 與 Qdrant 雙庫同步維運、GIS 地圖視覺化與批次標記。 | [Code](https://github.com/shawnhuang125/map-api-application) · [Demo](https://youtu.be/W34ugY3443A) |
| **Business_API** | `FastAPI` `SQLAlchemy` | 專為減少 RAG Token 消耗與優化商業查詢打造的後端微服務。 | [Code](https://github.com/shawnhuang125/business_api) |
| **Google Map ETL** | `Python` `Google APIs` | 自動化資料採集與清洗管線，負責非結構化餐飲評論與屬性結構化入庫。 | [Code](https://github.com/shawnhuang125/Graduation-Project) |
| **Review Labeling Tool** | `Python` `tkinter` | 具備人機協同 (Human-in-the-loop) 機制的桌面標記輔助 GUI，支援批量語意錄入。 | [Code](https://github.com/shawnhuang125/Data_Labeling_Assistant) |
| **IoT Door Monitor** | `C` `ESP32` `Flask` | 基於 ESP32 的門磁感測物聯網監控系統，整合 Telegram Bot 即時告警。 | [Code](https://github.com/shawnhuang125/Magnetic_Door_Monitoring_System) |
| **Media Downloader** | `Python` `FFmpeg` `yt-dlp` | 跨平台多媒體影音轉換與批次下載桌面 GUI 工具。 | [Code](https://github.com/shawnhuang125/x.com_converter) |

---

### 📜 Certifications

- **IPAS 資訊安全工程師 - 初級** (2024.11)
- **TQC-OS Linux 系統管理 - 專業級** (2024.11)

---

### 📫 Connect with Me

- **Personal Portfolio:** [shawnhuang125.github.io](https://shawnhuang125.github.io/)
- **LinkedIn:** [Shawn Huang](https://www.linkedin.com/in/luchia-huang-a9ba88381/)
- **Email:** [s0909799081@gmail.com](mailto:s0909799081@gmail.com)
