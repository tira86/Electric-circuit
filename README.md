# BLSA & OCSA DRAM Circuit Lab

An interactive, self-contained teaching lab for exploring conventional bit-line sense amplifiers (BLSA) and offset-cancellation sense amplifiers (OCSA) in DRAM.

The entire lab runs from one HTML file. It includes a complete English version rewritten for technical clarity and a Traditional Chinese version, with an in-app language switch that remembers the selected language.

## Open the lab

[Open `BLSA&OCSA.html`](BLSA%26OCSA.html)

Download the file and open it in a modern browser. No installation, build step, or internet connection is required for the simulations. External reference links still require network access.

## What is included

- Interactive BLSA and OCSA circuit views
- 17 read, write, precharge, refresh, timing, and offset-comparison cases
- 16 progressive lessons, from capacitors and MOS devices to complete DRAM operations
- Step-by-step ACT, READ, WRITE, PRE, and REF animation
- Live node voltages, branch currents, formulas, timing checks, and waveforms
- Clickable component explanations and a DRAM glossary
- Full-flow guide for read, write, write/readback, and refresh stories
- MOS and equivalent-switch display modes
- Traditional Chinese and English in the same offline file

## Educational scope

This project is a circuit-level teaching model, not a production DRAM implementation or a JEDEC compliance tool. Capacitances, transistor parameters, internal voltages, leakage, timing thresholds, and decision margins are selected to make circuit behavior visible. Real values depend on process, density, speed grade, mode-register settings, topology, PVT conditions, and the complete command sequence.

The model does not reproduce a full external DDR5 PHY, package effects, DQ/DQS serialization, every command constraint, or all bank/rank scheduling behavior.

## References

- JEDEC, `JESD79-5C_v1.30`
- *DRAM Circuit Design: Fundamental and High-Speed Topics*, Section 1.2
- Offset-cancellation topology concepts from US Patent [US20200227111A1](https://patents.google.com/patent/US20200227111A1/en)

## Repository layout

- `BLSA&OCSA.html` - complete bilingual offline lab
- `README.md` - project overview and usage notes

---

## 繁體中文

# BLSA 與 OCSA DRAM 電路實驗室

這是一套互動式 DRAM 電路教學工具，用來理解傳統位線感測放大器（BLSA）與偏移消除感測放大器（OCSA）的工作原理。

整個實驗室整合在單一 HTML 檔案中，包含繁體中文與由人工重新撰寫的完整英文內容。頁面內可直接切換語言，並會記住上次選擇。

## 開啟實驗室

[開啟 `BLSA&OCSA.html`](BLSA%26OCSA.html)

下載後以現代瀏覽器直接開啟即可。模擬功能不需安裝、不需建置，也不需網路；外部參考連結仍需連線。

## 內容特色

- 可互動的 BLSA 與 OCSA 電路圖
- 17 個讀取、寫入、預充電、刷新、時序與偏移比較案例
- 16 課循序教學，從電容、MOS 一直到完整 DRAM 操作
- ACT、READ、WRITE、PRE、REF 分階段動畫
- 即時節點電壓、支路電流、公式、時序檢查與波形
- 可點選的元件詳解與 DRAM 名詞表
- 讀取、寫入、寫後讀回與刷新的完整流程導覽
- MOS 與等效開關顯示模式
- 同一離線檔案內切換繁體中文與英文

## 教學模型範圍

本專案是電路層級的教學模型，不是量產 DRAM 實作，也不能作為 JEDEC 合規判定工具。電容、電晶體參數、內部電壓、漏電、時序門檻與判讀裕量皆以清楚呈現電路行為為目的；實際數值會受到製程、密度、速度等級、Mode Register、電路拓撲、PVT 條件與完整命令序列影響。

模型未重現完整 DDR5 外部 PHY、封裝效應、DQ/DQS 序列化、所有命令限制，以及完整的 bank/rank 排程。

## 參考資料

- JEDEC `JESD79-5C_v1.30`
- *DRAM Circuit Design: Fundamental and High-Speed Topics* 第 1.2 節
- OCSA 拓撲概念參考美國專利 [US20200227111A1](https://patents.google.com/patent/US20200227111A1/en)

## 儲存庫內容

- `BLSA&OCSA.html`：完整中英雙語離線實驗室
- `README.md`：專案介紹與使用說明
