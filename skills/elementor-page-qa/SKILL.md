---
name: elementor-page-qa
description: Run a pre-launch quality check on a WordPress/Elementor page or landing page (layout, mobile responsiveness, content, links, forms, speed, SEO basics) and produce a prioritized fix list. Use when the user asks to QA, review or check an Elementor page, landing page or new website before it goes live.
---

# Elementor Page QA

Use this skill to review a WordPress page built with Elementor before it goes live, and to give the builder a short, prioritized list of fixes.

## Inputs to collect first

Ask for anything missing. Do not guess.

- Page URL (staging or live), or screenshots of desktop and mobile
- Purpose of the page (lead generation, service page, product, ads landing page)
- Target audience and the one action the visitor should take
- Approved content or brief to compare against, if there is one
- Whether form and button tests are allowed

If only screenshots or pasted content are available, say which checks could not be done and mark them `Not checked`.

## Workflow

1. **Understand the goal.** Identify the primary call to action and judge every section against it.
2. **Go through `references/checklist.md`** in order: Content, Layout and design, Mobile and tablet, Links and buttons, Forms, Speed, SEO basics, Accessibility basics, Tracking.
3. **Rate each finding:** `Blocker` (fix before launch), `Should fix`, `Nice to have`, or `Not checked`.
4. **Write the fix list** grouped by priority. Each item states what is wrong, where it is, and what to change.
5. **Give a launch verdict:** Ready, Ready after blockers are fixed, or Not ready.

## Report format

1. **Page and date reviewed**
2. **Launch verdict** with one line of reasoning
3. **Blockers**
4. **Should fix**
5. **Nice to have**
6. **Not checked** and why

Keep each item to one or two lines. Name the section and device, for example: "Hero section, mobile: heading wraps to four lines and pushes the button below the fold."

## Elementor-specific things to look for

- Sections using fixed pixel widths or heights that break on mobile
- Text that is set as an image
- Inconsistent fonts, colors or spacing between sections (check global styles)
- Hidden-on-mobile elements that contain important content or the main button
- Heavy background videos, sliders or many animations on the first screen
- Forms without a success message, spam protection or a working notification email
- Leftover placeholder text, dummy images or "Lorem ipsum"
- Missing alt text on key images

## Rules

- Only report what was actually observed. Do not invent scores or test results.
- Do not include passwords, API keys or private client data in the report.
- Separate facts from opinions: mark design preferences as `Nice to have`, not `Blocker`.
- Never promise rankings or conversion rates.
- Keep the tone constructive; the reader is the person who built the page.
