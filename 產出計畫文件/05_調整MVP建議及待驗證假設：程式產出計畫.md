# 05_調整MVP建議及待驗證假設：程式產出計畫

## Summary

本計畫用於調整 `05_MVP 建議與待驗證假設初稿.md`，確認「使用者可以用文字或語音輸入」是否適合放入 MVP 階段，並產出調整後文件 `使用者分析文件/MVP建議與待驗證假設初稿.md`。

本次判斷結論：

- 文字輸入是匿名提問與匿名回覆的基本能力，應併入既有 Must-have 流程。
- 語音不應設計成語音聊天、語音訊息或保存錄音，而是「語音轉文字輔助輸入」。
- 依人工決策，語音轉文字輔助輸入列為 `Should-have` 簡化版。
- 語音輸入需保留待驗證語氣，因目前 65 份問卷未直接驗證語音輸入需求。

## Key Changes

- 新增 `MVP-16 文字輸入與語音轉文字輔助輸入` 至 MVP 功能候選清單。
- 在 `Must-have` 中補明匿名投遞與匿名回覆至少需支援文字輸入。
- 在 `Should-have` 中新增語音轉文字輔助輸入，作為降低長問題或長回覆輸入負擔的簡化版功能。
- 在 `Won’t-have now` 中新增 `語音訊息、即時語音聊天或保存原始錄音`，避免語音功能偏離非即時、低壓力文字信箱方向。
- 在待驗證假設中新增 `H-11`，驗證使用者是否願意以語音轉文字輸入敏感人生問題或回覆，並在送出前檢查與修正轉錄內容。
- 在參考平台觀察與人工決策模板中補上語音轉文字的常見做法、風險與人工確認欄位。

## Method Basis

內部依據：

- `AGENTS.md`
- `Current-Progress.md`
- `Progress-decision.md`
- `tool-and-template.md`
- `01_問卷重點整理.md`
- `02_需求洞察整理.md`
- `03_假設型Persona.md`
- `04_User Stories.md`
- `05_MVP 建議與待驗證假設初稿.md`

外部參考：

- Stanford HCI / Baidu / University of Washington: Speech Is 3x Faster than Typing for English and Mandarin Text Entry on Mobile Devices. <https://hci.stanford.edu/research/speech/paper.html>
- Microsoft Learn: Speech interactions 可將 speech recognition 用於文字輸入、表單輸入與文字聽寫。<https://learn.microsoft.com/en-us/windows/apps/develop/input/speech-interactions>
- Apple: Siri, Dictation & Privacy 說明 App 使用 Speech Recognition 轉錄時，音訊可能被送往 Apple。<https://www.apple.com/legal/privacy/data/en/ask-siri-dictation/>
- Google Gboard Help: advanced voice typing 的資料處理方式依功能而異，部分語音輸入可在裝置端處理。<https://support.google.com/gboard/answer/11197787>

## Implementation Changes

調整後文件位置：

- `使用者分析文件/MVP建議與待驗證假設初稿.md`

文件需完成以下修改：

- `3.2 外部排序方法佐證`：加入語音轉文字輸入的外部依據與隱私風險。
- `4. MVP 功能候選清單`：新增 `MVP-16`。
- `5.1 Must-have`：補明文字輸入是提問與回覆流程的基本能力。
- `5.2 Should-have`：新增「文字輸入與語音轉文字輔助輸入」。
- `5.4 Won’t-have now`：新增不做語音訊息、即時語音聊天或保存原始錄音。
- `6. 待驗證假設`：新增 `H-11`。
- `7. 參考平台觀察`：新增語音轉文字輸入觀察。
- `8. 人工判讀與決策填寫模板`：同步新增功能、風險、假設與 Won’t-have now 條目。
- `9. 人工決策清單`：補上語音轉文字是否進 MVP 的人工確認事項。
- `10. 文件狀態`：說明本文件已完成語音轉文字輔助輸入調整。

## Test Plan

- `產出計畫文件/05_調整MVP建議及待驗證假設：程式產出計畫.md` 存在。
- `使用者分析文件/MVP建議與待驗證假設初稿.md` 存在。
- 語音功能被列為 `Should-have`，不是 `Must-have`。
- 文件明確區分「語音轉文字輔助輸入」與「語音訊息 / 即時語音聊天 / 保存錄音」。
- `MVP-16` 至少對應 `US-02`、`US-03`、`US-06` 與 `IN-03`。
- `H-11` 已加入待驗證假設與人工決策表。
- 人工判讀模板中包含語音轉文字功能、風險與 Won’t-have now 確認項。
- 文件仍明確標示 MVP 排序是程式建議，不是最終開發承諾。

## Assumptions

- 本次依人工選擇採用 `Should-have 簡化版`。
- 第一版語音能力只處理語音轉文字，不傳送音檔給交流對象。
- 第一版不保存原始語音，不提供即時語音聊天。
- 若後續真的開發，優先考慮使用系統或鍵盤既有語音輸入能力，避免自行建置完整語音辨識後端。
- 語音輸入的隱私、公共場域可用性與轉錄錯誤需透過原型測試或 MVP 測試驗證。
