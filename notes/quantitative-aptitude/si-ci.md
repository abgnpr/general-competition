---
title: Simple & Compound Interest
parent: Quantitative Aptitude
nav_order: 14
---

# Simple & Compound Interest

**Tier 1 · Priority 5.** Pure percentage application. Do AFTER Percentages. If multipliers feel native, SI/CI is a weekend chapter; if not, no amount of SI/CI drill helps.

Status: not started

## The ONE Mental Model

Interest is **percentage applied over time**. The only question: is the percentage applied to the *original* principal each year (SI — linear) or to the *running* balance (CI — exponential)?

$$\boxed{\;\text{SI: Amount} = P(1 + RT/100) \qquad \text{CI: Amount} = P(1 + R/100)^T\;}$$

> **SI adds the same rupee each year. CI adds a slightly bigger rupee each year.** Everything else in this chapter is either a formula variant (half-yearly, different rates per year) or a shortcut for computing the *gap* between SI and CI.

Corollaries:

- CI is just successive % change applied $T$ times — same machinery as Percentages Formula 12.
- Every "population grows at $r\%$" or "price appreciates at $r\%$" question is a CI question.
- "Depreciates at $r\%$" = CI with $(1 − R/100)^T$.
- The SI-CI *difference* is where the exam trap lives — memorize the 2-yr and 3-yr shortcuts.

## The Central Formulas

### Simple Interest

$$\text{SI} = \dfrac{PRT}{100} \qquad A_{\text{SI}} = P + \text{SI} = P\left(1 + \dfrac{RT}{100}\right)$$

Linear in both $R$ and $T$. SI for 5 years = 5 × SI for 1 year. That scaling property alone solves half of SI problems.

### Compound Interest

$$A_{\text{CI}} = P\left(1 + \dfrac{R}{100}\right)^T \qquad \text{CI} = A_{\text{CI}} - P$$

Each year: multiply by $(1 + R/100)$. Year 2 interest is slightly higher than Year 1 because the base grew.

## The Full Formula Set

Core five in **bold**. The rest are tools you recognize on sight.

### A. Simple Interest

| # | Formula | When |
|---|---------|------|
| **1** | **SI = PRT/100** | Definition |
| **2** | A = P + SI = P(1 + RT/100) | Amount after $T$ years |
| 3 | P = (100 × SI)/(RT); R = (100 × SI)/(PT); T = (100 × SI)/(PR) | Solve for the missing variable |
| 4 | SI for different rates per year: just sum $\sum (P R_i / 100)$ for each year | "First year 5%, second 6%, third 8%" |
| 5 | Money doubles under SI when RT = 100 | "At what rate will ₹X double in 5 years?" → R = 20% |

### B. Compound Interest

| # | Formula | When |
|---|---------|------|
| **6** | **A = P(1 + R/100)^T** | Yearly compounding |
| **7** | **CI = A − P = P[(1 + R/100)^T − 1]** | Interest only, not amount |
| 8 | P = A / (1 + R/100)^T | Reverse — find original principal |
| 9 | Different rates per year $R_1, R_2, R_3$: A = P(1 + R_1/100)(1 + R_2/100)(1 + R_3/100) | Variable-rate CI |
| 10 | Money doubles under CI: T ≈ **72/R** (Rule of 72) | Quick doubling estimate |

### C. Compounding frequency (the #1 trap after base confusion)

When interest compounds $n$ times per year, **rate per period = R/n; number of periods = nT.**

| # | Formula | When |
|---|---------|------|
| **11** | **Half-yearly: A = P(1 + R/200)^(2T)** | Rate halves, periods double |
| 12 | Quarterly: A = P(1 + R/400)^(4T) | Rate quarters, periods quadruple |
| 13 | Monthly: A = P(1 + R/1200)^(12T) | Rarely asked but fair game |
| 14 | Continuously compounded (theoretical): A = P·e^(RT/100) | Not in banking syllabus; ignore |

Mnemonic: **"Divide the rate, multiply the time."**

### D. SI–CI difference (the highest-yield shortcut)

Memorize these cold — they appear almost every paper.

| # | Formula | When |
|---|---------|------|
| **15** | **2-yr difference: CI − SI = P(R/100)²** | Classic PYQ. Also = SI of one year's interest |
| **16** | **3-yr difference: CI − SI = P(R/100)² × (3 + R/100)** | Memorize as `P(R/100)²(300+R)/100` |
| 17 | 2-yr: CI = SI × (1 + R/200) (when same P, R, T=2) | Converts one into the other fast |
| 18 | Interpretation of Formula 15: Year-2 CI interest = Year-1 interest × (1 + R/100). Difference = R% of Year-1 SI. | Derivation-level understanding |

