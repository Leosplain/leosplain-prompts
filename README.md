# Leosplain Prompt Templates

**直接能用的繁體中文 Prompt 模板，來自真實踩坑與反覆測試。**

這裡不是「神奇萬能句合集」，而是把 Leosplain 網站上實際驗證過的工作規則，整理成可直接複製的卡片。  
你拿模板就能先跑，想知道「為什麼這樣寫、哪裡會失敗、怎麼改才有效」，再到原網站看完整實測。

**作者**：Leo（筆名）／ Leosplain Lab  
**原則**：第一手實測、清楚標示限制、無商業置入  
**授權**：MIT

---

## 為什麼直接來這裡還不夠？

模板能讓你立刻開始，但完整文章裡有這些東西：

- 真實失敗案例與修正過程
- 同一任務的 A/B 對照結果
- 測試環境、版本與限制說明
- 為什麼某個限制不能亂刪

想一次看懂「怎麼寫才穩、哪裡容易踩坑」，建議直接看原文章：

| 主題 | 完整文章 |
|------|----------|
| Prompt 核心框架（6 元素 + 5 套結構） | [Prompt Engineering 是什麼？](https://leosplain.com/ai-prompt-engineering/) |
| 日常高頻 5 張模組卡片 | [The Prompt Vault](https://leosplain.com/the-prompt-vault/) |
| 會議紀錄完整工作流 | [AI 會議紀錄怎麼寫？](https://leosplain.com/ai-meeting-notes-workflow/) |
| 防幻覺：先查核再寫作 | [AI 寫作防幻覺實測](https://leosplain.com/ai-writing-hallucination-fact-checking/) |
| Prompt 不好用時怎麼改 | [Prompt 怎麼改才有用？3 組對照](https://leosplain.com/prompt-details-breakdown-guide/) |

→ 更多 AI 實戰筆記：[leosplain.com](https://leosplain.com/)

---

## 這個 Repo 有什麼？

| 資料夾 | 內容 | 適合誰 |
|--------|------|--------|
| `01-core-frameworks/` | 5 套核心骨架（R-C-T-F、C-A-R-E、T-A-G、BAB、R-I-S-E） | 想建立固定寫法習慣的人 |
| `02-prompt-vault/` | 會議降噪、商務回信、審查、長文、程式碼審查 | 每天都在用 AI 處理工作的人 |
| `03-meeting-notes/` | 清理 → 摘要 → 決議 → 待辦（四組完整 Prompt） | 需要可交付會議紀錄的人 |
| `04-fact-checking/` | 先查核再寫作流程 | 在意來源與幻覺的人 |
| `05-prompt-debugging/` | 動詞、表格缺值、角色標準三組對照 | Prompt 結果不對、想快速除錯的人 |

---

## 怎麼用（30 秒上手）

1. 依任務類型進入對應資料夾
2. 複製 `.md` 裡的 Prompt
3. 把 `[貼上...]` 換成你的實際資料
4. 結果不理想 → 先看 `05-prompt-debugging/`，一次只改一類問題

### 使用原則（建議保留）

1. **資料與規則分開**：長文本放最後，用明確標記包起來
2. **保留負向限制**：「禁止自行補充」「找不到就標待確認」通常是防幻覺關鍵
3. **一次只改一類**：空話、假日期、假負責人，先對準一種再測
4. **結果請自行驗證**：模板來自特定時間與模型版本的實測

---

## 想看更多實測？

- 網站首頁：[leosplain.com](https://leosplain.com/)
- About（我怎麼測、測試環境）：[leosplain.com/about-me](https://leosplain.com/about-me/)
- 所有 Prompt 相關文章都標有可重現資源與限制說明

如果這個 Repo 對你有幫助，歡迎 star，也歡迎直接到網站看完整筆記。

---

## 貢獻

歡迎開 Issue 回報：
- 在特定模型上的失效案例
- 更好的限制寫法
- 新增高頻使用情境

請勿提交真實客戶資料或個資。

---

**最後更新**：2026-09-24  
**維護者**：Leo / Leosplain
