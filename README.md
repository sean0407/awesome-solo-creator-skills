# SoloStudio Skills

### AI 自媒體一人公司技能庫

> 一個人，也能營運一間內容公司。  
> *Build a one-person media company with AI.*

SoloStudio 是給自媒體創作者的開放工作室：提供可直接試用的 Agent Skills、可重現的內容工作流程，以及一份經過編輯的工具目錄。

**我們的核心不是收集最多連結，而是讓創作者能拿走一個工作流、試做一支內容，再把成果和改良回饋給社群。**

## 先試用

目前有三個原創 Skill 草稿，採 Agent Skills 的 `SKILL.md` 格式：

| Skill | 你可以拿它做什麼 |
|---|---|
| [Audience to Content Plan](skills/audience-to-content-plan/SKILL.md) | 從受眾描述與現有素材整理一週選題計畫，區分已知事實和待驗證假設。 |
| [Topic to Short Video](skills/topic-to-short-video/SKILL.md) | 把一個主題或來源資料整理成短影音企劃、口播稿、分鏡和查核清單。 |
| [Long Video to Short Clips](skills/long-video-to-short-clips/SKILL.md) | 從逐字稿挑選短片段，保留原意和時間碼，再產生平台版本草稿。 |

另外，已從 [marketingskills](https://github.com/coreyhaines31/marketingskills)（查核時 54,022 Stars、MIT 授權）收錄 15 個上游 Skills，按「定位 → 受眾與選題 → 文案 → 製作 → 發布 → 經營 → 搜尋 → 分析」排序。完整清單、版本和各檔案路徑見 [第三方 Skills 目錄](THIRD_PARTY_SKILLS.md)。

### 已收錄的上游 Skills

| 工作流程 | Skill 檔案 |
|---|---|
| 0. 定位 | [product-marketing](skills/third-party/marketingskills/skills/product-marketing/SKILL.md) |
| 1. 受眾與選題 | [customer-research](skills/third-party/marketingskills/skills/customer-research/SKILL.md) · [content-strategy](skills/third-party/marketingskills/skills/content-strategy/SKILL.md) · [marketing-ideas](skills/third-party/marketingskills/skills/marketing-ideas/SKILL.md) |
| 2. 文案 | [copywriting](skills/third-party/marketingskills/skills/copywriting/SKILL.md) · [copy-editing](skills/third-party/marketingskills/skills/copy-editing/SKILL.md) |
| 3. 製作 | [video](skills/third-party/marketingskills/skills/video/SKILL.md) · [image](skills/third-party/marketingskills/skills/image/SKILL.md) |
| 4. 發布 | [social](skills/third-party/marketingskills/skills/social/SKILL.md) |
| 5. 經營受眾與營收 | [lead-magnets](skills/third-party/marketingskills/skills/lead-magnets/SKILL.md) · [emails](skills/third-party/marketingskills/skills/emails/SKILL.md) · [influencer-marketing](skills/third-party/marketingskills/skills/influencer-marketing/SKILL.md) |
| 6. 搜尋與發現 | [seo-audit](skills/third-party/marketingskills/skills/seo-audit/SKILL.md) · [ai-seo](skills/third-party/marketingskills/skills/ai-seo/SKILL.md) |
| 7. 成效分析 | [analytics](skills/third-party/marketingskills/skills/analytics/SKILL.md) |

把任一 Skill 資料夾放到支援 Agent Skills 的 Agent 環境中，依該工具的安裝方式載入。格式包含 `SKILL.md` YAML frontmatter 和 Markdown 指示；不同 Agent 的相容性仍需實測。[Agent Skills 規格](https://agentskills.io/specification)

## 這個 Repo 歡迎什麼樣的 PR？

單純加連結可以幫忙擴充目錄；更能改善專案的 PR，會讓創作者多一個可直接拿去用的成果：

- **新 Skill**：解決明確的創作任務，附使用情境、輸入、輸出與人工檢查點。
- **實測案例**：用公開、虛構或已獲同意的素材跑過 Skill，記錄 Agent、日期、結果與限制。
- **平台適配**：同一工作流如何調整成 YouTube、Instagram、TikTok、Podcast 或電子報版本，附官方規則來源與查核日期。
- **在地化**：繁中、英文或其他語言版本，保留原始來源並說明用詞選擇。
- **可靠性改進**：減少幻覺、補來源檢查、改善時間碼／字幕處理，並附可重現例子。
- **目錄維護**：修正失效連結、過期授權或定價，提供原始證據。

從 [CONTRIBUTING.md](CONTRIBUTING.md) 開始，或查看 [貢獻任務清單](CONTRIBUTOR_TASKS.md)。

## 原創 Skill

### Audience to Content Plan

把創作者已知的受眾、內容目標與手邊素材，整理成可執行的一週計畫。Skill 會把事實、假設和需要查證的市場主張分開，避免把猜測寫成受眾研究結果。

### Topic to Short Video

從題目或來源材料產出短影音企劃。輸出包含不同角度的開場、口播草稿、分鏡提示、字幕與發布前查核項目；引用到的事實必須能回到使用者提供的來源。

### Long Video to Short Clips

從逐字稿和時間碼找出可獨立理解的片段，保留原句，不杜撰逐字稿，也不把片段剪輯建議誤稱為實際影片。沒有逐字稿或時間碼時，Skill 會明確標記限制。

## 精選資源目錄

以下初始候選 Repo 在 **2026-10-10** 查核時均超過 1,000 GitHub Stars。星數是人氣快照，不代表品質或適用性；新項目不設 Stars 門檻。新增資源請附上任務用途、原始連結和查核日期。

### Agent Skills 與工作流程

| 資源 | 用途 | Stars 快照 |
|---|---|---:|
| [marketingskills](https://github.com/coreyhaines31/marketingskills) | 行銷、文案、SEO、內容策略與成長 Skills；MIT 授權。 | 約 54k |
| [awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | 參考 Creative & Media、Business & Marketing 分類；各項授權需個別確認。 | 約 76.8k |
| [awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | 跨多種 Agent 的 Skills 目錄。 | 約 35k |
| [agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills) | 大型 Skills 集合；程式碼與文件可能採不同授權。 | 約 46.6k |
| [anthropics/skills](https://github.com/anthropics/skills) | 參考 Agent Skills 結構與官方範例；再使用前逐項核對授權。 | 約 180.2k |
| [Agent Skills Specification](https://github.com/agentskills/agentskills) | Skills 格式規格與文件。 | 約 26k |
| [agency-agents](https://github.com/msitarzewski/agency-agents) | 參考如何按角色、流程和交付物設計 Agent。 | 約 158.6k |
| [prompts.chat](https://github.com/f/prompts.chat) | 參考社群如何整理和分享提示詞；採用內容前確認來源和授權。 | 約 143k |

### 內容製作工具

| 資源 | 用途 | 授權／注意事項 | Stars 快照 |
|---|---|---|---:|
| [HyperFrames](https://github.com/heygen-com/hyperframes) | 以 HTML 建立並渲染影片。 | Apache-2.0（以原 Repo 為準） | 約 60.1k |
| [Remotion](https://github.com/remotion-dev/remotion) | 用 React 程式化製作影片。 | 商業使用前查閱原 Repo 的最新條款。 | 約 63k |
| [OpenMontage](https://github.com/calesthio/OpenMontage) | Agent 影片製作系統和製作流程範例。 | AGPL-3.0 | 約 66k |
| [Whisper](https://github.com/openai/whisper) | 語音辨識、字幕和逐字稿整理。 | MIT | 約 110.3k |
| [ComfyUI](https://github.com/Comfy-Org/ComfyUI) | 節點式生成媒體工作流。 | 確認程式碼和模型權重各自條款。 | 約 132.8k |

### 自動化與素材管理

| 資源 | 用途 | 授權／注意事項 | Stars 快照 |
|---|---|---|---:|
| [n8n](https://github.com/n8n-io/n8n) | 串接內容流程、AI 服務與外部工具。 | Fair-code；商業使用查看原 Repo 條款。 | 約 206k |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | 管理自己擁有或獲准使用的影音素材。 | 遵守素材權利和來源平台規範。 | 約 196k |

## 一人媒體公司的工作流程

1. **定位與選題**：受眾、內容支柱、痛點、選題與內容日曆。
2. **腳本與文案**：開場、腳本、品牌語氣和來源查核。
3. **製作與後製**：分鏡、字幕、配音、縮圖和圖文素材。
4. **再製與發布**：核心內容轉為各平台版本，人工確認後發布。
5. **受眾與社群**：留言分類、回覆草稿、社群規範與互動回顧。
6. **營運與營收**：電子報、贊助、數位產品、分析和內容實驗。

## 授權

本 Repo 的原創文字、Skills 與分類採 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)。位於 `skills/third-party/` 的上游 Skills 依各來源授權，授權全文與來源版本保留在各來源目錄；請參閱 [第三方 Skills 目錄](THIRD_PARTY_SKILLS.md)。提交內容前請確認自己有權依 CC BY 4.0 分享。