### E. Installments / EMI-flavor (SI-based)

| # | Formula | When |
|---|---------|------|
| 19 | Equal installment $x$ clears debt $A$ in $n$ years under SI at $R\%$: $A(1 + nR/100) = x \cdot n + x \sum_{k=0}^{n-1} \dfrac{kR}{100}$ | Rare, but SBI PO asks ~1 per year |
| 20 | Simpler form: each installment grows in value from its payment date to final date. Set total = compounded debt. | Construct equations; don't memorize a closed form |

### F. Applied CI (same formula, different label)

| # | Formula | When |
|---|---------|------|
| 21 | Population growth at $r\%$: Final = Initial × (1 + r/100)^T | Demographic MCQs |
| 22 | Depreciation at $r\%$: Final = Initial × (1 − r/100)^T | Machines, vehicles |
| 23 | Variable population: year-1 grows $a\%$, year-2 drops $b\%$ → Final = P × (1+a/100)(1−b/100) | Multi-year shifts |
| 24 | Present value of future amount $F$ at $r\%$ for $T$ yrs: PV = F / (1 + r/100)^T | Discounting — occasionally asked |

## High-Yield Shortcuts

1. **CI for 2 years at $R\%$ = equivalent of successive $R\%, R\%$.** Effective rate (Percentages Formula 9) = $2R + R²/100$. Compute on $P$ directly.
2. **SI-CI gap (2-yr) = $P(R/100)²$.** Identical to Percentages "equal ±R%" trap. Memorize.
3. **SI-CI gap (3-yr) = $P(R/100)² \times (3 + R/100)$.** Most-tested shortcut. At $R = 10\%$, gap = $P \times 0.01 \times 3.1 = 0.031P$.
4. **Rule of 72.** Doubling time under CI ≈ 72/R. At 8%, ~9 years. At 12%, ~6 years. Great for ballparking, not exact.
5. **CI → SI conversion.** If CI for 2 yrs at $R\%$ is given, SI = CI / (1 + R/200). Frequent exam flip.
6. **Half-yearly at $R\%$ for 1 year.** Equivalent to one year CI at $R + R²/400$. Example: 10% half-yearly for 1 yr = effective 10.25%.
7. **"At the same rate, SI doubles in 20 yrs."** Instantly: $R \times 20 = 100 \Rightarrow R = 5\%$. Then any CI question at the same rate opens up.
8. **CI on two different principals compared.** Ratios of amounts = ratios of principals (rate and time equal). Ratios in CI inherit principal ratios only.

## MCQ Tactics (exam-only)

- **Assume P = 100** (or 10,000 / 1,000 whichever gives clean numbers). All outputs become absolute rupees.
- **Assume P = LCM of denominators.** If rate is 12.5% (= 1/8), P = 800 keeps everything integer.
- **Plug R = 10%** in derivation problems first — gives the cleanest 2-yr ($P \times 0.01$) and 3-yr ($0.031P$) gaps.
- **Back-solve "find principal".** Four options → compute CI or amount for each, match the given value. Faster than algebra when numbers are ugly.
- **Ballpark via SI first.** CI ≥ SI for same $P, R, T$. If options bracket SI value, pick the one slightly above.
- **Divisibility checks.** SI = PRT/100 → SI must divide cleanly when all of P, R, T are integers. Use to eliminate options.

## Calculation Speed Hacks

- **CI at 10% for small T** — memorize:
  - T=2: amount factor 1.21, CI factor 0.21
  - T=3: amount factor 1.331, CI factor 0.331
  - T=4: amount factor 1.4641, CI factor 0.4641
- **CI at 20% for small T** — also memorize:
  - T=2: 1.44 (CI = 0.44)
  - T=3: 1.728 (CI = 0.728)
- **Fraction form of rate.** 12.5% = 1/8, 6.25% = 1/16, 16.67% = 1/6. CI factor (1 + 1/8) = 9/8. Two years = (9/8)² = 81/64. Clean.
- **SI shortcut per year.** SI per year = PR/100. All years equal → multiply by T at the end.
- **CI – SI 2-yr shortcut numeric.** R = 10%, P = 10000 → gap = 100. R = 20%, P = 10000 → gap = 400. Memorize a few anchor pairs.
- **"Amount doubles in $n$ years, triples in?" (CI).** Amount triples when $(1+R/100)^T = 3$. If doubles in $n$ years, $(1+R/100)^n = 2$. Triples at $T = n \log 3 / \log 2 \approx 1.585n$. For MCQ: doubles in 8 yrs → triples in ~12.7 yrs.

