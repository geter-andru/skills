# Andru free skills

Free skills for founders who sell a B2B product to enterprises, including founders who have never run an enterprise deal. Every sales or finance term is explained the first time it comes up. One so far. It works on its own: no account, no API key and no connector.

## pilot-business-case

For a paid pilot that is stalling, coming up for renewal, or being asked to "show the ROI". The skill walks you through five steps and leaves you with documents you can send:

1. **The pilot facts:** what was agreed, who uses it, what has happened.
2. **The baseline:** the "before" numbers the pilot never captured, rebuilt from records the customer already keeps, where they exist.
3. **A one-page case for the CFO:** what changed, what it's worth, what it costs, and the cost of doing nothing.
4. **Who else must agree:** finance, procurement (the team that runs vendor contracts), security, legal and the budget owner (whoever's budget pays for it), with what each will ask.
5. **Success criteria the customer writes:** so the renewal is judged on terms their own team set.

It's built not to invent numbers: anything missing is marked, with who at the customer can supply it.

## Install

**Claude Code**

```
/plugin marketplace add geter-andru/skills
/plugin install andru-skills@andru-skills
```

Or copy `skills/pilot-business-case/` into `~/.claude/skills/`.

**Cursor:** add this repository as a plugin. The skills are in `skills/`.

Then describe your pilot, for example: "My pilot with a logistics company ends next month and their CFO wants to see the ROI."

## About Andru

Andru is an enterprise buyer specialist for founders: it researches your company and the buyers who decide, then prepares you for real conversations with them. These skills don't need it. If you want the business case built on research about your own company and buyers, start with the free read at [andru-ai.com](https://andru-ai.com/?utm_source=claude-skill&utm_campaign=pilot-business-case&utm_content=readme).

## License

MIT
