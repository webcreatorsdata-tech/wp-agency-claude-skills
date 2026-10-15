---
name: wp-site-audit
description: Audit a WordPress site (health, security, performance, SEO basics, backups, updates) and turn the findings into a clear monthly maintenance report for the client. Use when the user asks for a WordPress site audit, a website health check, or a monthly website maintenance report.
---

# WordPress Site Audit + Monthly Maintenance Report

Use this skill to audit a WordPress website and produce a client-ready maintenance report. It is built for small agencies and freelancers who maintain many WordPress sites.

## Inputs to collect first

Ask the user for anything missing. Do not guess.

- Site URL and client/business name
- Reporting period (for example: September 2026)
- What was actually done this month (updates run, backups taken, fixes made, tickets closed)
- Access available: WP admin export, plugin list, PageSpeed results, uptime log, or just the public URL
- Any open issues carried over from last month

If only the public URL is available, audit only what can be checked from outside (see "Public checks") and say clearly in the report which sections were not verified.

## Workflow

1. **Confirm scope.** State which sections you can verify and which depend on data the user must provide.
2. **Run the checks** in `references/checklist.md`. Work section by section: Updates, Security, Backups, Performance, SEO basics, Uptime, Content/forms.
3. **Rate each finding** as `OK`, `Needs attention`, or `Critical`. Never mark something `OK` that was not actually checked; use `Not checked` instead.
4. **Write the report** using the structure below. Keep it short and written for a non-technical client.
5. **Separate facts from recommendations.** What was found goes in the findings table. What the client should approve or pay for goes in "Recommended next steps".

## Public checks (no login needed)

- Site loads over HTTPS, no mixed-content warnings, certificate expiry date
- `robots.txt` and `sitemap.xml` present and sane
- Page title and meta description present on the home page
- Core Web Vitals / PageSpeed scores if the user provides results
- Visible broken links or broken images on key pages
- Contact form and key call-to-action buttons work (only if the user confirms a test is allowed)

## Report structure

1. **Header:** client name, site URL, reporting period, prepared by
2. **Summary:** 3 to 5 lines. Overall status and the one thing the client most needs to know.
3. **Work completed this month:** only items the user confirmed
4. **Findings table:** Area | Status | Notes
5. **Issues and risks:** each with impact in plain language
6. **Recommended next steps:** prioritized, with approval needed marked
7. **Next month focus**

## Rules

- Never invent numbers (uptime %, scores, update counts). If a number was not provided, leave it out or mark it "not provided".
- Never include passwords, API keys, or private client data in the report.
- Write in the language the user asks for. Default to plain English with no jargon; explain any technical term in one short phrase.
- Do not promise rankings, traffic, or security guarantees.
- If a critical security issue is found (outdated plugin with a known vulnerability, malware signs), put it at the top of the summary.

## Output

Deliver the report as the format the user asks for (Markdown, Word, or PDF). A sample is in `examples/sample-report.md`.
