# wp-agency-claude-skills

Claude skills for people who build and maintain WordPress websites for clients: freelancers, small agencies and one-person studios.

Built by [Web Creators India](https://webcreatorsind.com), a WordPress development and digital solutions company.

## Skills

| Skill | What it does |
|-------|--------------|
| [`wp-site-audit`](skills/wp-site-audit/SKILL.md) | Audits a WordPress site (updates, security, backups, performance, SEO basics, uptime, forms) and writes a plain-language monthly maintenance report for the client |

## How to use

1. Download or clone this repository.
2. Add the `skills/wp-site-audit` folder to your Claude skills (see the Claude documentation for how skills are installed for your product).
3. Ask Claude something like: *"Run a WordPress site audit for example.com and write the September maintenance report."*

Claude will ask for anything it cannot verify, such as what work was done this month or uptime data, and will mark unchecked areas as "Not checked" instead of guessing.

## What is inside

```
skills/wp-site-audit/
  SKILL.md                   instructions Claude follows
  references/checklist.md    audit checklist
  examples/sample-report.md  sample report with fictional data
```

## Privacy

The sample report uses fictional data. These skills do not contain client names, credentials or private project information. Do not paste passwords or API keys into prompts.

## Contributing

Issues and pull requests are welcome: extra checklist items, report templates, translations, or new skills for WordPress agency workflows (SEO reporting, Elementor QA, onboarding checklists).

## License

MIT, see [LICENSE](LICENSE).
