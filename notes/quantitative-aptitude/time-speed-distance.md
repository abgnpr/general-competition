---
title: Time, Speed & Distance
parent: Quantitative Aptitude
nav_order: 16
---

# Time, Speed & Distance (+ Trains, Boats & Streams)

**Tier 1 · Priority 7.** Ratio + linear equations in motion. Trains, Boats & Streams, Circular Tracks — all sub-cases of the same formula with one extra variable (length, current, loop). Master the mental model once; get the sub-chapters free.

Status: not started

## The ONE Mental Model

Motion has three variables: **Distance $D$, Speed $S$, Time $T$** — linked by $D = S \times T$. Every TSD problem is one of three questions:

1. Two of $D, S, T$ given → find the third (trivial).
2. Two objects moving → use **relative speed** (same direction: subtract; opposite: add).
3. Medium shifts the speed (stream for boats, wind for planes) → **effective speed = own speed ± medium speed**.

> **The killer move: when $D$ is fixed, speed and time are inversely proportional.** If speeds are in ratio $3:4$, times are in ratio $4:3$ for the same distance. This single insight collapses 60% of TSD problems to pure Ratio.

Corollaries that kill most traps:

- Always convert units before setting up. km/hr ↔ m/s via ×5/18 or ×18/5. Don't leave km/hr and meters in the same equation.
- "Crossing a pole" = own length; "crossing a platform" = own length + platform length.
- Boat in still water $B$, stream $S$: downstream $= B+S$, upstream $= B-S$. $B = (D + U)/2$, $S = (D - U)/2$.
- Average speed (equal distance) = harmonic mean $2uv/(u+v)$. NOT arithmetic mean.

## The Central Formulas

$$\boxed{\;D = S \times T \qquad S = \dfrac{D}{T} \qquad T = \dfrac{D}{S}\;}$$

Everything in this chapter is a variant, a combination, or a unit-conversion wrapper around this line.

## The Full Formula Set

Core six in **bold**. Rest are one-line tools.

### A. Basic

| # | Formula | When |
|---|---------|------|
| **1** | **$D = S \times T$** | Definition |
| **2** | **km/hr ↔ m/s: $\times 5/18$ (km/hr → m/s); $\times 18/5$ (m/s → km/hr)** | Every train/real-world problem |
| **3** | **Same $D$: $S_1 : S_2 = T_2 : T_1$ (inverse)** | Ratio reflex |
| 4 | Same $T$: $S_1 : S_2 = D_1 : D_2$ (direct) | Rarer but same idea |
| 5 | Same $S$: $D_1 : D_2 = T_1 : T_2$ (direct) | Single vehicle, two legs |

### B. Average speed

| # | Formula | When |
|---|---------|------|
| **6** | **Equal distances at $u, v$: $S_{\text{avg}} = \dfrac{2uv}{u+v}$ (harmonic mean)** | "Goes at $u$, returns at $v$" |
| 7 | Three equal distances at $u, v, w$: $S_{\text{avg}} = \dfrac{3uvw}{uv+vw+wu}$ | Three-leg trip |
| 8 | Equal times at $u, v$: $S_{\text{avg}} = (u+v)/2$ (arithmetic mean) | "Drives at $u$ for 1 hr, $v$ for 1 hr" |
| 9 | General: $S_{\text{avg}} = \dfrac{\text{total distance}}{\text{total time}}$ | When neither D nor T equal |

### C. Relative speed

| # | Formula | When |
|---|---------|------|
| **10** | **Same direction: relative speed = $|S_1 - S_2|$** | Chaser / overtake |
| **11** | **Opposite direction: relative speed = $S_1 + S_2$** | Meeting / crossing head-on |
| 12 | Time to meet (opposite, starting apart by $D$): $T = D/(S_1 + S_2)$ | Two-train head-on |
| 13 | Time to catch up (same dir, starts $D$ behind): $T = D/(S_1 - S_2)$ | Classic overtake |

