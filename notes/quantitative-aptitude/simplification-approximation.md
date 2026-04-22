---
title: Simplification & Approximation
parent: Quantitative Aptitude
nav_order: 18
---

# Simplification & Approximation

**Tier 1 · Priority 9.** Treat as a **daily skill**, not a chapter to study once. Speed and accuracy on simplification is the single biggest lever on your overall quant score — every other chapter's time budget depends on how fast your arithmetic is.

Status: use daily as warmup

Reference tables (squares, cubes, fraction↔%, divisibility, unit-digit cycles) are in [Simplification Shortcuts & Tricks](simplification-shortcuts.md). This note is the *strategy and attack-plan layer* on top of those tables, plus a quick-recap cheat-sheet at the end for in-session use.

## The ONE Mental Model

> **Never compute more than you need to.** The answer is one of four options. Use every structural property of the expression — unit digit, parity, order of magnitude — to eliminate before computing.

Every question has a fastest path. Finding it takes 2 seconds; computing the wrong path can take 30. The exam rewards the person who pauses to look for shortcuts, not the one who dives into long multiplication.

**Two question types, two different strategies:**

| Type | Stem keyword | Strategy |
|------|--------------|----------|
| **Simplification** | "Simplify", "Find the value", "=" | Exact answer needed. Use VBODMAS + identities + fraction cancellation. |
| **Approximation** | "Approximate", "nearly equal", "≈", "approximately" | Round aggressively. Options are spread >5%. |

Reading the stem carefully is half the marks — the two types reward different tactics.

## VBODMAS — the only order rule

**V**inculum (bar) → **B**rackets `( )` `{ }` `[ ]` innermost first → **O**f (multiplication disguised) → **D**ivision → **M**ultiplication → **A**ddition → **S**ubtraction.

D and M have equal priority — left to right. Same for A and S.

**Common error:** treating "of" as addition. `1/2 of 40 + 10 = 20 + 10 = 30`, NOT `1/2 of 50 = 25`.

## Typical BODMAS Structures (Exam Patterns)

The actual exam pattern is not "simple BODMAS" — it's nested fractions, "of" clauses, and mixed operations.

### Pattern 1: Nested fractions with "of"

**Problem:** $\frac{2}{3}$ of $\frac{5}{7} + \frac{4}{5} \div \frac{8}{15} - \frac{1}{2}$

**Attack:**
1. Resolve "of" first: $\frac{2}{3} \times \frac{5}{7} = \frac{10}{21}$.
2. Resolve division: $\frac{4}{5} \div \frac{8}{15} = \frac{4}{5} \times \frac{15}{8} = \frac{60}{40} = \frac{3}{2}$.
3. Now addition/subtraction: $\frac{10}{21} + \frac{3}{2} - \frac{1}{2}$.
4. Combine the two halves: $\frac{3}{2} - \frac{1}{2} = 1$. Then $\frac{10}{21} + 1 = \frac{31}{21}$.

**Key move:** always cancel *before* multiplying fractions. Never compute $4 \times 15 = 60$ then $5 \times 8 = 40$ — cancel the 4 and 8 (giving 1:2) and the 5 and 15 (giving 1:3) first.

### Pattern 2: "Find the value of ?"

**Problem:** $24 \times ? + 36 = 180$

**Attack:**
1. Isolate: $24 \times ? = 144$.
2. $? = 144/24 = 6$.

Always move additive terms to the RHS first, then divide.

### Pattern 3: Square root / cube root fill-in-the-blank

**Problem:** $\sqrt{?} + 15 = 40$

**Attack:**
1. $\sqrt{?} = 25$.
2. $? = 625$ ($25^2$).

Know squares 1–30 cold (table in simplification-shortcuts.md §2.2).

### Pattern 4: Mixed fractions + decimals

**Problem:** $3\frac{1}{4} \times 2.4 - 0.5 \times 6$

