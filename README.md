# 退休資產、年金與現金流模擬器工具箱 
# Retirement Wealth, Annuity & Cash Flow Simulators Portal

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

[繁體中文](#-繁體中文) | [English](#-english)

---

## 🇭🇰 繁體中文

歡迎使用**退休資產、年金與現金流模擬器工具箱**！本專案提供純前端、無須後端（Serverless）的單頁互動式財務規劃工具，旨在幫助使用者評估資產積累、通脹（Inflation）、資產配置（Asset Allocation）、固定收益債券梯、香港年金（HKMC Annuity）及香港社署長者生活津貼（OALA）對長期「實質購買力」的動態影響。

### 🌐 線上工具體驗 (Live Demos)

1. **📈 工具一：長期儲蓄與實質購買力積累模擬器**[span_1](start_span)[span_1](end_span)
   * **檔名：** `Wealth_Accum_Simulator.html`[span_2](start_span)[span_2](end_span)
   * **定位：** 資產積累模型（退休前儲蓄與投資期）。[span_3](start_span)[span_3](end_span)
   * **核心功能：** 模擬定期定額投入、股債資產配置，在考慮預期通脹率與購買力折損下，動態評估名目總資產與「實質購買力（折現後）」的累積演變過程，並支援瀏覽器本地參數記憶。[span_4](start_span)[span_4](end_span)

2. **📊 工具二：退休資產與實質購買力提領模擬器**[span_5](start_span)[span_5](end_span)
   * **檔名：** `asset_withdrawal_simulator.html`[span_6](start_span)[span_6](end_span)
   * **定位：** 通用財務模型（適用於全球／跨國退休提領規劃）。[span_7](start_span)[span_7](end_span)
   * **核心功能：** 評估股票與債券資產組合，在考慮預期通脹率與購買力折損下，動態模擬提領金額演變與 4% 提領法則（4% Rule）的安全邊界。[span_8](start_span)[span_8](end_span)

3. **🛡️ 工具三：滾動債券梯與固定收益現金流模擬器 (v0.2)**[span_9](start_span)[span_9](end_span)
   * **檔名：** `bond_ladder_simulator.html`[span_10](start_span)[span_10](end_span)
   * **定位：** 進階固定收益策略模型。[span_11](start_span)[span_11](end_span)
   * **核心功能：** 專為鎖定固定現金流設計，支援 **6 個月短期緩衝池（T-bills）獨立配置**、精確月份梯隊間距、長天期債券末端延伸（10 年期長債鎖定），以及通脹動態調升機制，全面提升退休現金流的防禦力與穩健度。[span_12](start_span)[span_12](end_span)

4. **🇭🇰 工具四：香港年金 + 長生津與實質購買力模擬器 (2026)**[span_13](start_span)[span_13](end_span)
   * **檔名：** `hkmc_oala_simulator.html`[span_14](start_span)[span_14](end_span)
   * **定位：** 香港在地化專用模型（符合 2026 政策標準）。[span_15](start_span)[span_15](end_span)
   * **核心功能：** 整合香港年金計劃（HKMC）、社會福利署長者生活津貼（OALA）資產／收入審查機制與私人股債收益，動態計算每個月實質可用的現金流與資格變化。[span_16](start_span)[span_16](end_span)

### ✨ 專案亮點
* **完全隱私安全：** 所有計算均在使用者瀏覽器本地執行，絕不上傳任何個人財務數據。[span_17](start_span)[span_17](end_span)
* **零依賴輕量化：** 純 HTML5 / CSS3 / JavaScript 開發，支援響應式設計（RWD），手機與電腦皆可流暢操作。[span_18](start_span)[span_18](end_span)
* **高視覺化：** 內建動態圖表，實時呈現名義價值與實質購買力（Inflation-adjusted）的演變曲線。[span_19](start_span)[span_19](end_span)

---

## 🇬🇧 English

Welcome to the **Retirement Wealth, Annuity & Cash Flow Simulators Portal**! This repository hosts pure client-side, interactive web tools designed to help individuals evaluate the long-term impact of asset accumulation, inflation, asset allocation, bond laddering, public/private annuities, and government welfare subsidies on real purchasing power.[span_20](start_span)[span_20](end_span)

### 🌐 Interactive Tools

1. **📈 Simulator 1: Wealth Accumulation & Real Purchasing Power Simulator**[span_21](start_span)[span_21](end_span)
   * **Filename:** `Wealth_Accum_Simulator.html`[span_22](start_span)[span_22](end_span)
   * **Scope:** Accumulation phase model (pre-retirement savings and investments).[span_23](start_span)[span_23](end_span)
   * **Key Features:** Simulates regular savings growth, stock/bond portfolio allocations, dynamic contribution escalation, real purchasing power trajectory adjusted for inflation discount rates, and local parameter persistence.[span_24](start_span)[span_24](end_span)

2. **📊 Simulator 2: Retirement Asset & Purchasing Power Drawdown Simulator**[span_25](start_span)[span_25](end_span)
   * **Filename:** `asset_withdrawal_simulator.html`[span_26](start_span)[span_26](end_span)
   * **Scope:** Universal financial model for general retirement decumulation planning.[span_27](start_span)[span_27](end_span)
   * **Key Features:** Simulates stock/bond portfolio sustainability, dynamic withdrawal rates (including Trinity Study 4% Rule benchmarking), and purchasing power erosion caused by inflation.[span_28](start_span)[span_28](end_span)

3. **🛡️ Simulator 3: Bond Ladder & Fixed Income Cash Flow Simulator (v0.2)**[span_29](start_span)[span_29](end_span)
   * **Filename:** `bond_ladder_simulator.html`[span_30](start_span)[span_30](end_span)
   * **Scope:** Advanced fixed-income strategy model.[span_31](start_span)[span_31](end_span)
   * **Key Features:** Designed for predictable cash flows, supporting **6-month short-term buffer pool (T-bills) allocation**, refined month-interval ladder spacing, long-end bond extension (up to 10-year maturity locking), and inflation-adjusted payout projections.[span_32](start_span)[span_32](end_span)

4. **🇭🇰 Simulator 4: HKMC Annuity + OALA Cash Flow Simulator**[span_33](start_span)[span_33](end_span)
   * **Filename:** `hkmc_oala_simulator.html`[span_34](start_span)[span_34](end_span)
   * **Scope:** Hong Kong-specific retirement planning model (Updated for 2026 rules).[span_35](start_span)[span_35](end_span)
   * **Key Features:** Combines Hong Kong Mortgage Corporation (HKMC) Annuity, Social Welfare Department Old Age Living Allowance (OALA) means testing thresholds, and private investment yields to dynamically project real monthly cash flows.[span_36](start_span)[span_36](end_span)

### ✨ Highlights
* **100% Privacy Focused:** Client-side calculations only. No financial data is ever collected or transmitted to external servers.[span_37](start_span)[span_37](end_span)
* **Lightweight & Responsive:** Built with vanilla HTML5, CSS3, and JavaScript with Responsive Web Design (RWD) for desktop and mobile devices.[span_38](start_span)[span_38](end_span)
* **Rich Data Visualization:** Interactive dynamic charts comparing Nominal vs. Real Purchasing Power trajectories.[span_39](start_span)[span_39](end_span)

---

## 🛠️ 檔案結構 (Project Structure)

```text
.
├── index.html                       # 入口首頁 / Portal Page
├── Wealth_Accum_Simulator.html      # 工具一：資產積累模擬器 / Simulator 1
├── asset_withdrawal_simulator.html  # 工具二：通用提領模擬器 / Simulator 2
├── bond_ladder_simulator.html       # 工具三：債券梯模擬器 (v0.2) / Simulator 3
├── hkmc_oala_simulator.html         # 工具四：香港年金長生津模擬器 / Simulator 4
└── README.md                        # 專案說明文件 / Documentation
