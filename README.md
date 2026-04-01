# Outbound Council

Open-source sales research and outreach toolkit powered by Claude Code. Research target organizations, find contacts, write personalized cold emails scored by 6 expert sales advisors.

Works for any B2B company. You bring your product, pricing, and buyer profile. The council brings the sales science.

## What you get

- **Research any organization by name.** Claude finds decision-makers, contacts, org data, and recent signals.
- **Write cold emails in YOUR voice**, scored by 6 advisors (Cialdini, Hormozi, Klaff, Voss, Rackham, Schwartz).
- **Anti-AI slop detection.** Banned words, banned phrases, banned patterns. Your emails sound human.
- **Reply tracking.** Claude scans your inbox, classifies replies (OOO, wrong person, real interest), drafts responses.
- **Gmail integration.** Drafts created directly in your inbox. No copy-pasting.
- **CRM sync.** Plugs into your CRM API if you have one.
- **Shared learnings.** Team knowledge compounds over time. What one rep discovers helps everyone.
- **Objection handling.** 11 common objections with response scripts and follow-up cadence.

## Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/napiermd/outbound-council.git ~/outbound-council

# 2. Copy the project instructions
cp ~/outbound-council/rep-kit/CLAUDE.md ~/outbound-council/CLAUDE.md

# 3. Set up your company config (private, gitignored)
mkdir -p ~/outbound-council/company
cp ~/outbound-council/company.md.template ~/outbound-council/company/COMPANY.md
# Edit company/COMPANY.md with your product, pricing, buyer details

# 4. Create your voice profile
cp ~/outbound-council/voices/voice-template.md ~/outbound-council/voices/your-name.md
# Edit with your writing style

# 5. Start
cd ~/outbound-council && claude
```

Then type: "Research [organization name] in [location]"

## Setup Guide

**[Open the setup guide](https://napiermd.github.io/outbound-council/rep-kit/onboarding.html)** for step-by-step instructions with copy-paste buttons. 20 minutes to set up.

## Requirements

- Claude Pro subscription ($20/month) at [claude.ai](https://claude.ai)
- Claude Code CLI: `npm install -g @anthropic-ai/claude-code`
- Node.js 18+

## Structure

```
outbound-council/
├── rep-kit/
│   ├── onboarding.html        ← Setup guide for reps
│   └── CLAUDE.md              ← Project instructions (copy to root)
├── references/
│   ├── anti-ai-slop.md        ← Banned AI words/phrases/patterns
│   ├── objections-and-replies.md ← Reply handling, follow-ups, competitive intel
│   ├── schwartz.md            ← Copywriting and awareness levels
│   ├── hormozi.md             ← Offers, pricing, irresistible deals
│   ├── klaff.md               ← Frame control, authority, pitch
│   ├── cialdini.md            ← Persuasion psychology, social proof
│   ├── voss.md                ← Negotiation, empathy, calibrated questions
│   ├── rackham.md             ← SPIN selling, discovery conversations
│   ├── founder-frame.md.template      ← Template: your selling angle
│   ├── buyer-psychology.md.template   ← Template: your buyer's psychology
│   └── offer-psychology.md.template   ← Template: your trial/demo offer
├── voices/
│   └── voice-template.md      ← Fill out with your writing style
├── company/                   ← YOUR company data (gitignored, private)
│   └── COMPANY.md             ← Product, pricing, buyer, API config
├── company.md.template        ← Template to copy into company/
├── learnings.md               ← Team-wide shared knowledge
├── learnings/                 ← Per-rep learnings (no merge conflicts)
├── SKILL.md                   ← Claude Code skill definition
├── .gitignore                 ← Keeps company/ and .env private
└── LICENSE
```

## How it works

1. **You configure** `company/COMPANY.md` with your product, pricing, and buyer profile. This directory is gitignored — your business details never hit GitHub.
2. **Each rep** fills out a voice profile in `voices/your-name.md`.
3. **Claude reads everything** at session start: the 6 advisors, anti-AI-slop rules, your company config, shared learnings, and the rep's voice.
4. **Rep types** "Research [organization]" — Claude finds contacts, signals, and org data.
5. **Rep types** "Write the email" — Claude writes it, scores it against all 6 advisors, filters AI slop.
6. **Rep types** "Create the draft" — goes straight to Gmail.
7. **Rep types** "Check for replies" — Claude scans inbox and classifies responses.

## The 6 Advisors

| Advisor | Domain | Applied to |
|---------|--------|-----------|
| Schwartz | Awareness levels, copywriting | Email messaging and structure |
| Hormozi | Irresistible offers, pricing | Offer positioning and dollar anchoring |
| Klaff | Frame control, authority | Expert positioning, credential line |
| Cialdini | Persuasion, social proof | Specificity, reciprocity triggers |
| Voss | Tactical empathy, negotiation | Closing questions, reply handling |
| Rackham | SPIN selling, discovery | Opening conversations, not closing |

## License

MIT