### D. Trains

| # | Formula | When |
|---|---------|------|
| **14** | **Train of length $L$ crossing a pole / standing man: $T = L/S$** | Only train's length matters |
| **15** | **Train of length $L$ crossing a platform of length $P$: $T = (L+P)/S$** | Both lengths |
| 16 | Two trains of lengths $L_1, L_2$ crossing each other: $T = (L_1+L_2)/\text{relative speed}$ | Use relative speed direction |
| 17 | Train crossing a walking man (same dir, speed $s_m$): $T = L/(S-s_m)$ | Subtract man's speed |
| 18 | Train crossing a walking man (opp dir, speed $s_m$): $T = L/(S+s_m)$ | Add |

### E. Boats & Streams

| # | Formula | When |
|---|---------|------|
| **19** | **Downstream speed $D_s = B + S$; Upstream $U_s = B - S$** | Every boat problem |
| 20 | Boat speed in still water $B = (D_s + U_s)/2$ | Given downstream + upstream |
| 21 | Stream speed $S = (D_s - U_s)/2$ | Same inputs |
| 22 | Time ratio downstream : upstream = $(B-S) : (B+S)$ (same distance) | Inverse of speed ratio |
| 23 | Round trip on equal distance $d$: $T = d/(B+S) + d/(B-S) = \dfrac{2dB}{B^2 - S^2}$ | Up-and-back |

### F. Circular tracks

| # | Formula | When |
|---|---------|------|
| 24 | Same direction, first meeting: $T = L / |S_1 - S_2|$ (L = track length) | Two runners catch up |
| 25 | Opposite direction, first meeting: $T = L / (S_1 + S_2)$ | Runners meet |
| 26 | Same direction, first at starting point together: $T = \text{LCM}(L/S_1, L/S_2)$ | All return to start simultaneously |
| 27 | Three runners (same dir) at start together: $T = \text{LCM}(L/S_1, L/S_2, L/S_3)$ | Extension |

### G. Misc