**Attack:**
1. Convert mixed to improper: $3\frac{1}{4} = \frac{13}{4}$.
2. Convert decimals to fractions: $2.4 = \frac{12}{5}$, $0.5 = \frac{1}{2}$.
3. First term: $\frac{13}{4} \times \frac{12}{5} = \frac{13 \times 3}{5} = \frac{39}{5} = 7.8$.
4. Second term: $\frac{1}{2} \times 6 = 3$.
5. $7.8 - 3 = 4.8$.

Decimals → fractions whenever multiplication / division is involved.

### Pattern 5: Powers and indices

**Problem:** $8^4 \times 4^3 \div 2^{10}$

**Attack:**
1. Same base: $2^{12} \times 2^6 \div 2^{10} = 2^{12+6-10} = 2^8 = 256$.

Convert everything to the same base before applying index laws.

## The Elimination Toolkit (before computing)

Use these in order. Stop as soon as one option remains.

### 1. Unit-digit check
Compute only the last digit of the expression. Eliminates 2–3 options in under 5 seconds.

- Addition/subtraction: add/subtract unit digits only.
- Multiplication: multiply unit digits only.
- Powers: use the unit-digit cycle table (simplification-shortcuts.md §15).

**Example.** $473 \times 87 = ?$ → unit of $3 \times 7 = 21$ → unit digit **1**. Eliminate options not ending in 1.

### 2. Odd/even parity
Even × anything = even. Odd × odd = odd. Even + odd = odd.

Eliminates options instantly when options mix even and odd.

### 3. Order-of-magnitude estimate
Round every number to 1 significant figure. ±20% in 3 seconds.

**Example.** $\sqrt{2499}$ → $\sqrt{2500} = 50$. Eliminate options far from 50.

### 4. Digital sum (casting out nines)
Match the digital sum of the expression to options. See simplification-shortcuts.md §5.

Confirmation tool, not primary. Fails when the answer is a multiple of 9.

## Approximation Attack Patterns

Approximation is the primary method for the "Approximate" question type. The key insight: **options are always >5% apart**, so aggressive rounding is safe.

### Pattern A: Square root × integer

**Problem:** $\sqrt{624} \times 16.02 = ?$

1. $\sqrt{624} \approx 25$ ($25^2 = 625$).
2. $16.02 \approx 16$.
3. $25 \times 16 = 400$.

### Pattern B: Large-number percent

**Problem:** $39.97\%$ of $2499 + 15.03\%$ of $1199 = ?$

1. $40\%$ of $2500 = 1000$.
2. $15\%$ of $1200 = 180$.
3. $1000 + 180 = 1180$. Match to options.

### Pattern C: Division with near-anchors

**Problem:** $2399 \div 16.02 = ?$

1. $2400 / 16 = 150$. Match.

### Pattern D: Sum / product of near-round numbers

**Problem:** $4899 + 2034 - 1011 = ?$

1. $4900 + 2034 - 1011$. Exact: $5923$. Or: $4900 + 2034 = 6934; 6934 - 1011 = 5923$.
2. Approximate: $4900 + 2000 - 1000 = 5900$. Match.

### Pattern E: Multi-step with square root and %

**Problem:** $\sqrt{624} \times 16.02 + 289.97 \div 18.1$

1. $\sqrt{624} \approx 25$; $16.02 \approx 16$; $25 \times 16 = 400$.
2. $290 / 18 \approx 16.1$ (since $18 \times 16 = 288$).
3. $400 + 16 = 416$. Match.

### Pattern F: Square root inside fraction

**Problem:** $\sqrt{144.99} + \sqrt{80.95} = ?$

1. $\sqrt{145} \approx 12.04$; $\sqrt{81} = 9$.
2. $12 + 9 = 21$.

### Rounding strategy

**Errors should cancel.** If you round one factor up, round another down.
- Example: $48.6 \times 21.3 \approx 50 \times 20 = 1000$ (both rounded differently — but 5% error).
- Tighter: $49 \times 21 = 1029$ (exact is $1035$; 0.6% error).

Pick anchors that are easy *and* close. Don't round $48.6$ to $50$ if $48.6 \approx 48$ is just as easy.

