---
title: Simplification & Approximation
parent: Quantitative Aptitude
nav_order: 18
---

# Simplification & Approximation

**Tier 1 · Priority 9.** Treat as a **daily skill**, not a chapter to study once. Speed and accuracy on simplification is the single biggest lever on your overall quant score — every other chapter's time budget depends on how fast your arithmetic is.

Status: use daily as warmup

Reference tables (squares, cubes, fraction↔%, divisibility, unit-digit cycles) are in [Simplification Shortcuts & Tricks](simplification-shortcuts.md). This note is the *strategy and exam layer* on top of those tables.

## The ONE Mental Model

> **Never compute more than you need to.** The answer is one of four options. Use every structural property of the expression — unit digit, odd/even, order of magnitude — to eliminate before computing.

Every simplification question has a fastest path. Finding it takes 2 seconds; computing the wrong path can take 30. The exam rewards the person who pauses to look for shortcuts, not the one who dives into long multiplication.

## VBODMAS — the only order rule

**V**inculum (bar) → **B**rackets `( )` `{ }` `[ ]` innermost first → **O**f (multiplication disguised) → **D**ivision → **M**ultiplication → **A**ddition → **S**ubtraction.

D and M have equal priority — left to right. Same for A and S.

**Common error:** treating "of" as addition. `1/2 of 40 + 10 = 20 + 10 = 30`, not `1/2 of 50 = 25`.

## The Elimination Toolkit (use before computing)

Work through these in order — stop as soon as one option remains.

### 1. Unit-digit check
Compute only the last digit of the expression. Eliminates 2–3 options in under 5 seconds.

- Addition/subtraction: add/subtract unit digits only.
- Multiplication: multiply unit digits only.
- Powers: use the unit-digit cycle table (in simplification-shortcuts.md).

**Example.** $473 \times 87 = ?$ Unit digit of $3 \times 7 = 21$ → unit digit 1. Eliminate any option not ending in 1.

### 2. Odd/even parity
Is the answer odd or even? Eliminates options instantly when half are odd and half are even.

- Even × anything = even. Odd × odd = odd.
- Even + odd = odd. Even + even = even.

### 3. Order-of-magnitude estimate
Round every number to 1 significant figure. Gets you within ±20% in 3 seconds. Eliminates options that are wildly off.

**Example.** $\sqrt{2499} \approx \sqrt{2500} = 50$.

### 4. Digital sum (casting out nines)
Compute digital sum of the expression and match to options. See simplification-shortcuts.md §5.

Use as confirmation, not as primary — the method fails when the answer is a multiple of 9 (all nines look the same).

## Approximation Rules

Approximation is the primary method for the "Approximation" question type — where the question explicitly asks for `≈`.

| Situation | Rule |
|-----------|------|
| Options spread > 5% | Round aggressively to nearest 5 or 10 |
| Options spread 2–5% | Round to nearest integer |
| Options spread < 2% | Compute to one decimal place |
| Square root | Bracket between perfect squares; interpolate |
| Cube root | Know cubes 1–20 cold; bracket and interpolate |
| Long division | Estimate quotient to one decimal; match |
| Mixed expression | Simplify biggest term first; approximate smaller terms |

**Rounding strategy:** Always round such that errors cancel. If you round one factor up, round another down. Example: $48.6 \times 21.3 \approx 50 \times 20 = 1000$ (both rounded — error ~5%). Better: $49 \times 21 = 1029$ (tighter).

## Calculation Moves (indexed to exam question types)

These are the non-obvious speed moves. The obvious ones (×10 = shift decimal) are in simplification-shortcuts.md.

### Squaring near a base
$(n \pm d)^2 = n^2 \pm 2nd + d^2$. Keep $d$ small by picking a round-number base.
- $97^2 = (100-3)^2 = 10000 - 600 + 9 = 9409$.
- $53^2 = (50+3)^2 = 2500 + 300 + 9 = 2809$.

### Difference of squares
$a^2 - b^2 = (a+b)(a-b)$. Extremely fast when $a$ and $b$ are close.
- $83^2 - 17^2 = (83+17)(83-17) = 100 \times 66 = 6600$.

### Multiply near-equal numbers
$(a+d)(a-d) = a^2 - d^2$. Pick $a$ as midpoint.
- $47 \times 53 = (50-3)(50+3) = 2500 - 9 = 2491$.

