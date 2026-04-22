---
title: Data Interpretation
parent: Quantitative Aptitude
nav_order: 17
---

# Data Interpretation

**Tier 1 · Priority 8.** The payoff chapter. DI is not a new skill — it is Percentages + Ratios + Averages speed-tested on presented data. Every calculation lives in a chapter you already know; the new skill is **reading fast, picking smart, and approximating hard**.

Status: not started

## The ONE Mental Model

> **Read → Extract → Reduce → Calculate.** In that order, always.

DI problems fail when you skip step 2 (wrong number extracted from wrong row/column) or step 3 (full calculation instead of approximation). Most wrong answers in DI are reading errors, not calculation errors.

**The 30-second chart scan** — before touching any question:
1. What is the chart measuring? (Title)
2. What are the axes / columns? (Labels)
3. What is the unit? (Lakhs? Crores? Thousands? %)
4. What is the approximate range of values? (Sets the denominator for % questions)
5. Are there multiple series / categories? (Identifies which bar/slice to pull)

Only after this scan should you read the first question.

## DI Sub-types and Their Attack Protocols

### Tables

**Nature:** Dense grid of numbers. No visual. Hardest to eyeball.

**Attack:**
- Identify row and column precisely before reading the cell.
- Compute % change or ratio column-by-column, not row-by-row (usually faster).
- Approximation wins here: if options spread by >5%, round aggressively.
- Watch units — same table may mix lakhs and crores in different columns.

**Trap:** Reading the wrong row (one off) or misidentifying the "total" row.

---

### Bar Graphs

**Nature:** Comparative quantities; single or grouped bars.

**Attack:**
- Eyeball ratios before computing. If bar A is roughly 2/3 of bar B, that's 66.67%.
- For grouped bars: confirm which bar belongs to which category by legend before every question.
- % change between adjacent bars: (new − old)/old. Use fraction-table for clean answers.

**Trap:** Swapped legend colours / patterns. Re-check the legend after every 2 questions.

---

### Line Graphs

**Nature:** Trends over time. YoY change, growth rates.

**Attack:**
- "Highest increase" → largest upward slope, not the highest point.
- "Which year had highest growth rate?" → compute (this − prev)/prev for top 2–3 candidates only.
- Two lines: "when are they equal?" → intersection; "difference?" → vertical gap.

**Trap:** Confusing the value with the change. "In which year was sales highest?" ≠ "In which year did sales grow most?"

---

### Pie Charts

**Nature:** Parts of a whole as angles or percentages.

**Attack:**
- Convert degrees to %: multiply by 100/360 = 5/18. Equivalently: 36° = 10%, 72° = 20%, 90° = 25%, 180° = 50%.
- Value of a slice = % × total. Most errors happen by forgetting the total.
- Two pie charts (two years): for % change, compute absolute values from each, then (new − old)/old.

**Trap:** "What % of total?" when the chart already shows %: answer IS the slice %. Don't divide again.

Key angles worth knowing cold:

| Degrees | % |
|---------|---|
| 36° | 10% |
| 54° | 15% |
| 72° | 20% |
| 90° | 25% |
| 108° | 30% |
| 120° | 33.33% |
| 135° | 37.5% |
| 144° | 40% |
| 180° | 50% |
| 216° | 60% |
| 270° | 75% |

---

### Caselets (Paragraph DI)

**Nature:** Data buried in prose. The hardest sub-type for time management.

**Attack:**
1. **Rewrite as a table first.** Always. Don't jump to the questions.
2. Underline every number and its label as you read.
3. Identify what's given (absolute or %) and what's derived (total, ratios).
4. Fill the table column-by-column, not question-by-question.

**Trap:** A caselet gives partial data — some cells must be calculated from other given cells. Compute these *before* reading the questions so you don't re-derive under time pressure.

---

### Mixed / Combo DI

**Nature:** Two charts (e.g., bar + pie, or table + line) covering the same data set.

**Attack:**
- Read both charts in the 30-sec scan; identify what each provides.
- Cross-reference: one chart may give totals, the other splits. Combine to get individual values.
- Questions usually require data from both — never answer from just one.

**Trap:** Using the wrong chart for a question. Label your notes: "bar = production, pie = export share".

---

### Missing-Data DI

**Nature:** One or more cells in a table are marked "?". You solve them sequentially.

**Attack:**
- Identify constraints: row totals, column totals, given ratios.
- Solve cells in dependency order (easiest known-constraint first).
- Fill the whole table before answering questions.

---

## The Approximation Decision

> **If options differ by more than 5% of each other, approximate aggressively. If they differ by less than 2%, compute exactly.**

| Option spread | Approach |
|---------------|----------|
| Options: 40, 48, 56, 64 (spread ~10%) | Round to nearest 5; eyeball |
| Options: 44.4, 44.8, 45.2, 45.6 (spread <1%) | Compute to one decimal place |
| Options: 40%, 45%, 50%, 55% | Round to nearest integer; compare |

