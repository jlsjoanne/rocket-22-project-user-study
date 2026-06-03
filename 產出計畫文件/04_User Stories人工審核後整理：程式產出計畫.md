# 04_User Stories 人工審核後整理：程式產出計畫

## Summary

本計畫用於產出 `04_User Stories.md`，作為 `04_User Stories初稿.md` 經人工審核後的整理版。`04_User Stories初稿.md` 保留為初稿與人工審核紀錄，不覆寫。

整理後版本定位為「前進到 05 MVP 前的 User Stories」。文件仍維持假設型語氣，但 04 階段不需要再次人工審核，可作為 `05_MVP 建議與待驗證假設` 的依據。

## Key Decisions

- 核心 User Stories 數量調整為 7 則，符合 `Progress-decision.md` 與 `tool-and-template.md` 的 6-8 則門檻。
- `US-01`, `US-02`, `US-03`, `US-05`, `US-06`, `US-07`, `US-08` 列為 04 階段人工審核後核心故事。
- `US-04 查看等待狀態與替代建議` 不刪除，改列為「延後到 05 MVP 判斷」，因等待過久與沒人回覆仍是重要風險。
- 每則核心故事保留 `人工審核結果`，但移除審核前的 `人工審核提示`，避免正式整理版仍像待審稿。
- `外部方法對應` 改回方法論說明，不放入演算法、後台配對等產品實作描述。

## Alignment Rules

整理時需維持以下對齊：

- 專案內依據：每則故事需能回到 Persona 與 `F/T/IN` 證據來源。
- 產品定位：一對一匿名經驗交流信箱是主要產品假設，不是問卷已直接證明的唯一最佳形式。
- 外部方法：User Story 保持角色、目標、價值清楚；初步驗收條件保持可檢查，不寫成抽象願景或完整規格。
- 風險處理：等待、差異化、配對品質、分享者誘因、安全與回覆責任需帶入 05。

## Output Structure

`04_User Stories.md` 固定包含：

1. `文件定位與使用限制`
2. `方法依據與對齊檢查`
3. `人工審核後核心 User Stories 總覽`
4. `核心 User Story 證據卡`
5. `延後到 05 MVP 的故事與待驗證假設`
6. `是否仍需人工審核的判斷`
7. `文件狀態`

## Test Plan

- `04_User Stories.md` 存在，且 `04_User Stories初稿.md` 未被覆寫。
- 核心故事數為 7 則。
- `US-04` 清楚列入延後到 05 MVP，不混入核心故事清單。
- 每則核心故事都有 Persona、User Flow、User Story、支持證據、外部方法對應、初步驗收條件、風險與待驗證假設、人工審核結果。
- 每則核心故事至少引用 `F/T/IN` 證據。
- 文件明確判斷 04 階段不需再次人工審核，可進入 05 MVP 排序與待驗證假設。
- `Current-Progress.md` 更新為 04 人工審核後整理完成，下一步可規劃 05。

## Assumptions

- 本階段不新增外部來源，沿用既有 Atlassian、Scrum Alliance、Nielsen Norman Group 方法依據。
- `US-04` 是重要風險與 Should/Could 候選，不是 04 核心 User Stories 的必要保留項。
- 後續進入 05 時仍需人工決定 Must / Should / Could，不代表 7 則故事全部都會進入 MVP。
