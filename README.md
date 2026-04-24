# Sales Council

Source-backed GTM council for medtech, healthcare, enterprise sales, positioning, founder-led outbound, and clinical software market entry.

This repo started as an outbound toolkit. It is now being rebuilt around actual operators and thinkers whose public work can be distilled into usable GTM voices.

## What you get

- **A real-person GTM council**: April Dunford, Andy Raskin, Matt Dixon, John McMahon, Bob Moesta, Jason Lemkin, Omar Khateeb, Zed Williamson, Howie Chan, Josh Makower, and specialist extensions.
- **Source-backed profiles**: each profile should point to books, podcasts, talks, essays, company material, or other primary/near-primary sources.
- **Activation packs**: reusable voice sets for EMS outbound, hospital sales, founder-led GTM, and procedural-guidance AI.
- **Company-specific context**: private `company/` files keep IntuBlade buyer psychology, founder frame, deployment kit, and pricing out of Git.
- **Outbound execution**: anti-AI-slop rules, rep voice matching, reply handling, Gmail/CRM hooks, and shared learnings remain available.

## Why this exists

IntuBlade is not a generic SaaS motion.

The company sells a single-use video laryngoscope today, with software, QA/QI, computer vision, and procedural guidance opportunities ahead. That requires a council that can reason across:

- EMS and fire-chief outbound
- medical-device adoption
- hospital value analysis
- physician-founder authority
- enterprise qualification
- category creation
- software expansion
- clinical AI trust and workflow fit

## Structure

```text
sales-council/
├── council/
│   ├── roster.md              # Active voices and activation rules
│   ├── source-index.md        # Profile audit surface
│   ├── profile-standard.md    # Required profile format
│   ├── enrichment-protocol.md # How to deepen voices from sources
│   ├── scoring-rubrics.md     # Review criteria by use case
│   ├── invocation-patterns.md # How to activate the council
│   ├── operating-principles.md
│   ├── refresh-checklist.md
│   └── session-template.md
├── packs/
│   ├── ems-outbound-pack.md
│   ├── hospital-sales-pack.md
│   ├── founder-led-gtm-pack.md
│   └── procedural-guidance-ai-pack.md
├── references/
│   ├── april-dunford.md
│   ├── john-mcmahon.md
│   ├── ...
│   ├── anti-ai-slop.md
│   └── legacy framework files
├── voices/
│   └── voice-template.md
├── company/                   # private, gitignored
├── learnings.md
├── learnings/
├── rep-kit/
├── SKILL.md
└── README.md
```

## Core Council

| Voice | Domain |
| --- | --- |
| April Dunford | B2B positioning and sales narrative |
| Andy Raskin | Strategic narrative |
| Matt Dixon | Challenger Sale, JOLT, buyer indecision |
| John McMahon | Enterprise sales, MEDDICC, deal inspection |
| Bob Moesta | Jobs to Be Done, demand-side sales |
| Jason Lemkin | Founder-led SaaS and enterprise GTM |
| Omar Khateeb | Modern medtech GTM and social selling |
| Zed Williamson | Medical device sales acceleration |
| Howie Chan | Medtech brand and physician choice |
| Josh Makower | Biodesign and need-driven medtech innovation |

Specialist extensions include Mark Roberge, Christopher Lochhead, Mark Copeland, Scott Nelson, Bob Wachter, Halle Tecco, and Lisa Suennen.

## Activation Packs

- **EMS Outbound**: fire departments, EMS chiefs, medical directors, training officers, regional clusters.
- **Hospital Sales**: health systems, value analysis, procurement, ED/anesthesia, enterprise pilots.
- **Founder-Led GTM**: Andrew-led outreach, strategic narrative, conference follow-up, investor/customer story.
- **Procedural Guidance AI**: software, QA/QI, computer vision, clinical AI, workflow adoption.

## Setup

```bash
# 1. Clone the repo
git clone https://github.com/napiermd/outbound-council.git ~/sales-council

# 2. Copy the project instructions if using Claude Code
cp ~/sales-council/rep-kit/CLAUDE.md ~/sales-council/CLAUDE.md

# 3. Set up private company context
mkdir -p ~/sales-council/company
cp ~/sales-council/company.md.template ~/sales-council/company/COMPANY.md

# 4. Create your writing voice profile
cp ~/sales-council/voices/voice-template.md ~/sales-council/voices/your-name.md
```

## Profile Standard

Every profile should include:

- core domain
- why the voice matters in this council
- canonical sources
- current signals
- what the voice cares about
- signature questions
- what the voice respects
- what the voice is suspicious of
- what the voice would push on
- common advice pattern
- best pairings and tensions
- decision style
- watch sources
- last reviewed date and source confidence

See `council/profile-standard.md`.

## Enrichment Workflow

Profiles are enriched in layers:

1. Identify the voice and domain.
2. Ground the profile in canonical sources.
3. Add IntuBlade-specific applications.
4. Add source-mining backlogs and extraction targets.
5. Mine books, podcasts, talks, essays, and social material into frameworks, stories, language patterns, and decision heuristics.

Use:

- `council/enrichment-protocol.md`
- `council/enrichment-matrix.md`
- `council/voice-extraction-template.md`
- `council/profile-depth-rubric.md`

## Legacy Frameworks

The original Cialdini, Hormozi, Rackham, Voss, Klaff, and Schwartz files remain in `references/`. They are now treated as tactical frameworks underneath the real-person council, not as the main roster.

## License

MIT
