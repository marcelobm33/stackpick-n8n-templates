# StackPick n8n Templates + SaaS pricing index

Import-ready [n8n](https://n8n.io) workflows for the most expensive problem in any local
business — **leads nobody answered** — plus a verified pricing index for 23 automation,
WhatsApp and email tools.

Every price below is checked against the vendor's own pricing page and dated. No estimates,
no affiliate-weighted rankings. Machine-readable copy: [`pricing-index.json`](https://trystackpick.com/data/pricing-index.json).

## Free templates (`free/`)

| Template | What it does |
|---|---|
| [`whatsapp-lead-follow-up.json`](free/whatsapp-lead-follow-up.json) | New lead -> instant WhatsApp reply in under 60s -> sheet log -> polite 24h follow-up |
| [`missed-call-whatsapp-recovery.json`](free/missed-call-whatsapp-recovery.json) | Missed phone call -> WhatsApp message to the caller within seconds -> missed-call volume log |

**Setup:** import the JSON into n8n (self-hosted or [Cloud](https://trystackpick.com/reviews/n8n/)) and follow the
sticky notes inside each workflow. Roughly 10 minutes each. You need a WhatsApp Business API
account — [Wati vs respond.io compared on real pricing](https://trystackpick.com/vs/wati-vs-respond-io/).

Reference architecture: [car dealership AI stack](https://trystackpick.com/stacks/car-dealership-ai/).

## Verified SaaS pricing index

Entry price is the wrong number to compare on — the **billing unit** decides the real bill.
Zapier counts tasks, Make counts operations, n8n counts executions; the same job can cost 5x
more depending on which one you picked.


**AI writing**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [Jasper](https://trystackpick.com/reviews/jasper/) | $39/mo | per month per seat, billed annually | No | 2026-06-12 |

**All-in-one**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [Systeme.io](https://trystackpick.com/reviews/systeme-io/) | $27/mo | per month, billed annually | Yes | 2026-06-12 |

**Workflow automation**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [Make](https://trystackpick.com/reviews/make/) | $9/mo | per month, 10,000 credits, billed annually | Yes | 2026-07-10 |
| [Zapier](https://trystackpick.com/reviews/zapier/) | $20/mo | per month, 750 tasks, billed annually | Yes | 2026-06-12 |
| [n8n](https://trystackpick.com/reviews/n8n/) | $26/mo | per month, 2,500 executions (Cloud Starter, billed annually) | Yes | 2026-07-01 |
| [Lindy](https://trystackpick.com/reviews/lindy/) | $50/mo | per month, 5,000 credits (Pro) | Yes | 2026-07-01 |
| [Gumloop](https://trystackpick.com/reviews/gumloop/) | $97/mo | per month, 30,000 credits (Starter) | Yes | 2026-07-01 |

**CRM & sales**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [Pipedrive](https://trystackpick.com/reviews/pipedrive/) | $14/mo | per month per seat, billed annually | No | 2026-06-12 |
| [HubSpot](https://trystackpick.com/reviews/hubspot/) | $15/mo | per month per seat, Starter, billed annually | Yes | 2026-06-12 |
| [Happierleads](https://trystackpick.com/reviews/happierleads/) | $99/mo | per month for 300 identified visitors | No | 2026-07-10 |

**Email marketing**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [Brevo](https://trystackpick.com/reviews/brevo/) | $9/mo | per month, 5,000 emails (unlimited contacts) | Yes | 2026-06-12 |
| [Moosend](https://trystackpick.com/reviews/moosend/) | $9/mo | per month, 500 subscribers, billed annually | No | 2026-06-12 |
| [Mailchimp](https://trystackpick.com/reviews/mailchimp/) | $13/mo | per month, 500 contacts, billed monthly | Yes | 2026-06-12 |
| [ActiveCampaign](https://trystackpick.com/reviews/activecampaign/) | $15/mo | per month, 1,000 contacts, billed annually | No | 2026-06-12 |
| [GetResponse](https://trystackpick.com/reviews/getresponse/) | $19/mo | per month, 1,000 contacts, billed annually | Yes | 2026-06-12 |

**Project management**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [ClickUp](https://trystackpick.com/reviews/clickup/) | $7/mo | per month per seat, billed annually | Yes | 2026-06-12 |
| [monday.com](https://trystackpick.com/reviews/monday/) | $9/mo | per month per seat, billed annually (3-seat minimum) | Yes | 2026-06-12 |

**AI voice agents**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [Retell AI](https://trystackpick.com/reviews/retell/) | Free / custom | pay as you go, ~$0.07-0.13 per minute all-in | Yes | 2026-07-01 |
| [Vapi](https://trystackpick.com/reviews/vapi/) | Free / custom | pay as you go, $0.05/min platform fee + provider costs | Yes | 2026-07-01 |
| [Synthflow AI](https://trystackpick.com/reviews/synthflow/) | $29/mo | per month, 50 minutes included on entry plan | No | 2026-07-01 |

**WhatsApp / BSP**

| Tool | From | Billing unit | Free plan | Verified |
|---|---|---|---|---|
| [AiSensy](https://trystackpick.com/reviews/aisensy/) | $30/mo | per month (Basic ₹2,500 + GST, INR converted to approximate USD) | No | 2026-07-10 |
| [Wati](https://trystackpick.com/reviews/wati/) | $49/mo | per month, 5 users (Growth, billed annually) | No | 2026-07-01 |
| [respond.io](https://trystackpick.com/reviews/respond-io/) | $79/mo | per month, 5 users (Starter, billed annually) | No | 2026-07-01 |

Last verified: 2026-07-26. Prices change without notice — each row links to a review page
carrying the source URL and check date.

## Cost calculators

Model your own volume instead of trusting list price:

- [Automation cost calculator](https://trystackpick.com/calculators/automation-cost/) — n8n vs Make vs Zapier at your task volume
- [WhatsApp cost calculator](https://trystackpick.com/calculators/whatsapp-cost/) — platform fee plus Meta per-conversation charges
- [AI voice agent cost calculator](https://trystackpick.com/calculators/ai-voice-agent-cost/) — cost per minute vs a human answering
- [Email marketing cost calculator](https://trystackpick.com/calculators/email-marketing-cost/) — cost by list size

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

## Paid pack

**Dealership Lead Recovery Pack ($49)** — the production version: reply-aware day 1/3/7 cadence
that stops the moment the lead answers, lead scoring (hot/warm/cold), vehicle-interest capture,
setup guide and Meta-ready WhatsApp template copy.

-> [Get it on Gumroad](https://stackpick.gumroad.com/l/dealership-lead-recovery)

**WhatsApp Meta Template Kit ($19)** — 8 approval-ready template texts plus the rejection
checklist. No n8n required.

-> [Get the kit](https://stackpick.gumroad.com/l/whatsapp-meta-template-kit)

## License

Free templates: MIT — use commercially, no attribution required (a star helps).

---

Maintained by [StackPick](https://trystackpick.com) · 2 free workflows · pricing for 23 tools