**Key approximation moves:**

- $48.7\% \approx 50\% - 1\% = (N/2) - (N/100)$. Use for any value near a fraction anchor.
- $\sqrt{N}$: bracket between two perfect squares, interpolate linearly.
- Long division: if quotient is between two integers, pick the one; exact digit rarely matters.
- Ratio-reduction first: $\frac{348}{522} = \frac{2}{3} = 66.67\%$. Always simplify before computing.

## Calculation Arsenal for DI

These are the moves that save 15–20 seconds per question:

1. **Fraction-table lookup.** 37.5% → 3/8. Never compute ×0.375.
2. **Ratio simplification.** Cancel common factors before multiplying. $\frac{480}{720} = \frac{2}{3}$ immediately.
3. **% → fraction → multiply.** $16.67\%$ of $N$ = $N/6$.
4. **Cross-cancel in chains.** $\frac{A}{B} \times \frac{B}{C} = \frac{A}{C}$. Spotted instantly in multi-step DI.
5. **Split the %**: $17\%$ of $450 = 10\% + 5\% + 2\% = 45 + 22.5 + 9 = 76.5$.
6. **Anchor to round numbers.** $\frac{1984}{5012} \approx \frac{2000}{5000} = 0.4 = 40\%$.
7. **Unit-digit only when options differ in last digit.** Often avoids full multiplication.
8. **Average via deviation.** For a row of similar numbers, pick the middle, sum deviations (Averages Formula 3).

## Question-Picking Strategy (exam-only)

Not all DI questions are equal. Within a set:

| Question type | Difficulty | Pick first? |
|---------------|------------|-------------|
| Single-cell lookup | Low | Yes |
| % of single year | Low | Yes |
| Ratio of two values | Low–Medium | Yes |
| YoY % change | Medium | Yes |
| Average across years | Medium | Yes |
| Combined/total across all categories | Medium | Often |
| "Which year had highest X?" — needs scan | Medium | After above |
| Cross-chart (bar + pie combined) | High | Last in set |
| Missing-value caselet cell | High | Last in set |

**Set-level strategy:** Scan all 5 questions in a DI set before answering any. Pick the 3 easiest first. If question 4 is a multi-step monster, skip it and move on — a partially-answered set scores more than a fully-attempted slow one.

**Set-selection in the exam:** If two sets are available, prefer:
- Table or bar over caselet (faster to extract data)
- A set where 3+ questions are "% of" or "ratio" type
- Sets with round numbers in the data (fewer computation steps)

## Common Traps (memorize — these are where marks leak)

1. **Unit mismatch.** "Sales in Lakhs" vs "profit in Crores" in the same question. Convert before computing.
2. **"The following year" confusion.** "In the year following the highest sales year" — identify the year with highest sales first, then take the next.
3. **Wrong base for % change.** % change is always over the OLD value. "From 2021 to 2022" → old = 2021.
4. **Pie chart double-division.** If the pie already shows %, the slice value is already "% of total". Don't divide by 100 again.
5. **Bar graph legend swap.** Grouped bars — always re-verify which bar belongs to which series before each question.
6. **"More than" vs "as a % of".** "By how much more?" → absolute difference. "What % more?" → difference/old × 100.
7. **Averages of averages.** If different years have different bases, weighted average, not arithmetic mean of the % column.
8. **Reading across years in a pie.** Two pies for two years with same categories — the same category's slice % can differ. Don't carry over %.
9. **Cumulative total confusion.** Some tables show cumulative figures; subtraction needed to get per-period value.
10. **Caselet "remaining" trap.** "After A and B take their shares, C gets the rest" — compute A + B and subtract from total. Easy to miss under pressure.

### Trap Pairs (drill side-by-side)

| Sounds similar | Correct reading |
|----------------|-----------------|
| "Highest value in 2022" | Read the 2022 row/bar directly |
| "Highest growth in 2022" | (2022 − 2021)/2021 × 100 |
| "Ratio of A to B" | A/B |
| "B as a % of A" | (B/A) × 100 |
| "% increase from X to Y" | (Y − X)/X × 100 (base = X) |
| "% decrease from Y to X" | (Y − X)/Y × 100 (base = Y) |
| "By how much did A exceed B?" | A − B (absolute) |
| "By what % did A exceed B?" | (A − B)/B × 100 |
| "Production in Crores; Profit margin 12%" | Profit = 12% × production in Crores |
| "Revenue 500 L; costs 400 L; profit%?" | (100/400) × 100 = 25% (base = cost = CP) |
| "Combined avg of A and B" | (Total A + Total B) / total count — not (avg A + avg B)/2 unless equal counts |
| "Average annual growth rate" | NOT arithmetic mean of YoY %s; use geometric mean or CAGR |

## DI Attack Plan by Question Type

