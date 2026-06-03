# 05_MVP 建議與待驗證假設：程式產出計畫

## Summary

本計畫用於產出 `05_MVP 建議與待驗證假設.md`。目前已符合進入 05 的條件：`04_User Stories.md` 已完成人工審核後整理，形成 7 則核心 User Stories，且 `US-04 查看等待狀態與替代建議` 已延後到 05 MVP 判斷，不阻塞下一階段。

本階段可由程式產出 MVP 排序建議、支持數據、待驗證假設與簡短參考平台觀察，但最終 MVP 優先級仍需人工判讀。

## Key Changes

- 建立 `05_MVP 建議與待驗證假設.md`。
- 採用 MoSCoW 四欄排序：
  - `Must-have`：第一版若不做，主要產品假設難以成立。
  - `Should-have`：重要但可簡化或延後，不應完全忽略。
  - `Could-have`：有幫助但證據較弱、成本較高或可後續補強。
  - `Won’t-have now`：第一版明確不做，但保留原因與後續條件。
- 依 `Progress-decision.md` 的可程式產出範圍完成：
  - 根據問卷支持度與風險產生 MoSCoW 初稿。
  - 標註每個功能的支持數據與對應 User Story。
  - 產出待驗證假設。
  - 整理簡短參考平台觀察欄位，不另做完整競品分析文件。
- 在文件內新增人工判讀與決策填寫模板，讓人工結果有結構化紀錄。

## Method Basis

內部依據：

- `Progress-decision.md`
- `tool-and-template.md`
- `01_問卷重點整理.md`
- `02_需求洞察整理.md`
- `03_假設型Persona.md`
- `04_User Stories.md`

外部排序方法佐證：

- Atlassian prioritization frameworks：MoSCoW 可用於需求優先級分類。<https://www.atlassian.com/agile/product-management/prioritization-framework>
- Atlassian product backlog：backlog 需依優先級管理與持續調整。<https://www.atlassian.com/agile/scrum/backlogs>
- ProductPlan MoSCoW glossary：支撐 Must / Should / Could / Won’t-have 分類定義。<https://www.productplan.com/glossary/moscow-prioritization>

## File Structure

`05_MVP 建議與待驗證假設.md` 包含：

1. `文件定位與使用限制`
   - 說明此文件是 MVP 建議初稿，不是最終開發承諾。
   - 標註資料仍來自探索性問卷、人工收斂與假設型 User Stories。

2. `進入 05 的 Gate 判斷`
   - 確認 04 已完成，7 則核心故事與 `US-04` 延後項目可作為排序依據。

3. `方法依據`
   - 列出內部依據與外部排序方法來源。

4. `MVP 功能候選清單`
   - 從 `04_User Stories.md` 的 7 則核心故事與 `US-04` 延後項目整理功能候選。

5. `MoSCoW MVP 建議`
   - 每項功能包含：優先級、對應 User Story、支持證據、使用者價值、主要風險、程式建議理由、需人工確認。

6. `待驗證假設`
   - 匿名信箱價值、相關經驗配對、分享者供給、等待時間、安全信任、回覆品質與平台差異化。

7. `參考平台觀察`
   - 簡短觀察匿名社群、問答平台、經驗分享平台常見做法，例如匿名、檢舉封鎖、內容規範、導覽、非即時互動。

8. `人工判讀與決策填寫模板`
   - 提供人工審核欄位，讓團隊填寫最終優先級、調整理由、風險接受度、是否進 MVP、後續處理。

9. `文件狀態`
   - 標示本文件已完成程式初稿，後續等待人工填寫決策模板。

## Initial MoSCoW Direction

- `Must-have`
  - 匿名投遞一對一經驗信箱。
  - 主題與希望回覆方式。
  - 分享者收到相關提問與配對理由。
  - 分享者匿名回覆與略過/拒絕權。
  - 回覆前界線提醒。
  - 檢舉、封鎖或結束不舒服互動。
- `Should-have`
  - 新手導覽與信箱差異理解。
  - 等待狀態與替代建議。
- `Could-have`
  - 細緻經驗條件、配對權重或進階演算法。
  - 範例內容或經驗故事補位。
  - 分享者誘因機制。
- `Won’t-have now`
  - 完整公開經驗文章牆。
  - 即時一對一聊天。
  - 完整競品分析文件。
  - 複雜個人化推薦或完整社群功能。

## Artificial Decision Templates

`05_MVP 建議與待驗證假設.md` 需包含以下人工填寫模板：

### MVP 功能決策表

| 功能候選 | 程式建議排序 | 人工最終排序 | 是否進 MVP | 調整理由 | 風險接受度 | 後續處理 |
|---|---|---|---|---|---|---|
| 功能名稱 | Must / Should / Could / Won’t | Must / Should / Could / Won’t | 是 / 否 / 待議 | 人工填寫 | 高 / 中 / 低 | 保留 / 簡化 / 延後 / 刪除 |

### Must-have 最終確認表

| Must-have 功能 | 不做會造成什麼問題 | 是否真的是第一版必要 | 人工確認結果 |
|---|---|---|---|
| 功能名稱 | 人工填寫 | 是 / 否 / 待議 | 保留 Must / 降為 Should / 延後 |

### 風險接受度判斷表

| 風險 | 對應功能或故事 | 影響 | 可接受嗎 | 需補救措施 |
|---|---|---|---|---|
| 風險內容 | US-xx / 功能名稱 | 高 / 中 / 低 | 是 / 否 / 待驗證 | 人工填寫 |

### 待驗證假設決策表

| 待驗證假設 | 對應證據 | 驗證優先級 | 建議驗證方式 | 人工決策 |
|---|---|---|---|---|
| 假設內容 | F/T/IN/US | 高 / 中 / 低 | 問卷追問 / 訪談 / 概念測試 / MVP 測試 | 保留 / 合併 / 延後 |

### Won’t-have now 確認表

| 不做項目 | 不做原因 | 何時重新考慮 | 人工確認 |
|---|---|---|---|
| 功能名稱 | 證據不足 / 成本高 / 偏離核心 / 風險高 | MVP 測試後 / 未來版本 | 確認不做 / 改列 Could / 待議 |

## Test Plan

- `05_MVP 建議與待驗證假設.md` 存在。
- `05_MVP 建議與待驗證假設：程式產出計畫.md` 存在，保存本 Proposed Plan。
- 每個 MVP 候選功能至少對應 1 則 User Story 或 `US-04` 延後項目。
- 每個 Must-have 都能回到 `F/T/IN` 或 Persona/User Story 證據。
- 文件明確標示 MoSCoW 是程式排序建議，不是最終決策。
- 文件包含待驗證假設與人工決策清單。
- 文件包含人工判讀與決策填寫模板。
- 文件只包含簡短參考平台觀察，不另做完整競品分析。
- `Current-Progress.md` 更新為 05 已產出初稿，並標示等待人工填寫決策模板。

## Assumptions

- 使用 MoSCoW 四欄排序：Must / Should / Could / Won’t-have now。
- 05 階段可由程式產出初稿，但最終 MVP 優先級仍需人工決定。
- 不新增完整競品分析文件，只在 05 內放簡短參考平台觀察。
- `US-04` 不回到 04 核心故事，而是在 05 作為 Should-have 或待驗證假設處理。
- 一對一匿名經驗交流信箱仍是主要產品假設，不寫成已被問卷完全驗證的最佳方案。