## SI vs CI — the comparison drill

Given $P = 10{,}000$, $R = 10\%$:

| Year | SI interest | SI amount | CI interest (yearly) | CI amount |
|------|-------------|-----------|----------------------|-----------|
| 1 | 1000 | 11000 | 1000 | 11000 |
| 2 | 1000 | 12000 | 1100 | 12100 |
| 3 | 1000 | 13000 | 1210 | 13310 |
| 4 | 1000 | 14000 | 1331 | 14641 |

Observations:

- Year-1 SI and CI interest are always equal.
- Year-2 CI interest = Year-1 × (1 + R/100) = 1000 × 1.1 = 1100.
- 2-yr gap (CI − SI) = $12100 - 12000 = 100 = P(R/100)² = 10000 \times 0.01$. ✓
- 3-yr gap = $13310 - 13000 = 310 = P(R/100)²(3 + R/100) = 100 \times 3.1$. ✓

> If you can reproduce this table from scratch in 60 seconds, SI/CI is essentially done.

## Common Traps (memorize — these are where marks leak)

1. **Compounding frequency forgotten.** Half-yearly means R→R/2 **and** T→2T. Doing only one is the classic error.
2. **"Rate per annum, compounded half-yearly"** — this is the standard phrasing. R stays the annual figure; you halve it and double T.
3. **SI vs CI in Year 1.** They are equal for T=1. Don't "compute the difference" and get 0 — that's correct, not wrong.
4. **Differential rate per year**. "5% first year, 6% second year" under SI is *not* compounded; just add $P \times 5/100 + P \times 6/100$. Under CI, multiply $(1.05)(1.06)$.
5. **"Amount" vs "Interest".** A = P + I. Misreading costs one straight mark. "CI = ₹X" means interest only, not P + I.
6. **Population = CI.** "Town grew at 5% for 3 years" → $(1.05)^3$, not $1 + 3 \times 0.05$.
7. **Depreciation direction.** $(1 - R/100)^T$, not $1 - (R/100)^T$. Common exponent error.
8. **2-yr difference formula misuse.** $P(R/100)^2$ is only for 2 years. 3 years has a different (larger) factor.
9. **Interest on interest.** CI interest in Year 2 includes interest on Year 1's interest. Sometimes questions ask "interest on interest for 2 years" — that *is* the SI-CI gap.
10. **Principal changes mid-cycle.** "P deposited, after 2 years adds ₹X, total after 5 years?" — split into two sub-periods, compound each correctly.

### Trap Pairs (drill side-by-side)

| Sounds similar | Correct reading |
|----------------|-----------------|
| "10% p.a." | Annual rate 10%; compounding = yearly unless stated |
| "10% p.a., compounded half-yearly" | Rate per period = 5%; periods per year = 2 |
| "SI for 2 years is ₹400" | SI per year = ₹200; PR/100 = 200 |
| "CI for 2 years is ₹420" | CI includes both years' interest |
| "Difference between CI and SI" | Use Formula 15 or 16 — do not compute both and subtract |
| "Amount becomes 1.21 P in 2 years" | CI factor = 1.21 → R = 10% (since 1.1² = 1.21) |
| "Interest is equal to principal" | A = 2P → SI: RT = 100; CI: (1+R/100)^T = 2 |
| "Rate of 8% for 5 years, SI" | Amount = P(1 + 0.4) = 1.4P |
| "Population grew by 8% annually for 5 years" | Final = P × (1.08)^5 — CI, not SI |
| "Interest of ₹X in 1 year" | T = 1 → SI and CI give same result |

## Problem Patterns → Attack Plan

| Pattern | Attack |
|---------|--------|
| **Direct SI** | Formula 1. Trivial with P=100 assumption. |
| **Direct CI (small T)** | Formula 6. Use memorized multipliers (1.21, 1.331, 1.44). |
| **Find P given SI or CI** | Formulas 3, 8. Back-solve. |
| **Find R given SI or CI** | For SI: R = 100·SI/(PT). For CI: take $T$-th root of (A/P), subtract 1. |
| **Find T given SI or CI** | For SI: direct. For CI: often asks "in how many years does it double/triple" — use Rule of 72 or plug options. |
| **CI half-yearly / quarterly** | Apply Formula 11–13. Rate ÷ n, time × n. |
| **CI with different rates per year** | Formula 9. Multiply multipliers. |
| **Difference between CI and SI** | Formula 15 (T=2) or 16 (T=3). Never compute both and subtract. |
| **Population growth / depreciation** | CI formula. (1 ± R/100)^T. |
| **Installments** | Build equations: each installment, discounted back to original date, sums to P. |
| **Principal added/withdrawn mid-period** | Split into sub-periods; compound each. |
| **"In how many years does SI become x% of P?"** | SI = xP/100 → RT = x → T = x/R. |
| **Sum that amounts to $A_1$ in $T_1$ years and $A_2$ in $T_2$ years (SI)** | SI per year = $(A_2 − A_1)/(T_2 − T_1)$, back out P. |