| # | Formula | When |
|---|---------|------|
| 28 | Late/early: speed changed from $s$ to $s'$ changes time by $\Delta t$ → $D = \dfrac{s \cdot s' \cdot \Delta t}{s' - s}$ | "Walked at 5, reached 10 min late; walked at 6, reached 5 min early" |
| 29 | Missed/extra distance: $S = D/T$ with T shifted by late/early delta | Same family |
| 30 | Plane against wind: effective speed = plane speed ∓ wind (same as boat) | Wind variant |

## Unit Conversion — do it first, always

km/hr and m/s interconversion is the #1 source of silly errors. Internalize both directions.

- **km/hr → m/s: multiply by 5/18.** (divide by 3.6)
- **m/s → km/hr: multiply by 18/5.** (multiply by 3.6)

Anchors worth memorizing:

| km/hr | m/s |
|-------|-----|
| 18 | 5 |
| 36 | 10 |
| 54 | 15 |
| 72 | 20 |
| 90 | 25 |
| 108 | 30 |

> **Rule of thumb:** if train length is in meters and speed in km/hr, convert speed to m/s before dividing. If both are km, keep km/hr.

## High-Yield Shortcuts

1. **Ratio reflex (Formula 3).** Same $D$ → speed and time are reciprocal ratios. "A takes 6 hrs, B takes 4 hrs same route" → speed ratio 4:6 = 2:3.
2. **Harmonic mean for equal-distance return (Formula 6).** $\dfrac{2uv}{u+v}$. At $u=60, v=40$ → 48. Memorize a few anchor cases.
3. **Train crossing pole** — only train length. Don't include anything else.
4. **Train crossing platform** — total = train + platform.
5. **Two trains head-on** — add speeds, add lengths, divide.
6. **Two trains overtake** — subtract speeds, add lengths, divide.
7. **Boat: $B + S$ and $B - S$** are the only speeds that exist. Everything else is ratio on top.
8. **Late/early combo (Formula 28).** Memorize as "$\text{D} = \dfrac{S_1 S_2}{S_2 - S_1} \cdot (\Delta t)$" where $\Delta t$ is total time gap in hours.
9. **Circular track "together at start" = LCM of individual lap times.** At same direction.
10. **Plane with wind** = boat with stream. Same math, different names.

## MCQ Tactics (exam-only)

- **Convert units before reading options.** A wrong-unit answer on option B will misdirect you.
- **Plug options for two-train / catch-up problems.** Algebra is slower when time and length are both in the question.
- **Ballpark average speed.** Equal-distance harmonic mean is **less than** arithmetic mean. If options straddle the arithmetic mean, pick below.
- **Ratio check for boat problems.** Downstream always faster than upstream; if answer inverts this, eliminate.
- **Time budget via relative speed.** If relative speed seems tiny (two trains nearly same speed), crossing time will be *large*. Reject absurdly small options.
- **Dimensional sanity.** Time unit must match what's asked. If speed is m/s and length m, time is in seconds — don't report 8 minutes.

## Calculation Speed Hacks

- **×5/18 via factors.** 72 km/hr → $72/18 = 4$, $\times 5 = 20$ m/s. Divide first, multiply last.
- **Length sums.** Train 200 m + platform 400 m = 600 m. Compute totals before dividing.
- **Harmonic mean shortcut.** For $u$ and $v$ with common factors, factor out. 60 and 40 → $2 \cdot 60 \cdot 40 / 100 = 4800/100 = 48$.
- **Relative speed first.** In any two-object problem, compute relative speed before touching distances.
- **Boat algebra.** Given $D_s$ and $U_s$: $B$ is the mean, $S$ is half the difference. Two additions, one division.

## Ratio-and-Time Core (the single biggest insight)

> When distance is fixed, **ratio of speeds = inverse of ratio of times**.

Drill these flips:

| Given | Deduce |
|-------|--------|
| Speeds 3:5, same distance | Times 5:3 |
| Speed doubled | Time halved |
| Speed increased 25% | Time reduced by 1/5 = 20% |
| Speed reduced 20% | Time increased by 1/4 = 25% |
| Time saved 1/3 | Speed increased by 1/2 = 50% |
| A takes 30 min, B takes 50 min (same route) | Speed ratio 5:3 |

**Shortcut chain:** Percentages base-change table (25%↔20%, 50%↔33.33%) applies directly here — speed change and time change are inverse like "% more than / % less than".

## Trains — same chapter, one extra length

Train = moving object with length $L$. The ground station is a point; a platform has length. Relative motion for two trains uses both lengths.

| Scenario | Distance to cover | Speed |
|----------|-------------------|-------|
| Crossing pole/man | $L$ | own |
| Crossing platform | $L + P$ | own |
| Crossing another train (same dir) | $L_1 + L_2$ | $|S_1 - S_2|$ |
| Crossing another train (opp dir) | $L_1 + L_2$ | $S_1 + S_2$ |
| Crossing walking man (same dir) | $L$ | $S - s_m$ |
| Crossing walking man (opp dir) | $L$ | $S + s_m$ |

## Boats & Streams — two speeds, one formula

| Quantity | Formula |
|----------|---------|
| Downstream speed | $B + S$ |
| Upstream speed | $B - S$ |
| Still-water speed | $(D_s + U_s)/2$ |
| Stream speed | $(D_s - U_s)/2$ |
| Time ratio D:U (same distance) | $(B-S):(B+S)$ |
| Round trip time, distance $d$ each way | $\dfrac{2 d B}{B^2 - S^2}$ |

**Plane with wind** maps 1-for-1: $B$ = plane speed in still air, $S$ = wind speed. Same math.

## Common Traps (memorize — these are where marks leak)

1. **Unit mismatch.** Speed in km/hr, length in m — always convert before dividing.
2. **Average speed trap.** Equal distance → harmonic mean. Equal time → arithmetic mean. Read the stem.
3. **Pole vs platform.** Pole = train length only. Platform = train + platform.
4. **Two-train direction confusion.** Same dir → subtract speeds. Opposite → add. Never subtract with trains head-on.
5. **Boat direction mix-up.** Downstream is $B+S$; upstream is $B-S$. Don't forget that "with the current" = downstream.
6. **Stream effect on still-water speed.** Only the "against" direction loses speed below $B$; on still water, speed = $B$ regardless.
7. **Late/early formula (Formula 28) sign.** If higher speed gets you early, the late-time is positive and early-time contributes negatively to $\Delta t$. Safer: write down the two times explicitly and subtract.
8. **Relative speed with same length trains.** Both lengths add in crossing, not just the longer.
9. **Circular track — same direction vs opposite.** Same → subtract; opposite → add. Classic slip.
10. **"Meeting for the first time at the starting point"** = LCM. "Meeting anywhere on track" = $L / (S_1 \pm S_2)$. Different questions.

### Trap Pairs (drill side-by-side)

| Sounds similar | Correct reading |
|----------------|-----------------|
| "Train crosses a pole in 12 s" | $D = L$ |
| "Train crosses a 200 m platform in 20 s" | $D = L + 200$ |
| "Goes at 60, returns at 40, avg speed?" | Harmonic: $48$ km/hr |
| "Goes at 60 for 1 hr, 40 for 1 hr, avg?" | Arithmetic: $50$ km/hr |
| "Trains of 100 m and 200 m, opposite, 36 and 54 km/hr, crossing time?" | $(100+200) = 300$ m; relative $= 90$ km/hr $= 25$ m/s; time $= 12$ s |
| "Same trains, same direction" | Relative $= 18$ km/hr $= 5$ m/s; time $= 60$ s |
| "Boat goes 12 km downstream in 2 hrs" | $D_s = 6$ km/hr |
| "Boat goes 12 km in still water in 2 hrs" | $B = 6$ km/hr |
| "Reaches 10 min late at 5 km/hr, 5 min early at 6 km/hr" | Use Formula 28 — total gap = 15 min = 1/4 hr |
| "Walks at 5 reaches 10 min late, walks at 6 reaches on time" | Gap = 10 min |
| "Two runners same direction on circular track" | Subtract speeds |
| "Two runners opposite direction" | Add speeds |

## Problem Patterns → Attack Plan

| Pattern | Attack |
|---------|--------|
| **Direct D = ST** | Convert units; one-line division. |
| **Ratio of speeds given same distance** | Formula 3 reflex. |
| **Average speed, equal distance** | Formula 6. |
| **Average speed, equal time** | Formula 8. |
| **General average** | Formula 9 — total D / total T. |
| **Two objects head-on** | Add speeds, divide separation. |
| **Two objects same dir (overtake)** | Subtract speeds, divide gap. |
| **Train crossing pole** | $T = L/S$. Only length. |
| **Train crossing platform** | $T = (L+P)/S$. |
| **Two trains crossing each other** | Relative speed × direction; sum lengths. |
| **Train crossing walking man** | Adjust train speed by man's speed with direction sign. |
| **Boat downstream/upstream given D and U speeds** | $B$ and $S$ via mean / half-diff. |
| **Round trip boat** | Formula 23 or split into two legs. |
| **Circular track meeting** | Formula 24 or 25 depending on direction. |
| **Circular track back to start together** | LCM of lap times. |
| **Late / early at two speeds** | Formula 28 or write out $T_1 - T_2 = \Delta t$ explicitly. |
| **Missed distance** | Distance = (speed diff) × (late/early time, appropriately signed). |

## Links to Other Chapters

- **Ratio & Proportion** — "same distance → inverse ratio of time vs speed" IS the core. Most TSD is one-step ratio.
- **Percentages** — speed change ↔ time change via base-change flip (25% up ↔ 20% down).
- **Time & Work** — inverse-proportion twin: efficiency : time :: speed : time. Same machinery.
- **Averages** — Formula 6 (harmonic mean) is Averages Formula 16. Memorize once, use in both.
- **LCM** — circular tracks (same direction, at-starting-point) need LCM of lap times.
- **Linear equations** — late/early problems set up one equation with one unknown.
- **DI** — travel tables (distance vs time vs speed across cities) occasionally appear in RBI/NABARD.

## DI Integration Checklist

- **Units in the header.** Always read table headers carefully — km/hr and m/s may coexist.
- **Time saved / time extra** → apply Formula 28 or ratio reflex.
- **Comparing two trips** → ratio of speeds and times; no arithmetic needed.
- **Multi-city travel tables** → treat each leg independently; aggregate with total D / total T.

## Time Budget (per-question targets)

| Sub-pattern | Target | Red flag if > |
|-------------|--------|---------------|
| Direct D = ST (with unit conversion) | 25 s | 40 s |
| Average speed (harmonic) | 25 s | 40 s |
| Two trains crossing | 35 s | 60 s |
| Train + platform | 30 s | 50 s |
| Boat given $D_s$ and $U_s$ | 30 s | 50 s |
| Boat round trip | 45 s | 75 s |
| Relative speed, two-object meeting | 30 s | 50 s |
| Circular track (first meeting) | 35 s | 60 s |
| Late/early problem | 45 s | 75 s |
| Ratio of speeds / times (same D) | 20 s | 35 s |

If unit conversion slows you, the bottleneck is the ×5/18 reflex — drill km/hr → m/s for every multiple of 9 until instant.

## Exam Phrasing Cues (Indian banking/insurance)

- **SBI / IBPS PO**: 1 TSD + 1 trains/boats per paper. Late/early or average-speed trap ~50% of papers.
- **IBPS Clerk / SBI Clerk**: direct D=ST, simple trains crossing pole/platform. Speed > depth.
- **RBI Grade B / NABARD / SEBI**: ratio-heavy TSD embedded in DI; circular track problems occasional.
- **LIC AAO**: table-driven — distances and speeds given; compute combined trip time.
- **Keyword → attack**:
  - "speed" + "time" + "distance" → D = ST
  - "average speed" → check equal D or equal T
  - "downstream" / "with the current" → $B + S$
  - "upstream" / "against the current" → $B - S$
  - "still water" → $B$
  - "crosses a pole/man" → $L/S$
  - "crosses a platform/bridge" → $(L+P)/S$
  - "two trains in opposite directions" → add speeds + lengths
  - "two trains in the same direction" → subtract speeds, add lengths
  - "late by / early by" → Formula 28
  - "catches up with" → $D / (S_1 - S_2)$
  - "circular track" / "loop" → Formulas 24–27
  - "km/hr" with "meters" in the same stem → convert first

## PYQ-Flavor Drill Problems

Solve untimed first, then re-time at 45–60 s each.

1. **(IBPS PO — direct)** A train covers 180 km in 3 hours. Speed in m/s?
   *60 km/hr × 5/18 = 50/3 ≈ 16.67 m/s.*

2. **(SBI PO — harmonic avg)** Car goes 80 km/hr up, 60 km/hr return. Avg speed?
   *$2 \cdot 80 \cdot 60 / 140 = 9600/140 ≈ 68.57$ km/hr.*

3. **(IBPS Clerk — train + pole)** Train 150 m long crosses a pole in 10 s. Speed?
   *$150/10 = 15$ m/s $= 54$ km/hr.*

4. **(RBI Grade B — train + platform)** Train 200 m crosses a 300 m platform in 25 s. Speed?
   *$(200 + 300)/25 = 20$ m/s $= 72$ km/hr.*

5. **(NABARD — two trains opposite)** Trains of 150 m and 100 m at 54 km/hr and 36 km/hr, opposite directions. Time to cross?
   *Relative = 90 km/hr = 25 m/s. Distance = 250 m. Time = 10 s.*

6. **(LIC AAO — catch-up)** Car A at 40 km/hr starts from X; Car B at 60 km/hr starts from X, 2 hrs later. When does B catch A?
   *A's head-start = 80 km. Relative speed = 20 km/hr. Time = 80/20 = 4 hrs after B starts.*

7. **(SBI PO — boat)** Boat goes 24 km downstream in 2 hrs, 16 km upstream in 2 hrs. $B$ and $S$?
   *$D_s = 12, U_s = 8. B = 10, S = 2$.*

8. **(IBPS PO — boat round trip)** Boat speed 10 km/hr, stream 2 km/hr. Round trip of 48 km each way. Total time?
   *Downstream 12 → 4 hrs; upstream 8 → 6 hrs. Total 10 hrs. (Cross-check Formula 23: $2 \cdot 48 \cdot 10 / (100 - 4) = 960/96 = 10$.)*

9. **(IBPS Clerk — late/early)** At 5 km/hr he reaches 10 min late; at 6 km/hr, 5 min early. Distance?
   *Formula 28: $\Delta t = 15$ min $= 1/4$ hr. $D = (5 \cdot 6 \cdot 1/4) / (6-5) = 30/4 = 7.5$ km.*

10. **(SBI PO — circular, same dir)** Track 600 m. A at 6 m/s, B at 4 m/s, same direction. First meeting after start?
    *Relative 2 m/s. Time = 600/2 = 300 s = 5 min.*

11. **(RBI Grade B — circular, opp dir)** Same track, runners in opposite directions. First meeting?
    *Relative 10 m/s. Time = 60 s = 1 min.*

12. **(LIC AAO — ratio reflex)** A and B cover the same distance; A's speed is 25% more than B's. A takes 4 hours. B's time?
    *Speed ratio 5:4 → time ratio 4:5. B = 5 hrs.*

## Stage-7 Self-Test (if you can't do these in 45s each, revisit)

1. 36 km/hr in m/s? *(10)*
2. 25 m/s in km/hr? *(90)*
3. Avg speed: 60 up, 40 down, equal distance. *(48 km/hr)*
4. Train 120 m crosses pole in 8 s. Speed in km/hr? *($15$ m/s $= 54$)*
5. Train 200 m crosses 300 m platform in 20 s. Speed? *($500/20 = 25$ m/s $= 90$ km/hr)*
6. $B = 8, S = 3$. Downstream? Upstream? *(11, 5)*
7. Boat 18 km downstream in 2 hrs, 12 km upstream in 2 hrs. $B, S$? *($D_s = 9, U_s = 6$ → $B = 7.5, S = 1.5$)*
8. Speed ratio 3:4, time ratio (same D)? *(4:3)*
9. Two trains 100 m each, 54 and 36 km/hr, same direction, crossing time? *(rel = 18 km/hr = 5 m/s; $200/5 = 40$ s)*
10. Track 400 m, A at 5 m/s, B at 3 m/s, opp direction, first meeting? *($400/8 = 50$ s)*

If you can explain **why** each answer is right without the formula sheet, TSD is done.

## Revision Triggers

- If unit conversion takes more than 3 seconds, drill ×5/18 until reflex. Memorize the 18 / 36 / 54 / 72 / 90 / 108 km/hr anchors.
- If harmonic mean (Formula 6) feels slow, derive once from $D/T$: two trips of distance $d$ at $u$ and $v$ → total 2d, total time $d/u + d/v$ → avg = $2uv/(u+v)$.
- If you keep missing "pole vs platform", write "only train length" vs "train + platform" in the margin for the first 10 problems.
- If boat problems invert downstream/upstream, re-state: "current helps = faster, current fights = slower".
- If circular tracks confuse same/opposite, revisit Formulas 24–25 — then verify by picking ratios 3:2 and computing both.
- Whenever a Time & Work drill feels slow, check whether the real bottleneck is the inverse-proportion reflex — same one used here.
