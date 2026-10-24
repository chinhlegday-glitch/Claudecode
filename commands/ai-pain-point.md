---
description: Chọn đúng pain point để ứng dụng AI — mapping, chấm điểm, ưu tiên Top 3 và lập pilot 30-60-90
argument-hint: [step] [business-context]
---
Help the business choose the highest-value pain points for AI, using the Impact × Feasibility matrix and a weighted decision matrix.

<args>$ARGUMENTS</args>

## Steps
- `full` - End-to-end: strategy anchor → list pain points → score → matrix → Top 3 deep-dive → pilot charter (default)
- `list` - Brainstorm and group pain points by department (uses SME pain point library)
- `score` - Score given pain points on 10 impact criteria + 5 AI feasibility criteria
- `matrix` - Place scored pain points on the 2×2 matrix + weighted decision matrix
- `top3` - Deep-dive the Top 3: data needed, AI solution, expected benefit, risks
- `pilot` - Build the 1-page project charter + 30-60-90 plan + KPIs for pain point #1
- `workshop` - Produce a ready-to-run 2–3h "Mapping 3 nỗi đau" workshop kit

## Process
1. Activate Insights Agent (optimization advisor role)
2. Load skill `skills/chon-dung-pain-point-ai/SKILL.md` and its references
3. Ask for missing context: industry, team size, revenue range, 12-month goals, AI budget, current tools
4. Run the requested step(s); quantify every pain point (hours, VND, %)
5. Output using the skill's output format and templates

## Examples
- `/ai-pain-point full shop thời trang online 25 nhân sự` — Full mapping and pilot plan
- `/ai-pain-point score` — Paste a list of pain points, get impact/feasibility scores
- `/ai-pain-point pilot chatbot Fanpage` — Charter + 30-60-90 plan for a chosen project
- `/ai-pain-point workshop` — Workshop agenda + facilitator script + scoring sheets

## Tips
- Start from pain with numbers, never from a tool
- Data availability ≤ 2/10 is a knock-out: collect data first
- SMEs under 20 staff: run only 1 AI project at a time
- Measure a baseline for 1–2 weeks before turning AI on
