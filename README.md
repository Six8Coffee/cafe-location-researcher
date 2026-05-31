# Olivia — Café Location Researcher

**[📖 Live demo →](https://olivia.hospotech.io)**

**Most café location tools answer the question. This one asks if you're asking the right one.**

A folder-based AI researcher for independent Australian café operators making location decisions — first venue or expansion. Drop it into a Claude project and get a research partner that investigates what you don't know you don't know, not just what you asked about.

---

## Setup (do this first)

**Step 1 — Enable web search.**
This researcher uses live data sources — ABS, commercial listings, council DA portals, going concern listings. Without web search, it cannot investigate. In your Claude project: Settings → Project Settings → enable Web Search. If you're not sure whether it's on, ask Claude: "Do you have web search enabled?"

**Step 2 — Add this folder to your Claude project.**
Upload all files from this folder into a Claude project. Claude will use them as its operating context for every conversation in that project.

**Step 3 — Tell the researcher what you're investigating.**
Start with one of these:
- "I'm looking at opening in [suburb / town]. Can you research it?"
- "There's a café for sale on Bsale in [location]. Can you investigate it?"
- "I'm about to sign a lease in [location]. Can you check the DA pipeline?"
- "I'm looking for where to open my first café in regional NSW. I'm thinking [areas]."

The researcher will ask a few questions before searching — that's intentional. The questions determine what to search for and how to read what comes back.

---

## What's in the folder

```
olivia/
├── identity.md              ← who Olivia is + founder's lived position
├── rules.md                 ← diagnostic gate · investigation protocol · output format
├── examples.md              ← three complete investigations, one per mode
├── WRITEUP.md               ← design rationale
├── README.md                ← this file
└── reference/
    ├── investigation-types.md   ← 4 modes → source routing
    ├── source-guide.md          ← what each source is for + reliability note
    ├── domain-concepts.md       ← lease + planning vocabulary
    └── regional-adjustment.md   ← visitor economy framework (Yass NSW)
```

---

## What to expect

The researcher will not immediately produce a summary. It will ask what type of decision you're making, what your concept is, and what you've already looked at. Then it searches.

Every investigation produces:
- What the sources show — synthesised across sources, not listed one by one
- Where sources conflict — named explicitly, not buried
- Open questions — what the investigation raised but couldn't close
- What this investigation cannot tell you — specific steps for what to verify on the ground
- A sources log — every source used, when accessed, and its reliability limitation

The researcher presents findings. It does not make recommendations. The decision is yours.

---

## Who this is for

Independent café operators in Australia — whether you're choosing a first location, evaluating an acquisition, testing an expansion hypothesis, or checking a lease before you sign. Also useful for anyone advising operators: business brokers, commercial agents, hospitality consultants.

Not useful for: operators who want someone to make the decision for them, or who want a general market overview rather than an investigation of a specific question.

---

## Built by

Daniel Neuhaus — café owner and roaster, Trader & Co. | Six8 Coffee Roasters, Yass NSW. Built this because the standard location research tools assume metro. Most of the decisions worth making are regional.
