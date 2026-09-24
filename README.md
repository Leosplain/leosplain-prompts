# Leosplain Prompt Templates

**直接複製就能用的繁體中文 Prompt，全部來自實際測試、踩坑與反覆修改。**

這個 Repo 提供可以直接使用的 Prompt 模板。

但如果你想知道：

- 為什麼原本的 Prompt 會失效？
- 改哪一段之後結果才改善？
- A/B 測試到底差在哪裡？
- 哪些限制不能拿掉？
- 在什麼條件下，這個方法其實不適用？

完整測試、失敗案例與修改過程，都整理在 Leosplain 網站。

👉 **[前往 Leosplain 看完整 AI 實戰](https://leosplain.com/)**

**作者**：Leo（筆名）／ Leosplain Lab  
**原則**：第一手實測、清楚標示限制、無商業置入  
**授權**：MIT

---

## 如果你只看 3 篇

### ① Prompt 寫了很多，結果還是不穩
[Prompt Engineering 是什麼？](https://leosplain.com/ai-prompt-engineering/)

從 Prompt 結構、6 個核心元素，到實際使用時容易出錯的地方。

### ② Prompt 改了很多次，還是不知道問題在哪裡
[Prompt 怎麼改才有用？3 組對照](https://leosplain.com/prompt-details-breakdown-guide/)

直接看不同寫法的 A/B 對照，找出 Prompt 為什麼沒有照預期工作。

### ③ AI 給出的答案看起來很合理，但真的對嗎？
[AI 寫作防幻覺實測](https://leosplain.com/ai-writing-hallucination-fact-checking/)

從查核、來源到實際寫作流程，拆解怎麼避免把錯誤內容直接交出去。

---

## 想知道這些 Prompt 為什麼有效？

這個 Repo 給你可以直接使用的 Prompt。

網站文章則會公開完整測試過程：

- 真實失敗案例與修正過程
- 同一任務的 A/B 對照
- 測試環境、版本與限制
- 哪些規則實際上不能刪
- 哪些方法在不同情況下可能失效

**如果你想學的不只是「複製哪一句」，而是「為什麼這樣寫」，建議直接看原文章。**

| 你現在遇到的問題 | 建議先看 |
|---|---|
| 想建立穩定的 Prompt 寫法 | [Prompt Engineering 是什麼？](https://leosplain.com/ai-prompt-engineering/) |
| 想直接拿常用 Prompt 使用 | [The Prompt Vault](https://leosplain.com/the-prompt-vault/) |
| AI 會議紀錄總是很亂 | [AI 會議紀錄怎麼寫？](https://leosplain.com/ai-meeting-notes-workflow/) |
| 擔心 AI 一本正經講錯 | [AI 寫作防幻覺實測](https://leosplain.com/ai-writing-hallucination-fact-checking/) |
| Prompt 改了很多次仍然沒改善 | [Prompt 怎麼改才有用？3 組對照](https://leosplain.com/prompt-details-breakdown-guide/) |

→ [更多 AI 實戰筆記：leosplain.com](https://leosplain.com/)

---

## 這個 Repo 有什麼？

| 資料夾 | 內容 | 適合誰 |
|---|---|---|
| `01-core-frameworks/` | 5 套核心骨架（R-C-T-F、C-A-R-E、T-A-G、BAB、R-I-S-E） | 想建立固定寫法習慣的人 |
| `02-prompt-vault/` | 會議降噪、商務回信、審查、長文、程式碼審查 | 每天都在用 AI 處理工作的人 |
| `03-meeting-notes/` | 清理 → 摘要 → 決議 → 待辦 | 需要可交付會議紀錄的人 |
| `04-fact-checking/` | 先查核再寫作流程 | 在意來源與幻覺的人 |
| `05-prompt-debugging/` | 動詞、表格缺值、角色標準三組對照 | Prompt 結果不對、想快速除錯的人 |

---

## 怎麼用（30 秒上手）

1. 依任務類型進入對應資料夾
2. 複製 `.md` 裡的 Prompt
3. 把 `[貼上...]` 換成你的實際資料
4. 結果不理想 → 先看 `05-prompt-debugging/`，一次只改一類問題

### 使用原則

1. **資料與規則分開**：長文本放最後，用明確標記包起來
2. **保留限制**：「禁止自行補充」「找不到就標待確認」通常是防幻覺的重要條件
3. **一次只改一類**：不要同時修改太多變數
4. **結果請自行驗證**：模板來自特定時間與模型版本的實測

---

## 想看更多實測？

**網站不是只整理 Prompt，而是把實際測試過程一起公開。**

👉 [Leosplain](https://leosplain.com/)

👉 [作者與測試方法](https://leosplain.com/about/)

覺得這些 Prompt 有用，歡迎 Star。

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
