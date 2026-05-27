# Nursing FRAM AI Scenario Skill

這個 repository 是作業一成果，包含兩個部分：

1. `skills/nursing-fram-ai-scenario/`：一個可直接使用的 Codex Skill，用於設計「護理 FRAM 研究與 AI 輔助臨床情境」。
2. `portfolio/ai-supported-nursing-handoff-fram-study.md`：使用該 Skill 產出的作品範例，以「AI 輔助護理交班」為主題。
3. `fa.html`：可直接開啟的互動式 HTML 作品頁，呈現 FRAM × AI 護理情境設計模型。

## 題目

結合目前護理 FRAM 研究與 AI 設計情境，設計一個可直接使用的學術導向 Skill。本設計遵循「先定義任務邊界、再設計流程與評估」的原則。

## Repository Structure

```text
skills/
  nursing-fram-ai-scenario/
    SKILL.md
    agents/
      openai.yaml
    references/
      fram-nursing-guide.md
      evaluation-rubric.md
portfolio/
  ai-supported-nursing-handoff-fram-study.md
fa.html
index.html
```

## How To Use The Skill

把 `skills/nursing-fram-ai-scenario` 放入 Codex skills 目錄，或在支援 Skills 的環境中指定此資料夾。可以用下列 prompt 觸發：

```text
Use the nursing-fram-ai-scenario skill to design an academic FRAM study for AI-supported nursing handoff in an internal medicine ward.
```

## Work Demonstration

作品檔案 `portfolio/ai-supported-nursing-handoff-fram-study.md` 展示此 Skill 可產出的具體成果，內容包含：

- 任務邊界
- 研究目的
- FRAM 功能表
- 功能共振分析
- AI 輔助情境
- 評估計畫
- 倫理與限制

互動式作品頁 `fa.html` 則可作為 GitHub Pages 展示頁，讓使用者輸入護理情境參數並產生 FRAM 功能表、AI 輔助設計建議與評估維度。