| Question | One-line attack |
|----------|----------------|
| "Find value of X in year Y" | Read cell directly; apply unit |
| "% change from Y1 to Y2" | (Y2−Y1)/Y1 × 100; use fraction table |
| "Ratio of A to B" | Simplify the two cell values; cancel |
| "Average over N years" | Sum the N cells ÷ N; use deviation method |
| "By how many units did X exceed Y?" | Subtract absolute values |
| "What % of total is category C?" | C / total × 100; total must be stated or computed |
| "In which year was growth highest?" | Scan for largest absolute jump first; confirm with ratio |
| "Combined value of A and B in year Y" | Add the two cells; same unit |
| "Value in year Y if grew Z% from Y−1" | Cell × (1 + Z/100) |
| "Angle/slice for category C in pie" | Value / total × 360 OR directly if % given: % × 3.6 |

## Links to Other Chapters

- **Percentages** — % change, % of total: every second DI question.
- **Ratio & Proportion** — ratio of two values, combined category splits.
- **Averages** — row/column averages, deviation method for clustered numbers.
- **Profit & Loss** — revenue/cost/margin tables in RBI/NABARD DI.
- **SI/CI** — "YoY growth rate for N years" = CAGR, same as CI.
- **Ratio ↔ % flip** — DI is 60% faster when you stop computing and start converting.

## Time Budget (per-question targets)

| Question type | Target | Red flag if > |
|---------------|--------|---------------|
| Single cell lookup | 15 s | 25 s |
| Ratio of two cells | 20 s | 35 s |
| % change (two cells) | 25 s | 40 s |
| Average across N years | 30 s | 50 s |
| "Which year had highest X" (needs scan) | 40 s | 60 s |
| Cross-chart (two data sources) | 45 s | 75 s |
| Caselet cell extraction | 60 s first cell | 90 s |

**Per-set target:** 5 questions in 5–6 minutes. If a set runs past 7 minutes, abandon the hardest question and move on.

## Exam Phrasing Cues (Indian banking/insurance)

- **SBI / IBPS PO Prelims**: 2 DI sets, 10 questions. Usually 1 table + 1 bar/line. Heavy on % change and ratio.
- **SBI / IBPS PO Mains**: 3–4 DI sets, 15–20 questions. Includes caselet and mixed DI. Approximation is decisive.
- **IBPS Clerk**: 1–2 DI sets, simpler data. Direct lookup + one % change question.
- **RBI Grade B**: DI is the hardest in the sector. Multi-chart, multi-step, unusual units. Read every label twice.
- **NABARD Grade A**: agriculture/rural data. Same mechanics but unfamiliar category names — read title carefully.
- **LIC AAO**: Insurance tables. Revenue/expense/claim ratio DI common. P&L flavor.
- **Keyword → attack**:
  - "approximately" → round aggressively, options will be spread
  - "exactly" / "find the value" → compute carefully, options are close
  - "the following/preceding year" → shift year index, don't use same year
  - "combined" / "total" → sum across categories or years
  - "difference between" → absolute subtraction, not %
  - "how many times" → ratio (A/B), not percentage
  - "as a percentage of" → numerator/denominator × 100, confirm base
  - "average" → sum/count, watch for weighted average if groups differ
  - "grew at the same rate" → apply % growth to given base

## PYQ-Flavor Drill (meta-drill — process, not numbers)

Practice these five question types on any DI set you encounter:

1. **Ratio question** — simplify the two cells, cancel common factors, done.
2. **% change** — apply (new − old)/old × 100; use fraction table on the result.
3. **Average** — use deviation method; pick the middle value in the range as anchor.
4. **"Which year highest/lowest"** — scan all candidates first (3-second visual), compute only top 2.
5. **Cross-chart** — label which chart gives what, combine the two values, compute.

Run a timed mock on one 5-question DI set per day. Target: 5 questions in 5 minutes. Log which step slowed you — extraction, calculation, or approximation — and fix that step, not the question type.

## Stage-7 Self-Test

On your next full-length mock, after attempting DI sets, answer:

1. Did I do the 30-second chart scan before question 1? *(If no: this is the first fix)*
2. Did I pick the 3 easy questions first? *(If no: change set-opening habit)*
3. Was my approximation aggressive enough? *(Check: did I recompute what I already estimated?)*
4. Did I misread a unit, row, or column? *(If yes: slow down the extraction step only)*
5. Did any set take more than 7 minutes? *(If yes: practice abandoning the hardest question)*

If all five answers are yes/no correctly, DI execution is solid — speed is the only remaining variable.

## Revision Triggers

- If ratio questions are slow, the bottleneck is fraction-table recall in Ratio & Proportion — revisit that chapter.
- If % change is slow, the bottleneck is "% change over old base" — revisit Percentages Formula 5.
- If caselet extraction is slow, practice re-writing paragraph data into a 2×3 table in under 60 seconds — timed.
- If cross-chart questions are consistently wrong, practice labeling each chart before reading questions.
- Any DI question that takes more than 90 seconds is a signal — the bottleneck is arithmetic, not DI skill. Fix speed via Simplification warmup.