## Calculation Moves (speed shortcuts)

### Squaring near a base
$(n \pm d)^2 = n^2 \pm 2nd + d^2$. Keep $d$ small.
- $97^2 = (100-3)^2 = 10000 - 600 + 9 = 9409$.
- $53^2 = (50+3)^2 = 2500 + 300 + 9 = 2809$.

### Difference of squares
$a^2 - b^2 = (a+b)(a-b)$.
- $83^2 - 17^2 = 100 \times 66 = 6600$.

### Multiply near-equal numbers
$(a+d)(a-d) = a^2 - d^2$. Pick $a$ = midpoint.
- $47 \times 53 = 50^2 - 3^2 = 2491$.

### ×99, ×999, ×98
$n \times 99 = 100n - n$.
- $47 \times 99 = 4700 - 47 = 4653$.
- $47 \times 98 = 4700 - 94 = 4606$.

### Fraction cancellation before multiplying
Always simplify before multiplying.
- $\frac{3}{8} \times \frac{64}{15}$ → cancel 8 and 64 → $\frac{3 \times 8}{15} = \frac{24}{15} = \frac{8}{5} = 1.6$.

### Surds
$\sqrt{a} \times \sqrt{b} = \sqrt{ab}$. Simplify under the radical first.
- $\sqrt{48} = \sqrt{16 \times 3} = 4\sqrt{3}$.

### Indices: same base
- $8^4 \times 4^3 = 2^{12} \times 2^6 = 2^{18}$.

## The Daily Warmup Protocol

5 minutes before every quant session. Non-negotiable.

| Activity | Count | Time |
|----------|-------|------|
| Simplification MCQs (BODMAS + fraction) | 10 | 3 min |
| Approximation MCQs | 5 | 1.5 min |
| Mental: squares 1–30 in order | once | 30 s |

**What to log:** Any question that took > 35 s. Find the specific operation that caused the slowdown — long multiplication, fraction reduction, root estimation — and drill that operation the next day.

## Common Traps (memorize)

1. **VBODMAS order violated.** "Of" done after addition. "Of" is multiplication — do it before + and −, but after brackets.
2. **Vinculum (bar) missed.** $\overline{3 + 5} \times 2 = 16$, not $3 + 10 = 13$.
3. **Negative inside brackets.** $-(a - b) = -a + b$. Sign error is the #1 slip.
4. **Squaring a fraction.** $\left(\frac{2}{3}\right)^2 = \frac{4}{9}$. Numerator AND denominator squared.
5. **Approximate on "exact" question.** In "Simplify" questions, approximation gives the wrong option.
6. **Compute on "approximate" question.** Burns 30 seconds per question; fails to finish the set.
7. **Unit-digit of even power of 2.** Cycle 2,4,8,6 → period 4. $2^{100}$: 100 mod 4 = 0 → 4th in cycle → unit digit **6**.
8. **"Of" applied to wrong operand.** $20\%$ of $80 + 40 = (20\% \times 80) + 40 = 56$, not $20\% \times 120 = 24$.
9. **Mixed fraction misread.** $3\frac{1}{4} \ne 3 \times \frac{1}{4}$. It's $3 + \frac{1}{4} = \frac{13}{4}$.
10. **Decimal place miscount.** $1.2 \times 3.4 = 4.08$, not $40.8$. Count decimal places from both operands.

## Time Targets

| Question type | Target | Red flag |
|---------------|--------|----------|
| Pure simplification (BODMAS, integers) | 30 s | 50 s |
| Simplification with fractions/surds | 40 s | 60 s |
| Approximation (≈ type) | 25 s | 40 s |
| Indices / surds simplification | 40 s | 65 s |
| "Find ?" equation | 30 s | 50 s |

If consistently over red flag: the bottleneck is one of multiplication tables, squares table, or fraction↔% recall. Identify which and drill that specific table for 5 days.

## Exam Phrasing Cues

