# StackPick n8n Templates + SaaS pricing index

Import-ready [n8n](https://n8n.io) workflows for the most expensive problem in any local
business — **leads nobody answered** — plus a verified pricing index for 25 automation,
WhatsApp and email tools.

Every price below is checked against the vendor's own pricing page and dated. No estimates,
no affiliate-weighted rankings. Machine-readable copies: [JSON](data/pricing-index.json) ·
[CSV](data/pricing-index.csv) · [live dataset](https://trystackpick.com/pricing-index/).

**New original research:** [SaaS Pricing Snapshot — August 2026](https://trystackpick.com/reports/saas-pricing-august-2026/) analyzes the median entry price, free-plan availability and billing-unit mismatch across all 25 records. [Affiliate link status](https://trystackpick.com/partner-status/) identifies every commissioned and direct vendor link.

## Free templates (`free/`)

| Template | What it does |
|---|---|
| [`whatsapp-lead-follow-up.json`](free/whatsapp-lead-follow-up.json) | Lead webhook -> Wati template request -> sheet log -> verified reply check before a 24-hour follow-up |
| [`missed-call-whatsapp-recovery.json`](free/missed-call-whatsapp-recovery.json) | Mapped missed-call event -> Wati template request -> volume log; verify messaging permission first |

**Setup:** import the JSON into n8n (self-hosted or [Cloud](https://trystackpick.com/reviews/n8n/)) and follow the
sticky notes inside each workflow. Configure credentials and approved templates, validate reply
history and maintain opt-out suppression. Other providers need request/response adapters.
Delivery time is not guaranteed. You need a WhatsApp Business API account — [Wati vs respond.io compared on real pricing](https://trystackpick.com/vs/wati-vs-respond-io/).

Reference architecture: [car dealership AI stack](https://trystackpick.com/stacks/car-dealership-ai/).

## Editable WhatsApp message copy — $19

Prefer starting with the text? Our **WhatsApp Meta Template Kit** includes eight English
message drafts, a submission checklist and a setup guide, delivered as three Markdown files
in a ZIP. One-time purchase; WhatsApp Business API access and provider/message fees are separate.
Meta approval, delivery and sales are not guaranteed.

[Read a real sample and see every file](https://trystackpick.com/templates/?utm_source=github&utm_medium=referral&utm_campaign=whatsapp_kit#whatsapp-meta-template-kit).
The same page has the $49 n8n dealership reference workflow for technical users.

## Verified SaaS pricing index

Entry price is the wrong number to compare on — the **billing unit** decides the real bill.
Zapier counts tasks, Make counts operations, n8n counts executions; the same job can cost 5x
more depending on which one you picked.


**AI writing**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [Jasper](https://trystackpick.com/reviews/jasper/) | $59/mo | per month per seat, billed annually | No | 2026-08-25 |

**All-in-one**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [Systeme.io](https://trystackpick.com/reviews/systeme-io/) | $17/mo | per month, monthly billing | Yes | 2026-08-25 |

**Workflow automation**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [Make](https://trystackpick.com/reviews/make/) | $9/mo | per month, 10,000 credits, billed annually | Yes | 2026-08-25 |
| [Zapier](https://trystackpick.com/reviews/zapier/) | $20/mo | per month, 2,000 tasks, billed annually | Yes | 2026-08-25 |
| [n8n](https://trystackpick.com/reviews/n8n/) | $23/mo | per month, 2,500 executions (Cloud Starter €20, billed annually; approximate USD) | Yes | 2026-08-25 |
| [Lindy](https://trystackpick.com/reviews/lindy/) | $29.99/mo | per month per user, 3,000 credits (Plus) | No | 2026-08-25 |
| [Gumloop](https://trystackpick.com/reviews/gumloop/) | $37/mo | per month, 20,000 included credits (Pro) | No | 2026-08-25 |

**CRM & sales**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [HubSpot](https://trystackpick.com/reviews/hubspot/) | $7/mo | per month per seat, Starter, annual payment; current new-customer offer | Yes | 2026-08-25 |
| [Pipedrive](https://trystackpick.com/reviews/pipedrive/) | $14/mo | per month per seat, billed annually | No | 2026-08-25 |
| [Happierleads](https://trystackpick.com/reviews/happierleads/) | $99/mo | per month for 300 identified visitors | No | 2026-08-25 |

**Email marketing**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [Moosend](https://trystackpick.com/reviews/moosend/) | $7/mo | per month, 500 subscribers, billed annually | No | 2026-08-25 |
| [Brevo](https://trystackpick.com/reviews/brevo/) | $9/mo | per month, 5,000 emails; $9 monthly or $8.08 with annual billing | Yes | 2026-08-25 |
| [Mailchimp](https://trystackpick.com/reviews/mailchimp/) | $11/mo | per month, 500 contacts; regular Essentials price rounded from $10.56 | Yes | 2026-08-25 |
| [ActiveCampaign](https://trystackpick.com/reviews/activecampaign/) | $15/mo | per month, 1,000 contacts, billed annually | No | 2026-08-25 |
| [GetResponse](https://trystackpick.com/reviews/getresponse/) | $19/mo | per month, 1,000 contacts; annual prepay saves 18% | No | 2026-08-25 |
| [Smartlead](https://trystackpick.com/reviews/smartlead/) | $39/mo | per month | No | 2026-08-25 |

**Project management**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [ClickUp](https://trystackpick.com/reviews/clickup/) | $7/mo | per month per seat, billed annually | Yes | 2026-08-25 |
| [monday.com](https://trystackpick.com/reviews/monday/) | $9/mo | per month per seat, billed annually (3-seat minimum) | Yes | 2026-08-25 |

**AI voice agents**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [Retell AI](https://trystackpick.com/reviews/retell/) | Free / custom | pay as you go, $0.07-$0.31 per minute for AI Voice Agents | Yes | 2026-08-25 |
| [Vapi](https://trystackpick.com/reviews/vapi/) | Free / custom | pay as you go, $0.05/min platform fee + provider costs | Yes | 2026-08-25 |
| [Synthflow AI](https://trystackpick.com/reviews/synthflow/) | $2500/mo | per month equivalent of the $30,000 annual Enterprise contract minimum | No | 2026-08-25 |

**WhatsApp / BSP**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [AiSensy](https://trystackpick.com/reviews/aisensy/) | $16/mo | per month (Basic ₹1,500; INR converted to approximate USD at the 2026-08-24 ECB reference rate) | Yes | 2026-08-25 |
| [Wati](https://trystackpick.com/reviews/wati/) | $58/mo | per month, 3 users and 500 active contacts (Growth R$299, billed annually; approximate USD) | No | 2026-08-25 |
| [respond.io](https://trystackpick.com/reviews/respond-io/) | $79/mo | per month, 5 users (Starter, billed annually) | No | 2026-08-25 |
| [Gallabox](https://trystackpick.com/reviews/gallabox/) | $112/mo | per month (Basic, billed annually; Meta message fees billed separately) | No | 2026-08-25 |

Snapshot generated: 2026-09-04. Individual verification dates are shown in each row. Prices change without notice — each row links to a review page
carrying the source URL and check date.

## Cost calculators

Model your own volume instead of trusting list price:

- [Automation cost calculator](https://trystackpick.com/calculators/automation-cost/) — n8n vs Make vs Zapier at your task volume
- [WhatsApp cost calculator](https://trystackpick.com/calculators/whatsapp-cost/) — platform fee plus Meta per-conversation charges
- [AI voice agent cost calculator](https://trystackpick.com/calculators/ai-voice-agent-cost/) — cost per minute vs a human answering
- [Email marketing cost calculator](https://trystackpick.com/calculators/email-marketing-cost/) — cost by list size

## AI training jobs worldwide

StackPick also compares contributor platforms for people who want to help train AI. The
pages keep advertised rates separate from guaranteed work, show the verified Hub.xyz and
Crowtado referral destinations, and let readers model approved hours in local currency.

- [Worldwide AI training jobs comparison](https://trystackpick.com/ai-training-jobs/?utm_source=github&utm_medium=referral&utm_campaign=ai_training_research) — Hub.xyz, Crowtado and Claru side by side
- [Hub.xyz evidence review](https://trystackpick.com/ai-training-jobs/hub-xyz-review/?utm_source=github&utm_medium=referral&utm_campaign=ai_training_research) · [Crowtado evidence review](https://trystackpick.com/ai-training-jobs/crowtado-review/?utm_source=github&utm_medium=referral&utm_campaign=ai_training_research)
- [No-hype contributor guide](https://trystackpick.com/ai-training-jobs/how-to-make-money-training-ai/?utm_source=github&utm_medium=referral&utm_campaign=ai_training_research)
- [Brazil · Portuguese](https://trystackpick.com/pt/trabalhos-treinamento-ia/?utm_source=github&utm_medium=referral&utm_campaign=ai_training_research) · [India · Hindi](https://trystackpick.com/hi/ai-training-jobs-india/?utm_source=github&utm_medium=referral&utm_campaign=ai_training_research) · [Nigeria](https://trystackpick.com/ng/ai-training-jobs-nigeria/?utm_source=github&utm_medium=referral&utm_campaign=ai_training_research)
- Public data: [`ai-training-platforms.json`](data/ai-training-platforms.json) · [`ai-training-markets.json`](data/ai-training-markets.json)

Rates, tasks, approvals and payout availability can change. The calculators are scenarios,
not promises of work or income.

## Pick a stack from the data

- [Find My Stack](https://trystackpick.com/find-my-stack/) — rank active partner options by job, budget and operating priority
- [Switch & Save](https://trystackpick.com/switch-and-save/) — compare a current bill against a migration path
- [Plan Finders](https://trystackpick.com/plan-finder/) — match published capacity to monthly volume
- [Download the CSV](https://trystackpick.com/data/pricing-index.csv) — entry price, billing unit, free-plan flag, verification date and vendor source
- [Read the monthly pricing report](https://trystackpick.com/reports/saas-pricing-august-2026/) — findings and methodology from the current snapshot

### Embed them on your own site (free)

The WhatsApp and automation calculators ship as embeddable widgets — one iframe, no signup,
no API key, no tracking scripts on your page. Numbers update whenever we re-verify vendor
pricing, so there is nothing to maintain. Attribution link is the only condition.

**[Get the embed snippet →](https://trystackpick.com/embed/)**

## Switching tools?

- [Zapier alternatives](https://trystackpick.com/alternatives/zapier/) · [Make alternatives](https://trystackpick.com/alternatives/make/) · [n8n alternatives](https://trystackpick.com/alternatives/n8n/)
- [Mailchimp alternatives](https://trystackpick.com/alternatives/mailchimp/) · [Wati alternatives](https://trystackpick.com/alternatives/wati/)
- [BiteSpeed alternatives](https://trystackpick.com/alternatives/bitespeed/) — for a vendor that quotes only by sales call
- [Full comparison index](https://trystackpick.com/compare/)

## License

Free templates: MIT — use commercially, no attribution required (a star helps).

---

Maintained by [StackPick](https://trystackpick.com) · 2 free workflows · pricing for 25 tools
