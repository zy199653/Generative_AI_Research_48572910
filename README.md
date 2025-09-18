# AI_Research

put some stuff - all data for the project

> Tip/提示：为减少路径兼容问题，建议将 `research files` → `research_files`，`tutorial assignment'` → `tutorial_assignment`。

---

## 🧭 How to Navigate | 如何查找与使用

- **assignment/**
  - `instructions/`（可选）：任务书与评分标准 | task sheets & rubrics  
  - `submissions/`：作业答案与导出的 PDF | answers/exports

- **reference/**
  - `papers/`：论文 PDF | PDFs of articles  
  - `notes/`：阅读笔记，文件名与 PDF 保持同干名 | reading notes (same stem as PDF)  
  - 引文库导出（如 `references.bib`/`library.enl`）放此处 | citation exports live here

- **research files/**
  - `data_raw/`：原始数据（可能含敏感信息，谨慎权限）| raw data (may be sensitive)  
  - `data_clean/`：清洗后数据（记录处理日志）| cleaned data (+ change log)  
  - `code/`：脚本/Notebook | scripts/notebooks  
  - `reports/`：分析报告、图表导出 | analysis reports & figures  
  - `logs/`：实验/决策/溯源记录 | experiment & provenance logs

- **tutorial_assignment/**
  - GitHub 仓库结构截图、提交历史截图、README 截图 | repo tree, history, README screenshots  
  - 协作练习的分支/PR 链接与冲突解决记录 | links & conflict-resolution notes

---

## 🏷 Naming Conventions | 命名规范

- **Files/文件：** `topic_keyword-YYYYMMDD-vNN.ext`  
  例/eg：`survey_clean-20250918-v01.csv`，`eda-demographics-20250918-v02.ipynb`
- **Branches/分支：** `feat/<desc>-<sid>`，`fix/<desc>-<sid>`，`docs/<desc>-<sid>`
- **Commits/提交消息：** 小且清晰，例如/for example：  
  - `feat: add cleaned survey data and EDA notebook`  
  - `fix: correct dtype for age column`  
  - `docs: update README navigation`

一致、可读、可排序，有利于检索与复现。Consistent names aid searchability and reproducibility.

---

## 👥 How to Contribute | 协作方式

1. **Fork & Clone（派生并克隆）**  
   Fork 本仓库至你的账号并克隆到本地。Fork this repo and clone your fork locally.

2. **Create a Branch（创建分支）**  
   使用上述分支命名规范。Use the branch naming scheme above.

3. **Make Changes（进行修改）**  
   按“仓库结构”放置文件；敏感数据勿入库（或使用私有仓库/访问控制）。  
   Place files in the right folders; avoid committing PII/sensitive data.

4. **Commit Well（良好提交）**  
   小步提交+清晰信息。Small, logical commits with clear messages.

5. **Push & Open PR（推送与发起 PR）**  
   将分支推送到你的 fork，并向上游仓库的 `main` 发 PR。  
   Push your branch and open a PR against upstream `main`.  
   在 PR 描述中写明目的、关键改动、潜在风险与测试说明。  
   Describe purpose, key changes, risks, and test notes.

6. **Review & Merge（评审与合并）**  
   至少 1 名 reviewer 审核。若有冲突，请在 PR 中解决并说明取舍依据。  
   At least one approval. Resolve merge conflicts and explain the resolution.

---

## 🔐 Data & Privacy | 数据与隐私

- **原始数据/访谈文本/同意书** 等应视为 **受限**；优先使用私有仓库并控制访问。  
  Treat raw data/transcripts/consent forms as **restricted**; prefer private repos.  
- 使用 `.gitignore` 排除大文件/二进制/敏感文件。Use `.gitignore` for large/binary/sensitive files.  
- `paper submitted.pdf` 建议只读存档，后续修订请在工作稿进行。Keep the submitted PDF read-only.

---

## ♻️ Reproducibility Checklist | 可复现性清单

- 在 `research_files/logs/` 记录数据处理与主要决策。Log preprocessing & decisions.  
- 固定关键依赖版本（如 `requirements.txt` 或 notebook 头部说明）。Pin critical dependency versions.  
- 图表统一导出到 `research_files/reports/` 并使用描述性文件名。Export figures with descriptive names.

---

## 👤 Maintainers | 维护者

- Reviewer: _Name (GitHub @handle)_  
- Developers: _Name (GitHub @handle)_, _Name (GitHub @handle)_