- **"Simplify"** → exact answer; no rounding. VBODMAS + identities.
- **"Approximate value"** / **"≈"** → round aggressively; options spread.
- **"Find the value of"** (with surds/indices) → convert to same base.
- **"What should replace ?"** → isolate the `?`, work backward.
- **"Which of the following is equal to..."** → compute the LHS, match.

**SBI/IBPS Prelims:** 10–15 Simplification/Approximation questions; fastest marks in the paper. Target 100% accuracy — these are not the questions to get wrong.

## Stage-7 Drill (10 problems, 5 minutes total)

Target: 30 seconds each. Use the elimination toolkit first.

**Simplification:**

1. $3\frac{2}{5} \times 2\frac{1}{2} - 1\frac{1}{4} = ?$
   *$\frac{17}{5} \times \frac{5}{2} - \frac{5}{4} = \frac{17}{2} - \frac{5}{4} = \frac{34-5}{4} = \frac{29}{4} = 7.25$.*

2. $\frac{2}{3}$ of $\frac{9}{16} + \frac{1}{4} \div \frac{3}{8} = ?$
   *$\frac{2}{3} \times \frac{9}{16} = \frac{3}{8}$; $\frac{1}{4} \div \frac{3}{8} = \frac{1}{4} \times \frac{8}{3} = \frac{2}{3}$; $\frac{3}{8} + \frac{2}{3} = \frac{9+16}{24} = \frac{25}{24}$.*

3. $\sqrt{?} \times 8 = 96$.
   *$\sqrt{?} = 12$, $? = 144$.*

4. $25\%$ of $640 + 15\%$ of $200 = ?$
   *$160 + 30 = 190$.*

5. $15 \times 16 + 12 \times 18 - 20 \times 11 = ?$
   *$240 + 216 - 220 = 236$.*

**Approximation:**

6. $\sqrt{440.99} \times 14.02 \approx ?$
   *$\sqrt{441} = 21$; $21 \times 14 = 294$.*

7. $39.89\%$ of $1499.98 + 24.97\%$ of $799.98 \approx ?$
   *$40\% \times 1500 = 600$; $25\% \times 800 = 200$; $600 + 200 = 800$.*

8. $3599.98 \div 15.03 + 17.99^2 \approx ?$
   *$3600/15 = 240$; $18^2 = 324$; $240 + 324 = 564$.*

9. $\sqrt[3]{2196.9} \times 14.98 \approx ?$
   *$\sqrt[3]{2197} = 13$; $13 \times 15 = 195$.*

10. $(124.97 \times 8.01) \div (19.98 \times 5.02) \approx ?$
    *$125 \times 8 / (20 \times 5) = 1000 / 100 = 10$.*

If you completed 10 in under 5 minutes with 9+ correct, Simplification is at exam pace.

## In-Session Cheat-Sheet (recap)

When using this note during study, these are the top-8 moves to reach for before anything else:

| Move | When to use |
|------|-------------|
| Fraction ↔ % flip | Any expression with "% of N" or decimal like 0.625 |
| Unit-digit elimination | Multiple-choice with options differing in last digit |
| Approximate before multiplying | Any "approximate" question |
| Cancel before multiplying fractions | Every fraction multiplication |
| Square near a base: $(n±d)^2$ | Squaring 2-digit or 3-digit numbers |
| Difference of squares | $a^2 - b^2$ form |
| ×99, ×98 via $100n - n$ (or $-2n$) | Near-power-of-10 multipliers |
| Deviation method for averages | Row of similar numbers |

Full reference tables: simplification-shortcuts.md.

## Revision Triggers

- If warmup questions consistently exceed 35 s, track the operation type and target it — usually 2-digit multiplication or cube roots.
- If approximation answers are off by one option, rounding is too aggressive or too lazy — calibrate using the "spread >5%" rule.
- If indices problems stall, re-read Laws of Indices in simplification-shortcuts.md §8 and do 5 problems.
- If VBODMAS errors appear in mocks, slow down the read-order step — write V-B-O-D-M-A-S at the top of each question for the next 20 problems.
- If "Find ?" problems slow you, practice isolating the variable as a first step, before any arithmetic.
