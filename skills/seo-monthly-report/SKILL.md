---
name: seo-monthly-report
description: Turn a month of SEO work and data (Search Console, Analytics, rankings, backlinks, task log) into a clear monthly SEO report for a client, with honest wins, problems and next steps. Use when the user asks for a monthly SEO report, SEO progress update or SEO summary for a client website.
---

# SEO Monthly Report

Use this skill to write a client-ready monthly SEO report for a website. It is built for freelancers and small agencies who report to non-technical clients.

## Inputs to collect first

Ask for anything missing. Do not guess or fill gaps with typical numbers.

- Client name, website URL, reporting month
- Main goals (leads, calls, sales, local visibility, brand searches)
- Data provided by the user, for example: Google Search Console export (clicks, impressions, CTR, average position, top queries and pages), Google Analytics numbers, keyword ranking list, backlink list, Google Business Profile insights
- Previous month's numbers for comparison, if available
- Work done this month (pages optimized, content published, technical fixes, links built)
- Planned work for next month and anything that needs client approval

If a data source is missing, leave that section out or mark it "Data not provided". Never invent numbers.

## Workflow

1. **Confirm what data exists** and which sections can be written from it.
2. **Compare to the previous period** where data allows. State the change as a number and a direction, for example "clicks: 1,240 vs 1,105 last month (+12%)". If there is no previous month, say so.
3. **Find the story.** Pick the 2 or 3 findings that matter most to the client's goals. Not every metric deserves a line.
4. **Be honest about causes.** SEO results take time and many things affect them. Say "likely related to" when the cause is not certain. Do not claim credit for a change without a reason.
5. **Write the report** using the structure below.
6. **Run the checks** in `references/checklist.md` before delivering.

## Report structure

1. **Header:** client, website, month, prepared by
2. **Summary:** 3 to 5 lines in plain language: what moved, why it matters, what happens next
3. **Key numbers:** table with this month, last month and change. Only metrics the user provided.
4. **Work completed:** only items the user confirmed
5. **Wins:** what improved, with the numbers
6. **Problems and risks:** drops, errors, lost pages, indexing issues, competitor moves, each explained simply
7. **Top pages and queries:** short lists from the data provided
8. **Next month plan:** prioritized actions, marking what needs client approval
9. **Notes:** data sources used and anything not verified

## Rules

- Never invent rankings, traffic, conversions or backlink counts.
- Do not promise rankings, traffic or revenue.
- Do not hide bad months. Report drops plainly with the most likely reasons and the planned response.
- Avoid jargon. Explain terms like CTR, impressions and average position in one short phrase the first time they appear.
- Do not include passwords, API keys or private account details.
- Separate facts (numbers from data) from interpretation (what they might mean).
- Write in the language the user asks for.

## Output

Deliver in the format the user asks for (Markdown, Word or PDF). A sample is in `examples/sample-seo-report.md`.