### ×99, ×999 etc.
$n \times 99 = 100n - n$. Extend for any near-power-of-10.
- $47 \times 99 = 4700 - 47 = 4653$.

### Fraction ↔ % swap in BODMAS
When an expression contains "% of N" inside a larger expression, convert % to fraction first — then cancel before multiplying.
- $\frac{3}{8}$ of $\frac{64}{15}$ = cancel 8 and 64 → $\frac{3 \times 8}{15} = \frac{24}{15} = 1.6$.

### Surds (square roots) pattern
$\sqrt{a} \times \sqrt{b} = \sqrt{ab}$. $\frac{\sqrt{a}}{\sqrt{b}} = \sqrt{a/b}$. Simplify under the radical first, then take root.
- $\sqrt{48} = \sqrt{16 \times 3} = 4\sqrt{3}$.

### Indices: same base
$a^m \times a^n = a^{m+n}$; $a^m \div a^n = a^{m-n}$; $(a^m)^n = a^{mn}$.
Convert everything to same base before operating — especially powers of 2, 3, 5.
- $8^4 \times 4^3 = 2^{12} \times 2^6 = 2^{18}$.

## The Daily Warmup Protocol

5 minutes before every quant session. Non-negotiable.

| Activity | Count | Time |
|----------|-------|------|
| Simplification MCQs (BODMAS + fraction) | 10 | 3 min |
| Approximation MCQs | 5 | 1.5 min |
| Mental drill: squares 1–30 in order | once | 30 s |

**What to log:** Any question that took > 35 seconds. Find the specific operation that caused the slowdown — long multiplication, fraction reduction, root estimation — and drill that operation the next day.

## Common Traps (memorize)

1. **VBODMAS order violated.** "Of" done after addition. Always handle "of" before + and −.
2. **Vinculum (bar) missed.** $\overline{3 + 5} \times 2 = 8 \times 2 = 16$, not $3 + 5 \times 2 = 13$.
3. **Negative inside brackets.** $-(a - b) = -a + b$. Distributing the minus is the #1 sign error.
4. **Squaring a fraction.** $\left(\frac{2}{3}\right)^2 = \frac{4}{9}$, not $\frac{2}{9}$.
5. **Approximate too early.** In "exact" simplification questions, approximation gives the wrong option.
6. **Unit-digit of even power of 2.** Cycle is 2, 4, 8, 6 — period 4. $2^{100}$: 100 mod 4 = 0 → 4th in cycle → unit digit **6**.
7. **"Of" applied to wrong operand.** $20\%$ of $80 + 40 = 20\% \times 80 + 40 = 56$, not $20\% \times 120 = 24$.

## Time Targets

| Question type | Target | Red flag |
|---------------|--------|----------|
| Pure simplification (BODMAS, integers) | 30 s | 50 s |
| Simplification with fractions/surds | 40 s | 60 s |
| Approximation (≈ type) | 25 s | 40 s |
| Indices / surds simplification | 40 s | 65 s |

If you're consistently over the red flag, the bottleneck is one of: multiplication tables, squares table, fraction↔% recall. Identify which and drill that specific table for 5 days.

## Exam Phrasing Cues

- **"Simplify"** → exact answer; no rounding. Use VBODMAS + algebraic identities.
- **"Approximate value"** / **"≈"** → round aggressively; options are spread.
- **"Find the value of"** (with surds/indices) → convert to same base, apply index laws.
- **"What should replace ?"** (fill-in the blank) → work backwards from the expression structure.

**SBI/IBPS Prelims**: 10–15 Simplification/Approximation questions; these are the fastest marks in the paper. Target 100% accuracy here — these are not the questions to get wrong.

## Revision Triggers

- If warmup questions consistently exceed 35 s, track the operation type and target it — usually it's 2-digit multiplication or cube roots.
- If approximation answers are off by one option, your rounding is too aggressive or too lazy — calibrate using the "spread > 5%" rule.
- If indices problems stall, re-read Laws of Indices in simplification-shortcuts.md §8 and do 5 problems.
- If VBODMAS errors appear in mocks, slow down the read-order step — write V-B-O-D-M-A-S at the top of each question for the next 20 problems.
