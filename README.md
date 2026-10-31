# InsightfulPipe B2B Sales Skills

**20 free Claude skills for B2B sales and marketing: cold email, LinkedIn outreach, ABM, lead scoring and handoff, prospect lists, sales decks, proposals and objection handling.**

Most of these skills also work from reports you export and paste in, with no account needed. Skills that need numbers read them live from your accounts when the InsightfulPipe MCP is connected.

Part of the free [InsightfulPipe marketing skills library](https://github.com/Insightful-Pipe/marketing-skills). Skills with a **Page** link have a page with a sample run at [insightfulpipe.com](https://insightfulpipe.com/marketing-claude-skills); newer ones get theirs soon.

## Install

### Claude Code

```
/plugin marketplace add Insightful-Pipe/b2b-sales-skills
/plugin install insightfulpipe-b2b-sales@insightfulpipe-b2b-sales
```

### Any agent: Claude Code, Codex, Cursor and others

```
npx skills add Insightful-Pipe/b2b-sales-skills
```

Add `--skill abm-program-planner` to install one skill.

### Claude.ai and Claude Desktop

Download a skill's ZIP from its page on insightfulpipe.com (the **Page** links below), or zip its folder from `skills/` if it has no page yet, then in Claude open **Customize > Skills**, choose **+ Create skill > Upload a skill** and pick the ZIP. Skills need code execution turned on.

## Skills (20)

| Skill | What it does | |
|---|---|---|
| [Abm Program Planner](skills/abm-program-planner/) | Plans an account-based marketing (ABM) program from your target account list and closed deals. | [Page](https://insightfulpipe.com/marketing-claude-skills/sales/abm-program-planner) |
| [B2B Cold Email Writer](skills/cold-email-writer/) | Writes B2B cold email sequences for a lead list, with subject lines, follow-ups and a personal first line per prospect built on one dated public fact, and sorts replies. |  |
| [B2B Demand Generation Planner](skills/b2b-demand-gen-planner/) | Plans B2B demand generation backwards from a revenue target, working out deals, SQLs, MQLs and leads from your own CRM rates, then splits channels and outbound into a… |  |
| [B2B Lead Enrichment and Scoring](skills/b2b-lead-enrichment/) | Cleans, enriches and scores B2B lead lists from Google Sheets, Airtable or a paste for ICP fit, maps decision makers, drafts cold emails and watches target accounts for… |  |
| [B2B Prospect List Builder](skills/prospect-list-builder/) | Builds a B2B prospect list of real companies from business listings, ad libraries, search results and app stores, each with dated evidence and a reason to reach out… |  |
| [Closed Lost Deal Re-engagement Planner](skills/lost-deal-reengagement/) | Ranks closed lost deals worth another try, codes each loss cause, dates the retry from it and checks accounts for signs of change, then drafts owner notes, a nurture… |  |
| [Cold Email Campaign Analyzer](skills/outbound-campaign-analyzer/) | Analyzes cold email campaign results from a sending tool export by step, variant, segment and mailbox, with confidence ranges, to find delivery, list, message or offer… |  |
| [Cold Email Deliverability Setup Planner](skills/cold-email-infrastructure-planner/) | Plans the cold email sending setup before launch. |  |
| [Customer Advocacy Program Planner](skills/customer-advocacy-program/) | Plans a B2B customer advocacy and reference program from your customer export. |  |
| [Lead Scoring Model from Deal History](skills/lead-scoring-model-builder/) | Builds a lead scoring model from your own won and lost leads, turning traits and actions into points, fitting decay and picking the MQL threshold from a backtest. |  |
| [LinkedIn Prospecting Message Writer](skills/linkedin-outreach-writer/) | Writes LinkedIn prospecting messages per prospect, including connection notes, first messages, follow-ups and InMails, each opening from a dated post or news and… |  |
| [MQL to SQL Handoff Designer](skills/lead-handoff-designer/) | Designs the marketing to sales lead handoff from your CRM lead export, setting MQL vs SQL rules, lead routing, a response time SLA, rejected lead recycling and no-show… |  |
| [Objection Handling Guide](skills/objection-handling-guide/) | Builds a sales objection handling guide from your own call notes, lost reasons, comments and reviews, ranking objections by pipeline touched and writing a sourced reply… | [Page](https://insightfulpipe.com/marketing-claude-skills/sales/objection-handling-guide) |
| [ROI Business Case Builder](skills/roi-business-case-builder/) | Builds the ROI business case for one buyer in one deal from their own numbers, with low, expected and high results, payback, NPV, sensitivity and a one-page case for… |  |
| [Sales Call Script Writer](skills/sales-call-script-writer/) | Writes sales call guides from your own call notes, including a cold calling script with voicemail and gatekeeper lines, a discovery guide tied to BANT or MEDDICC fields… |  |
| [Sales Deck Writer](skills/sales-deck-builder/) | Writes a B2B sales deck slide by slide from the buyer's goal, with headlines, speaker notes and a checked source for every claim, plus an optional .pptx. |  |
| [Sales Follow-Up Email Writer](skills/sales-follow-up-writer/) | Writes one-to-one sales follow-up emails for open deals from call notes, like the demo recap, proposal chasers and a polite last email, with when each is due. |  |
| [Sales One-Pager Writer](skills/sales-one-pager-writer/) | Writes a one-page sales sheet for one persona or industry, a solution brief, why-us comparison or customer result sheet, with sourced proof, benefits ranked by buyer… |  |
| [Sales Playbook Builder](skills/sales-playbook-builder/) | Builds a sales playbook from a CRM export, sequence report and call notes, with who to target, deal stages, weekly activity targets worked back from quota and a… |  |
| [Sales Proposal and RFP Response Writer](skills/sales-proposal-writer/) | Writes B2B sales proposals with priced options from discovery notes, and RFP responses with a compliance matrix and a bid or no-bid score before any answer, every claim… |  |

## Live data (optional)

Skills that read account data use the [InsightfulPipe MCP server](https://insightfulpipe.com/mcp-servers) when it's connected. Without it, each skill tells you which exports to paste in and works from those.

## What this plugin runs and sends

The plugin contains skills only: Markdown instructions (`SKILL.md`, `HOW_TO_USE.md`) and sample input and output files. It adds no hooks, commands or MCP servers, runs no code on your machine and sends no data anywhere by itself. When you have the InsightfulPipe MCP connected, Claude uses it to read your accounts, and makes a change only after you confirm it. The `scripts/` and `.github/` folders keep this repository in sync with insightfulpipe.com and are not part of what the plugin does.

## License

MIT. See [LICENSE](LICENSE).