## Links to Other Chapters

- **Percentages** — SI is a single application of a rate; CI is successive. Formula 12 of Percentages IS Formula 6 here.
- **Profit & Loss** — multiplier chains are identical. Markup + discount ≈ two-year CI minus SI.
- **Ratios** — SI for different principals at same R, T → interests in ratio of principals. Same for CI.
- **Averages** — "average rate of interest over 3 schemes" = weighted average (Averages Formula 19).
- **Time & Work** (remote) — not a direct link; skip.
- **Partnership** — partnership profit = CI variant (capital × time). Analogous machinery.
- **DI** — banking DI tables often give "interest earned by 3 schemes across years"; compute using whichever mode the stem specifies.

## DI Integration Checklist

- **"Interest" unqualified** in a DI stem: read headers carefully. If ambiguous, assume SI unless the question says "compounded".
- **Table of rates across years** → CI with Formula 9.
- **Cross-comparing SI and CI on the same P, R, T** → always pick the memorized gap formula.
- **"What was the principal?"** → usually solvable in one line with Formula 3 or 8.
- **YoY interest on a fixed deposit** → CI if reinvested; SI if withdrawn each year. Stems usually specify.

## Time Budget (per-question targets)

| Sub-pattern | Target | Red flag if > |
|-------------|--------|---------------|
| Direct SI | 20 s | 35 s |
| Direct CI (T=2 or 3) | 30 s | 50 s |
| CI half-yearly (T=1) | 30 s | 50 s |
| SI-CI 2-yr difference | 15 s | 30 s |
| SI-CI 3-yr difference | 30 s | 50 s |
| Different rate per year (CI) | 40 s | 60 s |
| Doubling time (Rule of 72 / plug) | 25 s | 40 s |
| Installments (SI) | 60 s | 90 s |
| Population growth (CI) | 25 s | 40 s |
| DI cell — interest | 30 s | 50 s |

If 2-yr SI-CI gap takes more than 15 s, the bottleneck is Formula 15 recall — drill it.

## Exam Phrasing Cues (Indian banking/insurance)

- **SBI / IBPS PO**: 1 SI + 1 CI per paper, usually. SI-CI difference + compounding frequency always appear.
- **IBPS Clerk / SBI Clerk**: direct SI, simple CI for 2 years. No half-yearly typically. Speed > depth.
- **RBI Grade B / NABARD / SEBI**: embedded in DI caselets ("Scheme A offers SI at 8%, Scheme B CI at 6% compounded half-yearly"). Multi-step.
- **LIC AAO**: annuity and installment flavors more likely than other exams.
- **Keyword → attack**:
  - "simple interest" / "SI" → Formula 1
  - "compound interest" / "CI" → Formula 6
  - "amount" → P + I (never just I)
  - "per annum" (p.a.) → annual rate
  - "compounded annually" → T as-is, R as-is
  - "compounded half-yearly" → R/2, 2T
  - "compounded quarterly" → R/4, 4T
  - "payable half-yearly" → same as compounded half-yearly
  - "difference between CI and SI" → Formula 15 or 16 by T
  - "grows at X% per annum" → CI
  - "depreciates at X% per annum" → CI with (1−R/100)^T
  - "doubles" → A = 2P
  - "triples" → A = 3P
  - "installments" → construct period-by-period equation

## PYQ-Flavor Drill Problems

Solve untimed first, then re-time at 45–60 s each.

1. **(IBPS PO — direct SI)** SI on ₹8,000 at 7.5% p.a. for 4 years.
   *SI = 8000 × 7.5 × 4 / 100 = ₹2,400.*

2. **(SBI PO — direct CI, T=2)** CI on ₹10,000 at 10% p.a. for 2 years.
   *CI factor = 0.21 → CI = ₹2,100.*

3. **(IBPS Clerk — find P)** SI at 6% p.a. for 5 years is ₹900. Principal?
   *P = 100 × 900 / (6 × 5) = ₹3,000.*

