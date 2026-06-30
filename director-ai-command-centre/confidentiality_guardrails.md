# Confidentiality Guardrails
## A Practical Guide for Using Claude Safely at Director Level

---

## The One Rule That Covers Everything

**If you would not email it to a stranger, do not paste it into Claude.**

Claude (when used via claude.ai or the API) processes your input through Anthropic's servers. Even though Anthropic does not use your conversations to train models by default, and even though Claude is not a public forum, the safest mental model is: anything you paste in has left your building. Treat it accordingly.

---

## What NOT to Paste into Claude Without Checking Company Policy First

### 1. Personal Data (High Risk)
- **Staff names** tied to performance issues, salaries, disciplinary matters, or HR decisions
- **Customer names, email addresses, phone numbers, loyalty IDs, or transaction histories**
- **Supplier contact names** linked to commercial decisions or disputes
- Any data that falls under POPIA (Protection of Personal Information Act) in South Africa — which covers any identifiable information about a living person

**What to do instead:** Replace names with roles. "Sarah in buying" becomes "the Buying Manager". "Customer ref 00123" becomes "a customer account".

---

### 2. Financial Data Under NDA or Not Yet Public (High Risk)
- Exact revenue figures, margin percentages, or EBITDA that have not been publicly disclosed
- Budget-vs-actual data that forms part of board reporting
- Supplier pricing, cost of goods, or rebate structures
- Forward-looking financials (range plans, forecasts, targets)

**What to do instead:** Use ranges and approximations. "Revenue of R450m" becomes "revenue in the R400–500m range". "Margin of 52.3%" becomes "margin in the low-to-mid fifties". You get equally useful analysis; you share no sensitive specifics.

---

### 3. Strategic Information (High Risk)
- Merger, acquisition, or disposal plans (M&A is the highest-risk category)
- Unpublished brand or product strategies
- Plans to enter or exit markets, channels, or geographies
- Competitive intelligence obtained under NDA or from confidential sources
- Pricing or promotional strategies not yet public

**What to do instead:** Describe the situation conceptually. "We are evaluating acquiring a competitor brand" becomes "we are evaluating a potential strategic transaction". Claude can still help you structure the thinking.

---

### 4. Security and Operational Credentials (Critical Risk — Never Paste)
- System usernames, passwords, API keys, tokens
- Internal server names, VPN configurations, or network architecture
- Store alarm codes, safe combinations, or access credentials
- Vendor portal login details

**There is no safe version of pasting this. Never do it.**

---

### 5. Legal and Compliance Matters (High Risk)
- Legal advice you have received — sharing this externally may waive privilege
- Active litigation details, settlement amounts, or dispute correspondence
- Regulatory submissions or responses before they are filed or published
- Internal investigation findings or reports

---

## How to Anonymise Before You Paste

Use these substitutions as a habit:

| Original | Replace with |
|---|---|
| Employee name | Role title (e.g. "the Planning Manager") |
| Customer name / ID | "the customer" or "a high-value account" |
| Supplier name (if sensitive) | "our primary knitwear supplier" or "Supplier A" |
| Exact rand figures | Ranges (e.g. "approx. R50–60m") |
| Store names (if linked to performance issues) | "Store in Region X" or "Store 1 / Store 2" |
| Colleague performance concerns | "a member of the team" — describe the behaviour, not the person |
| Internal system / platform names | "our planning system" or "our stock management platform" |

After anonymising, re-read the content once and ask: "If this appeared in a news article, would it cause damage?" If yes, anonymise further.

---

## The "What Can I Actually Ask Claude?" Reframe

You almost always can get what you need from Claude without sharing sensitive specifics.

Instead of pasting your actual supplier contract, describe the situation:
> "I have a supplier contract where we have 60-day payment terms and the supplier is claiming force majeure. What clauses should I check and what questions should I ask legal?"

Instead of pasting raw salary data, describe the problem:
> "I need to assess whether my team structure is cost-efficient given our revenue. What framework would help me think through this?"

Instead of pasting confidential financials, describe the analytical challenge:
> "I need to assess margin risk in a range where sell-through is below plan. What factors should I analyse and what decisions do I need to make?"

Claude gives you the framework, the questions, and the analytical structure. You apply it to the real numbers in your own systems. That's often more useful anyway.

---

## Safe Before You Paste — Checklist

Run through this before pasting anything sensitive into Claude:

- [ ] **No names of individuals** (staff, customers, suppliers linked to sensitive matters)
- [ ] **No exact financial figures** that are commercially sensitive or not publicly disclosed
- [ ] **No personal data** covered by POPIA
- [ ] **No M&A or strategic information** not yet public
- [ ] **No legal correspondence** or privileged advice
- [ ] **No credentials, passwords, or system access details** — ever
- [ ] **No HR or disciplinary information** linked to identifiable individuals
- [ ] **Checked: does my company's AI policy permit this?** (If you don't know, assume no.)

If you tick all boxes: proceed.
If you have doubt on any item: anonymise it first, or ask Claude how to get the same help without sharing that information (Prompt 35 in the dashboard does this for you).

---

## A Note on Claude's Data Handling

When you use Claude via claude.ai:
- Anthropic does not use your conversations to train its models by default (you can check your privacy settings)
- Your conversations are stored temporarily for the session and may be reviewed by Anthropic for safety purposes
- You are not sending data to your company's systems — you are sending it to Anthropic's servers

When your company has an enterprise agreement with Anthropic:
- Data handling terms are governed by that agreement
- Check with your IT or legal team for the specifics

**Final authority on what can and cannot be shared with external AI tools rests with your company's IT, data governance, and legal teams. When in doubt, ask them — not Claude.**

---

*Practical, plain English. No legalese. Designed to be read once and remembered.*
