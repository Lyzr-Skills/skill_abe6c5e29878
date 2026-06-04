# Fact-Check Criteria — Telugish Scriptwriter

## Purpose

Every factual claim in the script must be verified against the research dossier before delivery. This prevents misinformation, protects VR Raja's credibility, and ensures the channel can defend every statement.

---

## Step 1: Extract All Factual Claims

Go through the entire script and extract every claim of these types:

| Claim Type | Examples | What to Look For |
|------------|----------|-----------------|
| **Statistics & Numbers** | "91 lakh voters", "₹27,000 crores", "50% population" | Any number, percentage, or quantity |
| **Dates & Timelines** | "April 25 na", "2026 elections", "last 10 years" | Any date, year, month, or time period |
| **Attributions** | "PM Modi said...", "WHO report prakaram..." | Any claim attributed to a person or organization |
| **Events** | "China satellite launched", "Budget passed" | Any described occurrence |
| **Cause-Effect** | "Ee policy valla 5 crore people benefited" | Any statement that X caused Y |
| **Data Points** | "15% more voting than last time" | Any comparative or absolute data claim |
| **Legal/Political Facts** | "Article 370 was removed", "SC ruling prakaram..." | Any claim about law, constitution, or government action |
| **Quotes** | "'India is ready' ani PM chepparu" | Any direct or paraphrased quote |

**Tip:** Re-read the script slowly for claim extraction. Every paragraph has at least 1-2 claims. You will miss subtle ones on a first pass.

---

## Step 2: Source Tier Priority

When verifying each claim, prioritize sources in this order:

### Tier 1: Primary Sources (Highest)
- Government databases (Election Commission, Census, RBI, etc.)
- Official government orders, gazettes, notifications
- Court rulings and judgments (full text)
- International organization reports (UN, WHO, World Bank, IMF)
- Official party statements, press releases
- Verified video/audio recordings of events

### Tier 2: Major News Organizations
- Reuters, Associated Press, BBC
- The Hindu, Indian Express, Economic Times
- Major international outlets (NYT, WaPo, Guardian)
- Verified Indian news channels (NDTV, Times Now — factual coverage, not opinion)

### Tier 3: Secondary / Analytical
- Academic papers, think tank reports (ORF, PRS, CPR, etc.)
- Verified expert analysis
- Fact-checking organizations (Alt News, Boom Live, Factly, etc.)
- Data journalism projects (IndiaSpend, etc.)

### Tier 4: Contextual / Background (Lowest)
- Wikipedia (for general context only — not for specific stats)
- Blogs, social media posts (unless quoting the person directly)
- Unverified YouTube claims
- "Many people say", "It is believed" — these are NOT sources

---

## Step 3: Verification Status System

For each extracted claim, find evidence in the research dossier and assign:

| Status | Icon | Criteria | Action |
|--------|------|----------|--------|
| **VERIFIED** | ✅ | 2+ credible sources (at least Tier 1 or 2) agree on the same fact | Keep in script as-is |
| **PARTIALLY VERIFIED** | ⚠️ | Only 1 credible source, or multiple sources but all lower tier (3-4) | Rewrite with conditional language |
| **UNVERIFIED** | ❌ | No source found in dossier, or sources disagree without clear resolution | REMOVE entirely from script |
| **CONTRADICTED** | 🔄 | Different sources give different numbers/versions of the same claim | Use most credible version, note the discrepancy |

### Status Determination Flowchart

```
Does the dossier contain the claim?
├── YES → How many sources?
│   ├── 2+ sources → Are they independent?
│   │   ├── YES → ✅ VERIFIED
│   │   └── NO (same source cited twice) → ⚠️ PARTIALLY
│   └── 1 source only → ⚠️ PARTIALLY VERIFIED
└── NO → Do sources say something different?
    ├── YES → 🔄 CONTRADICTED (use most credible version)
    └── NO → ❌ UNVERIFIED (remove from script)
```

---

## Step 4: Handling Each Status

### ✅ VERIFIED Claims

Keep in script as-is. No changes needed.

### ⚠️ PARTIALLY VERIFIED Claims

Rewrite the claim with conditional/qualifier language to signal uncertainty:

| Original (direct) | Rewritten (with qualifier) |
|-------------------|---------------------------|
| "91 lakh voters ni remove chesaru" | "Oka report prakaram, 91 lakh voters ni remove chesaru" |
| "₹27,000 crores fraud jarigindi" | "Oka estimation prakaram, ee fraud amount ₹27,000 crores varaku undochu" |
| "15% population affected" | "Initial surveys prakaram, 15% population affected ayyindi" |

Conditional language options:
- "oka source prakaram..."
- "initial reports prakaram..."
- "oka estimation prakaram..."
- "data suggest chestundi..."
- "... ani oka claim undi"
- "... varaku undochu"

### ❌ UNVERIFIED Claims

**Remove entirely from the script.** Do not rephrase. Do not keep with a qualifier. If the dossier has zero evidence, the claim cannot stay. This protects VR Raja's credibility.

After removal, check if the surrounding text still flows. If removal leaves a gap, fill it with verified content from the dossier.

### 🔄 CONTRADICTED Claims

