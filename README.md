# Outbound Council

Sales research and outreach toolkit powered by Claude Code. Research fire/EMS departments, find contacts, write personalized cold emails scored by 6 expert advisors.

## For Sales Reps

**[Open the setup guide](rep-kit/onboarding.html)** to get started. Download this repo, open the HTML file in your browser, and follow the steps. 15 minutes to set up.

What you get:
- Research any fire/EMS department by name. Claude finds the chief, medical director, training officer, fleet data, and recent news.
- Write cold emails in YOUR voice, scored by 6 sales advisors (Cialdini, Hormozi, Klaff, Voss, Rackham, Schwartz).
- Built-in AI slop detection. No "I hope this finds you well." No "Best regards." No em dashes. Your emails sound human.
- Objection handling and follow-up sequences for when departments reply.
- Automatic pricing calculations based on department size and intubation volume.
- Institutional knowledge that compounds over time (learnings.md).

## Structure

```
outbound-council/
├── rep-kit/
│   ├── onboarding.html        ← Start here. Setup guide for reps.
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
│   ├── physician-founder-frame.md  ← IntuBlade-specific selling angle
│   ├── public-safety-buyer.md      ← Fire/EMS buyer psychology
│   └── deployment-kit-psychology.md ← Free kit offer structure
├── voices/
│   └── voice-template.md      ← Fill this out with your writing style
├── learnings.md               ← Accumulates knowledge over time
├── SKILL.md                   ← Claude Code skill definition
└── LICENSE
```

## Quick Start (for reps)

```bash
git clone https://github.com/napiermd/outbound-council.git ~/outbound-council
cp ~/outbound-council/rep-kit/CLAUDE.md ~/outbound-council/CLAUDE.md
cd ~/outbound-council && claude
```

Then type: "Research [department name] in [state]"

## Requirements

- Claude Pro subscription ($20/month) at [claude.ai](https://claude.ai)
- Claude Code CLI: `npm install -g @anthropic-ai/claude-code`
- Node.js 18+ (for npm)

## License

MIT
