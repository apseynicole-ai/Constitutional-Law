# Dad's Director AI Command Centre

A custom-built, offline Claude AI toolkit for Senior Directors in South African fashion and apparel retail.
37 executive-grade prompts, organized across 7 categories, with a live dashboard interface.

---

## What This Is

A personal AI command centre built specifically for director-level work in fashion retail. It gives you:

- **37 ready-to-use prompts** — written in an executive tone, specific to your industry, ready to copy and paste into Claude
- **7 categories** — Director OS, Project Oversight, Decision-Making, Fashion Retail, Meetings, Claude Hacks, and Confidentiality
- **Global variables** — fill in your company, project, or meeting name once and it's auto-inserted when you copy
- **Search and filtering** — find any prompt by keyword in seconds
- A fully **offline dashboard** — no internet required, no accounts, no tracking

---

## How to Open It

1. Navigate to the `director-ai-command-centre/` folder
2. Double-click `index.html`
3. It opens in your default browser — Chrome, Edge, or Safari all work
4. No installation, no internet connection, no software required

---

## How to Use the Prompt Cards

1. **Fill in your global variables** at the top of the dashboard (Company / Brand, Project Name, etc.) — these are substituted automatically when you copy
2. **Browse by category** using the sidebar or navigation strip, or use the **search box** to find a prompt by keyword
3. **Read the card** — each one shows you what the prompt is for and when to use it
4. **Click "View full prompt text"** to expand and preview the prompt
5. **Click "Copy Prompt"** — the text is copied to your clipboard with your variables already substituted
6. **Paste into Claude** and replace any remaining `[BRACKETED PLACEHOLDERS]` with your specific context before pressing Enter
7. The note on each card reminds you: always replace bracketed placeholders before pasting into Claude

---

## Recommended First Setup in Claude

### Step 1: Create a Claude Project called "Director Cockpit"

In Claude, click **Projects** → **New Project** → name it "Director Cockpit".

Projects give Claude persistent memory of your context. You only brief it once per project.

### Step 2: Add General Non-Confidential Context

In the Project settings, add a brief note about who you are and what you do. Keep it non-confidential — no company financials, no named staff, no supplier contracts.

Example:
> I am a Senior Director at a major South African fashion and apparel retail brand. My function covers buying, planning, supplier management, store operations, and digital. I want direct, structured responses. No filler. Lead with the most important point. Label all assumptions clearly.

### Step 3: Paste the Director Cockpit Master Prompt (Prompt 01)

Copy Prompt 01 from the dashboard and paste it into your Project's system instructions or as your first message in the project. This sets the standing rules for how Claude works with you across all sessions in this project.

### Step 4: Use the Relevant Prompt Card Per Workflow

Each time you sit down to work, pick the appropriate prompt card from the dashboard, copy it, and paste it into Claude — then add your specific content (meeting notes, project updates, the document you need summarised, etc.).

You don't need to re-explain who you are in each session if you're working in the Director Cockpit project. Claude retains that context.

---

## Suggested Weekly Workflow

| Day / Moment | Prompt to Use |
|---|---|
| **Monday morning** | Prompt 02: Weekly Director Briefing |
| **Before any key meeting** | Prompt 23: Meeting Prep Pack |
| **Before Exco or Board** | Prompt 24: Board/Exco Briefing Prep |
| **Before any major approval** | Prompt 15: Approval Gate Checklist |
| **During a live session with new info** | Prompt 29: Delta Mode Prompt |
| **End of Thursday / Friday** | Prompt 03: Delta Update + Prompt 04: Risk Radar |
| **After any campaign ends** | Prompt 20: Campaign Post-Mortem |
| **When something is going wrong** | Prompt 07: Project Rescue Mode |
| **Whenever you get a long document** | Prompt 30: No-Fluff Executive Summary Prompt |
| **Before pasting anything sensitive** | Prompts 34–37: Confidentiality & Safety section |

---

## Confidentiality Warning

**Do not paste confidential company information into Claude unless your company's IT and data governance policy explicitly permits it.**

This includes: employee names and HR data, customer personal data, financial data under NDA, supplier contract terms, M&A information, and pricing strategy.

See `confidentiality_guardrails.md` in this folder for a full practical guide on what to share, how to anonymise, and how to get the same quality of help from Claude without exposing sensitive information.

---

## Files in This Folder

| File | What it is |
|---|---|
| `index.html` | The dashboard — open this in your browser |
| `styles.css` | Visual design (linked automatically) |
| `app.js` | All functionality and prompt data (linked automatically) |
| `prompts.md` | All 37 prompts in plain markdown — use without the dashboard |
| `confidentiality_guardrails.md` | Practical guide on what not to share and how to stay safe |
| `README.md` | This file |

---

*Built as a birthday gift. Made to be useful every single week.*