4. **(RBI Grade B — SI-CI gap, 2 yr)** Difference between CI and SI on a sum at 10% p.a. for 2 years is ₹50. Find the sum.
   *Formula 15: P × (0.1)² = 50 → P = 50 / 0.01 = ₹5,000.*

5. **(NABARD — SI-CI gap, 3 yr)** At 10% p.a., the difference between CI and SI on a sum for 3 years is ₹186. Find the sum.
   *Formula 16: P × (0.1)² × (3 + 0.1) = P × 0.031 = 186 → P = ₹6,000.*

6. **(LIC AAO — half-yearly)** CI on ₹8,000 at 10% p.a. compounded half-yearly for 1 year.
   *A = 8000 × (1.05)² = 8000 × 1.1025 = 8820 → CI = ₹820.*

7. **(SBI PO — doubling)** At what rate p.a. (CI) will a sum double in 3 years? (Use Rule of 72.)
   *72/R ≈ 3 → R ≈ 24%.*

8. **(IBPS Clerk — different rate per year)** CI on ₹10,000 at 5% (yr 1), 10% (yr 2), 20% (yr 3).
   *A = 10000 × 1.05 × 1.10 × 1.20 = 10000 × 1.386 = ₹13,860 → CI = ₹3,860.*

9. **(IBPS PO — population)** Population increases 10% yearly. In 2020 it was 1,00,000. In 2023?
   *1,00,000 × (1.1)³ = 1,00,000 × 1.331 = 1,33,100.*

10. **(RBI Grade B — depreciation)** A machine worth ₹1,00,000 depreciates at 10% p.a. Value after 3 years?
    *1,00,000 × (0.9)³ = 1,00,000 × 0.729 = ₹72,900.*

11. **(SBI PO — compare SI and CI)** SI on a sum for 2 years at 8% is ₹1,600. What is CI at same R, T, P?
    *SI per year = 800 → P = 800 × 100 / 8 = ₹10,000. CI = 10000 × (1.08² − 1) = 10000 × 0.1664 = ₹1,664. (SI-CI gap = ₹64 = P × 0.08² = 10000 × 0.0064 ✓)*

12. **(IBPS PO — amount becomes)** A sum of ₹5,000 amounts to ₹6,050 in 2 years under CI. Find R.
    *(1 + R/100)² = 6050/5000 = 1.21 → 1 + R/100 = 1.1 → R = 10%.*

## Stage-7 Self-Test (if you can't do these in 45s each, revisit)

1. SI: P = ₹2,400, R = 5%, T = 3 yrs. Find SI. *(₹360)*
2. CI: P = ₹16,000, R = 12.5%, T = 2 yrs. *((1 + 1/8)² − 1 = 81/64 − 1 = 17/64 → CI = 16000 × 17/64 = ₹4,250)*
3. SI-CI gap at 20% for 2 yrs on ₹500? *(500 × 0.04 = ₹20)*
4. SI-CI gap at 10% for 3 yrs on ₹10,000? *(10000 × 0.01 × 3.1 = ₹310)*
5. Half-yearly CI at 20% p.a. for 1 yr on ₹1,000. *(1000 × 1.1² = ₹1,210; CI = ₹210)*
6. At what SI rate does money double in 8 years? *(R × 8 = 100 → R = 12.5%)*
7. At 5% CI, a sum amounts to ₹4,410 in 2 years. Principal? *(4410 / 1.05² = 4410 / 1.1025 = ₹4,000)*
8. Population 20,000; grows 10% yr 1, drops 5% yr 2. End? *(20000 × 1.1 × 0.95 = ₹20,900)* *(₹ is wrong unit here — just 20,900 people)*
9. ₹P doubles in 12 years under SI. Triples in? *(If 12R = 100 → R = 25/3. Triples when RT = 200 → T = 24 years.)*
10. CI for 3 years at 10% on ₹20,000? *(20000 × 0.331 = ₹6,620)*

If you can explain **why** each answer is right without the formula sheet, SI/CI is done.

## Revision Triggers

- If the 2-yr SI-CI gap formula ($P(R/100)^2$) isn't reflex, drill by deriving it from the CI table at 10% and 20%.
- If half-yearly/quarterly problems stall, write the mnemonic "divide the rate, multiply the time" three times and do 5 conversions.
- If population/depreciation questions feel like a separate chapter, they aren't — re-label them as CI and move on.
- If Partnership problems slow you down later, check that the bottleneck is actually CI-style capital×time compounding.
