# 04_User Stories 初稿：程式產出計畫

## Summary

本計畫用於產出 `04_User Stories初稿.md`。文件定位是「假設型核心故事 backlog」，不是最終開發承諾。初稿採 8 則 User Stories 作為顆粒度，完整覆蓋提問、媒合、回覆、安全、導覽、等待與互動界線，再交由人工審核刪減。

本階段除參考專案內文件，也加入外部可靠來源作為方法佐證，讓產出的 User Stories 更能說服老師、團隊或審查者。

## Internal Basis

- `Progress-decision.md`：User Stories 可由程式依 Persona 與核心流程產出 6-8 則草稿，但核心故事選擇、粒度與驗收條件仍需人工判讀。
- `tool-and-template.md`：`04_User Stories` 應產出 6-8 則核心故事，附簡短證據與驗收條件。
- `01_問卷重點整理.md`：提供 `F-xx` 量化發現與 `T-xx` 開放題主題。
- `02_需求洞察整理.md`：提供 `IN-xx` 正式需求洞察與可支撐的 User Story 類型。
- `03_假設型Persona.md`：提供 P-01 經驗尋求者、P-02 經驗分享者、使用情境與故事線索。

## External Validation

外部來源只用來驗證 User Story 寫法、backlog 方法與驗收條件設計是否合理，不取代本專案的問卷、Persona 與洞察證據。

| 來源 | 可支撐的做法 | 使用方式 |
|---|---|---|
| Atlassian Agile Guide: User Stories with Examples and a Template, <https://www.atlassian.com/agile/project-management/user-stories> | User Story 可用「As a [user], I want [goal] so that [reason]」格式，並搭配 acceptance criteria 讓團隊理解成功條件。 | 支撐本文件每則故事使用「作為一位……我希望……以便……」與驗收條件。 |
| Atlassian Work Management: Acceptance Criteria, <https://www.atlassian.com/work-management/project-management/acceptance-criteria> | Acceptance criteria 應清楚、可驗證，說明故事完成時的成功條件。 | 支撐每則故事放入初步驗收條件，但保留人工確認。 |
| Scrum Alliance: Acceptance Criteria, <https://resources.scrumalliance.org/Article/need-know-acceptance-criteria> | User Story 描述使用者需求與目標，acceptance criteria 補足需要達成的條件，兩者互補。 | 支撐將 User Story 與驗收條件拆開，避免把故事寫成規格清單。 |
| Nielsen Norman Group: UX Stories Communicate Design Ideas, <https://media.nngroup.com/media/articles/attachments/UXStoriesCommunicateDesign.pdf> | UX story 可幫助團隊用具體人物與情境溝通設計理由。 | 支撐本階段引用 Persona 真實使用情境與人工審核提示，提高說服力。 |

## File Structure

`04_User Stories初稿.md` 固定包含：

1. `文件定位與使用限制`
   - 說明資料來自 65 份探索性問卷與人工收斂洞察。
   - 說明一對一匿名經驗交流信箱是主要產品假設，不是已被問卷完全驗證的最佳形式。
   - 說明 8 則故事是初稿 backlog，仍需人工審核刪減。

2. `方法依據`
   - 列出內部依據文件。
   - 列出外部可信來源與其支撐的做法。

3. `User Stories 總覽`
   - 列出 8 則故事。
   - 欄位包含 `Story ID`、`故事名稱`、`Persona`、`User Flow`、`主要洞察`、`人工審核建議`。

4. `User Story 證據卡`
   - 每則故事包含：
     - `Story ID`
     - `Persona`
     - `User Flow`
     - `User Story`
     - `支持證據`
     - `外部方法對應`
     - `初步驗收條件`
     - `風險與待驗證假設`
     - `人工審核提示`

5. `人工審核與刪減提示`
   - 提醒團隊判斷哪些故事應保留、合併、延後或刪除。

## 8 則初稿 Story

| Story ID | 故事名稱 | Persona | User Flow | 主要證據 |
|---|---|---|---|---|
| US-01 | 新手導覽與信箱差異理解 | P-01 | 瀏覽 / 導覽 | F-06, F-12, F-13, T-06, T-08, IN-04, IN-05 |
| US-02 | 匿名投遞一對一經驗信箱 | P-01 | 提問 | F-01, F-03, F-12, F-14, F-15, T-02, IN-01, IN-03 |
| US-03 | 選擇主題、相關經驗條件與希望回覆方式 | P-01 | 提問 / 媒合 | F-10, F-11, F-12, T-08, IN-02, IN-03 |
| US-04 | 查看等待狀態與替代建議 | P-01 | 等待 / 瀏覽 | F-06, F-12, T-06, T-08, IN-03, IN-04 |
| US-05 | 分享者收到相關提問與配對理由 | P-02 | 媒合 / 回覆前判斷 | F-02, F-11, F-17, T-03, T-08, IN-02, IN-03 |
| US-06 | 分享者匿名回覆並保留拒絕或略過權 | P-02 | 回覆 | F-02, F-12, F-14, T-01, T-04, T-08, IN-01, IN-03 |
| US-07 | 回覆前友善提醒與非專業建議界線 | P-02 | 安全 / 回覆品質 | F-16, F-19, T-03, T-05, IN-01, IN-03 |
| US-08 | 檢舉、封鎖或結束不舒服互動 | P-01 / P-02 | 安全 / 互動結束 | F-04, F-12, F-14, F-15, T-01, T-02, T-04, IN-01 |

## Human Review Rules

人工審核時逐則檢查：

- 是否真的支撐一對一匿名經驗交流信箱，而不是泛泛的社群平台功能。
- 是否有足夠 `F/T/IN` 證據。
- 是否符合外部 User Story 方法：使用者角色清楚、目標清楚、價值清楚、可驗收。
- 是否粒度過大或過小。
- 是否需要將 8 則刪減成 6 則正式核心故事。
- 是否把安全與信任錯誤視為可完全延後的附加功能。

刪減結果需標示：

- `保留`
- `合併`
- `延後到 05 MVP`
- `刪除`
- `刪減理由`

建議優先保留 `US-02`, `US-03`, `US-05`, `US-06`, `US-07`, `US-08`。若需要縮成 6 則，優先討論是否將 `US-01` 與 `US-04` 合併或延後，但不能完全刪除其風險紀錄。

## Test Plan

- 共 8 則 User Stories。
- 每則都使用「作為一位……我希望……以便……」格式。
- 每則至少對應 1 個 Persona、1 個 User Flow、1 個 `IN-xx`。
- 每則至少引用 1 個 `F-xx`；涉及安全、信任、內容品質者至少再引用 1 個 `T-xx`。
- 文件含外部可靠來源作為方法佐證。
- 明確標註一對一匿名經驗交流信箱是主要產品假設，不是已驗證最佳方案。
- 含人工審核與刪減提示，避免初稿被誤用為最終開發範圍。

## Assumptions

- 本階段只產出 User Stories 初稿，不做 MVP Must / Should / Could 排序。
- 外部來源用來驗證 User Story 寫法與 backlog 方法，不用來驗證本產品需求本身。
- 8 則故事是初稿顆粒度，後續人工可刪減為 6-8 則正式核心故事。
- 安全、隱私、檢舉/封鎖、回覆界線與非專業建議提示視為匿名交流基礎條件，不當作可完全省略的附加功能。