Compare the conflicting sources. Apply these rules:
1. **Tier 1 source beats Tier 2-4.** Use the primary source version.
2. **Official data beats media report.** Government numbers take precedence.
3. **Recent data beats old data.** If 2025 and 2023 numbers differ, use 2025 with a note.
4. **If tiers are equal** (e.g., two Tier 2 news orgs disagree), present both: "Kani oka controversy undi — X sources antunnayi A ani, Y sources antunnayi B ani."

Example:
```
[⚠️ Sources disagree]
Election Commission data prakaram, 70 lakh voters removed. Kani
opposition parties matram antunnayi — 91 lakhs ani. Ee controversy
ippatiki clear kaaledu.
```

---

## Step 5: Special Claim Types

### Statistics & Numbers
- Verify the exact number, year/period, and context
- Check: is this total or net? Cumulative or annual?
- If the dossier only has a range, use: "X nunchi Y varaku"

### Dates & Timelines
- Verify exact date in dossier
- If only month/year available, say: "April 2026 lo"
- Do NOT fabricate exact dates from partial information

### Quotes
- Verify exact wording
- If only paraphrase available, say: "X cheppedi entante..."
- NEVER invent a quote that doesn't exist in the dossier

### Cause-Effect
- Verify the claim that X caused Y
- Check for alternative explanations in the dossier
- If causation is uncertain, use: "... ani evidence undi" or "... connect chesi choodachu"

### Events
- Verify: did the event happen as described?
- Check: date, location, participants, outcome
- If details conflict, use the most credible version

---

## Step 6: Quality Rules

1. **Never verify using the same source twice.** Two citations from Reuters count as 1 source. Two separate news orgs = 2 sources.

2. **ZERO source support = ❌ REMOVE.** No exceptions. Even if the claim seems obvious.

3. **At least 70% of claims should be ✅ VERIFIED.** If a script has too many ⚠️ or 🔄, the research dossier was insufficient. Flag this to the user.

4. **Every ❌ removal must be reported** in the fact-check report with the exact claim that was removed.

5. **No "common knowledge" exceptions.** "Everyone knows X" is not verification. Find a source.

6. **After removing ❌ claims, re-read the script** to ensure it still makes sense. If removal created a logic gap, bridge it with verified content.

---

## Fact-Check Report Template

Append this to the end of every script:

```
═══ FACT-CHECK REPORT ═══
Script: {Topic}
Date: {YYYY-MM-DD}
Source: Research dossier

Summary:
• ✅ VERIFIED: {N} claims
• ⚠️ PARTIALLY VERIFIED: {N} claims
• ❌ UNVERIFIED: {N} claims (REMOVED from script)
• 🔄 CONTRADICTED: {N} claims

--- Detailed Breakdown ---

✅ VERIFIED:
1. "{Claim text}" — Source(s): {source names}
2. "{Claim text}" — Source(s): {source names}
...

⚠️ PARTIALLY VERIFIED:
1. "{Claim text}" — Source: {source name} (1 source only)
   Action: Rewritten with qualifier: "{rewritten version}"
...

❌ UNVERIFIED (REMOVED):
1. "{Original claim text}" — No sources found
   Action: Removed from script
...

🔄 CONTRADICTED:
1. "{Claim text}" — Source A: {version} / Source B: {version}
   Resolution: {most credible version used}
...

Coverage:
• Total claims: {N}
• % verified (✅ + ⚠️): {N}%
• % removed (❌): {N}%
• Source citations in script: {N} (target: ≥70% of claims have nearby source cite)
```

---

## Example Fact-Check Report

```
═══ FACT-CHECK REPORT ═══
Script: 2026 West Bengal Elections — Voter List Controversy
Date: 2026-04-15
Source: Research dossier (4 sources: EC data, 2 news articles, 1 report)

Summary:
• ✅ VERIFIED: 8 claims
• ⚠️ PARTIALLY VERIFIED: 2 claims
• ❌ UNVERIFIED: 1 claim (REMOVED)
• 🔄 CONTRADICTED: 1 claim

--- Detailed Breakdown ---

✅ VERIFIED:
1. "91 lakh voters missing from West Bengal voter list" — EC official statement + Times of India
2. "AI technology used for voter list cleaning" — EC press release + Economic Times
3. "Opposition parties protested against removal" — 3 news sources (ToI, Hindu, Indian Express)
4. "EC claimed cleaning was to remove duplicate entries" — EC statement + The Hindu
5. "TMC said supporters were unfairly targeted" — TMC press release + news coverage
6. "BJP supported the cleanup" — BJP statement + Times of India
7. "15 lakh duplicate entries found" — EC data + The Hindu report
8. "West Bengal has 7.5 crore registered voters" — EC voter data + Census

⚠️ PARTIALLY VERIFIED:
1. "Majority of removed voters are TMC supporters" — Source: TMC claim (1 source)
   Action: Rewritten as: "TMC antundi — majority removed voters TMC supporters ani"

❌ UNVERIFIED (REMOVED):
1. "Bangladeshi infiltrators added as fake voters" — EC data does not support this
   Action: Removed from segment 2

🔄 CONTRADICTED:
1. "Number of duplicate entries" — EC says 15 lakh, Opposition says 25 lakh
   Resolution: Used EC version (Tier 1 source)

Coverage:
• Total claims: 12
• % verified (✅ + ⚠️): 83%
• % removed (❌): 8%
• Source citations in script: 9 of 12 claims have nearby source cite (75%)
```
