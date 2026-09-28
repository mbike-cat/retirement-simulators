# 退休資產、年金與現金流模擬器工具箱 
# Retirement Wealth, Annuity & Cash Flow Simulators Portal

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

[繁體中文](#-繁體中文) | [English](#-english)

---

## 🇭🇰 繁體中文

歡迎使用**退休資產、年金與現金流模擬器工具箱**！本專案提供純前端、無須後端（Serverless）的單頁互動式財務規劃工具，旨在幫助使用者評估資產積累、通脹（Inflation）、資產配置（Asset Allocation）、固定收益債券梯、香港年金（HKMC Annuity）及香港社署長者生活津貼（OALA）對長期「實質購買力」的動態影響。

### 🌐 線上工具體驗 (Live Demos)

1. **📈 工具一：長期儲蓄與實質購買力積累模擬器**
   * **檔名：** `Wealth_Accum_Simulator.html`
   * **定位：** 資產積累模型（退休前儲蓄與投資期）。
   * **核心功能：** 模擬定期定額投入、股債資產配置，在考慮預期通脹率與購買力折損下，動態評估名目總資產與「實質購買力（折現後）」的累積演變過程，並支援瀏覽器本地參數記憶。

2. **📊 工具二：退休資產與實質購買力提領模擬器**
   * **檔名：** `asset_withdrawal_simulator.html`
   * **定位：** 通用財務模型（適用於全球／跨國退休提領規劃）。
   * **核心功能：** 評估股票與債券資產組合，在考慮預期通脹率與購買力折損下，動態模擬提領金額演變與 4% 提領法則（4% Rule）的安全邊界。

3. **🛡️ 工具三：滾動債券梯與固定收益現金流模擬器**
   * **檔名：** `bond_ladder_simulator.html`
   * **定位：** 進階固定收益策略模型。
   * **核心功能：** 專為鎖定固定現金流設計，模擬透過美國國債梯（Bond Laddering）到期劃撥與股債提領順序，觀察退休期間資金池的防禦力與提領穩定度。

4. **🇭🇰 工具四：香港年金 + 長生津與實質購買力模擬器 (2026)**
   * **檔名：** `hkmc_oala_simulator.html`
   * **定位：** 香港在地化專用模型（符合 2026 政策標準）。
   * **核心功能：** 整合香港年金計劃（HKMC）、社會福利署長者生活津貼（OALA）資產／收入審查機制與私人股債收益，動態計算每個月實質可用的現金流與資格變化。

### ✨ 專案亮點
* **完全隱私安全：** 所有計算均在使用者瀏覽器本地執行，絕不上傳任何個人財務數據。
* **零依賴輕量化：** 純 HTML5 / CSS3 / JavaScript 開發，支援響應式設計（RWD），手機與電腦皆可流暢操作。
* **高視覺化：** 內建動態圖表，實時呈現名義價值與實質購買力（Inflation-adjusted）的演變曲線。

---

## 🇬🇧 English

Welcome to the **Retirement Wealth, Annuity & Cash Flow Simulators Portal**! This repository hosts pure client-side, interactive web tools designed to help individuals evaluate the long-term impact of asset accumulation, inflation, asset allocation, bond laddering, public/private annuities, and government welfare subsidies on real purchasing power.

### 🌐 Interactive Tools

1. **📈 Simulator 1: Wealth Accumulation & Real Purchasing Power Simulator**
   * **Filename:** `Wealth_Accum_Simulator.html`
   * **Scope:** Accumulation phase model (pre-retirement savings and investments).
   * **Key Features:** Simulates regular savings growth, stock/bond portfolio allocations, dynamic contribution escalation, real purchasing power trajectory adjusted for inflation discount rates, and local parameter persistence.

2. **📊 Simulator 2: Retirement Asset & Purchasing Power Drawdown Simulator**
   * **Filename:** `asset_withdrawal_simulator.html`
   * **Scope:** Universal financial model for general retirement decumulation planning.
   * **Key Features:** Simulates stock/bond portfolio sustainability, dynamic withdrawal rates (including Trinity Study 4% Rule benchmarking), and purchasing power erosion caused by inflation.

3. **🛡️ Simulator 3: Bond Ladder & Fixed Income Cash Flow Simulator**
   * **Filename:** `bond_ladder_simulator.html`
   * **Scope:** Advanced fixed-income strategy model.
   * **Key Features:** Designed for locking predictable cash flows through US Treasury bond laddering and structured asset decumulation sequencing to enhance retirement portfolio defense.

4. **🇭🇰 Simulator 4: HKMC Annuity + OALA Cash Flow Simulator**
   * **Filename:** `hkmc_oala_simulator.html`
   * **Scope:** Hong Kong-specific retirement planning model (Updated for 2026 rules).
   * **Key Features:** Combines Hong Kong Mortgage Corporation (HKMC) Annuity, Social Welfare Department Old Age Living Allowance (OALA) means testing thresholds, and private investment yields to dynamically project real monthly cash flows.

### ✨ Highlights
* **100% Privacy Focused:** Client-side calculations only. No financial data is ever collected or transmitted to external servers.
* **Lightweight & Responsive:** Built with vanilla HTML5, CSS3, and JavaScript with Responsive Web Design (RWD) for desktop and mobile devices.
* **Rich Data Visualization:** Interactive dynamic charts comparing Nominal vs. Real Purchasing Power trajectories.

---

## 🛠️ 檔案結構 (Project Structure)

```text
.
├── index.html                       # 入口首頁 / Portal Page
├── Wealth_Accum_Simulator.html      # 工具一：資產積累模擬器 / Simulator 1
├── asset_withdrawal_simulator.html  # 工具二：通用提領模擬器 / Simulator 2
├── bond_ladder_simulator.html       # 工具三：債券梯模擬器 / Simulator 3
├── hkmc_oala_simulator.html         # 工具四：香港年金長生津模擬器 / Simulator 4
└── README.md                        # 專案說明文件 / Documentation
