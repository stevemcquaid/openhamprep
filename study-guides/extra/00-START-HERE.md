# Amateur Extra Class (Element 4) Study Guides

Ten guides, one per subelement, covering the **NCVEC 2024–2028 Amateur Extra Class question pool** —
current through the **4th errata of February 4, 2026**.

Every one of the 599 active pool questions appears in these guides, printed in full with all four
choices, the correct answer marked, and the Part 97 citation where the pool provides one. Each
group's questions sit directly beneath the concept notes that explain them.

**The exam:** 50 questions, one drawn at random from each of the 50 groups. **You need 37 correct to
pass (74%).** You can miss 13.

---

## The guides

| # | Guide | Exam Qs | Groups | Pool Qs |
|---|---|---|---|---|
| E1 | [Commission's Rules](E1-commissions-rules.md) | **6** | 6 | 68 |
| E2 | [Operating Procedures](E2-operating-procedures.md) | 5 | 5 | 60 |
| E3 | [Radio Wave Propagation](E3-radio-wave-propagation.md) | 3 | 3 | 39 |
| E4 | [Amateur Practices](E4-amateur-practices.md) | 5 | 5 | 63 |
| E5 | [Electrical Principles](E5-electrical-principles.md) | 4 | 4 | 49 |
| E6 | [Circuit Components](E6-circuit-components.md) | **6** | 6 | 68 |
| E7 | [Practical Circuits](E7-practical-circuits.md) | **8** | 8 | 99 |
| E8 | [Signals and Emissions](E8-signals-and-emissions.md) | 4 | 4 | 48 |
| E9 | [Antennas and Transmission Lines](E9-antennas-and-transmission-lines.md) | **8** | 8 | 93 |
| E0 | [Safety](E0-safety.md) | 1 | 1 | 12 |
| | **Total** | **50** | **50** | **599** |

Because the exam draws exactly one question from each group, **every group is worth exactly one
question** — E9E counts the same as E7D. That makes group size a useful guide to effort: E7D and
E8C each have 15 questions competing for one exam slot, while E9E has only 10.

---

## Where to spend your effort

**E7 and E9 are 16 of your 50 questions** — 32% of the exam — the two largest subelements by a wide
margin. Add **E1** and **E6** (6 questions apiece) and those four subelements cover 28 of the 50 you
need, against a passing bar of 37. That's the core to prioritize.

A reasonable order:

1. **E1** — frontload the rules tables while you're fresh; the sideband-edge arithmetic in E1A takes
   real thought, so don't leave it for a tired pass
2. **E7** — the largest subelement; digital logic, amplifier classes, filters, regulators, mixers,
   op-amp gain, and oscillators, one group at a time
3. **E9** — antenna gain math, matching systems, transmission-line stub behavior, and the Smith
   chart; builds naturally on E7's circuit vocabulary
4. **E6** — component trivia with almost no math; fast once you've built the vocabulary in E7
5. **E4** — test equipment and receiver performance; the most reasoning-heavy subelement, worth
   understanding rather than memorizing
6. **E2** — satellites, TV modes, contest/DX practice, and the digital-mode alphabet soup; no math,
   mostly operational knowledge
7. **E5** — resonance, time constants, and phasor math; do the arithmetic by hand at least once
8. **E8** — modulation index and deviation ratio calculations plus digital-mode definitions
9. **E3** — builds directly on General's G3 ionosphere model; three questions, but a wide spread of
   topics
10. **E0** — one group, one question; save for last and review right before the exam

---

## Things to actually memorize

Everything else you can reason out. These you can't:

**Numbers**
- 2200 m caps at 1 W EIRP; 630 m caps at 5 W EIRP (not PEP) except parts of Alaska
- 60-meter data and USB voice bandwidth: 2.8 kHz
- Remote control link failure: transmissions must stop within 3 minutes
- Highest modulation index for angle modulation below 29.0 MHz: 1.0
- Maximum spurious emission below 30 MHz: −43 dB relative to the fundamental
- RF exposure limits are most restrictive from 30–300 MHz
- A co-located transmitter shares over-exposure responsibility at just 5% of its own MPE limit
- Handheld transceivers sold before May 3, 2021 are grandfathered from RF exposure evaluation
- Protect an FCC monitoring facility from harmful interference within 1 mile
- EME: max separation ~12,000 miles while the Moon is mutually visible; meteor scatter works
  28–148 MHz; tropospheric ducts run 100–300 miles over water
- Transequatorial propagation: 2,000–3,000 mile paths, max range 5,000 miles
- Receiver noise floor theoretical minimum: −174 dBm in a 1 Hz bandwidth at room temperature
- A 20× bandwidth increase costs about 13 dB more noise
- PEP-to-average power ratio for unprocessed SSB: about 2.5 to 1
- An 8-bit A/D converter encodes 256 levels; resolving 1 V to 1 mV steps needs 10 bits
- dBd = dBi − 2.15
- 0 dBm = 1 mW; −100 dBm = 0.1 picowatt
- Doubling frequency on a parabolic dish adds 6 dB of gain
- One RC time constant: 63.2% charge / 36.8% discharge
- Silicon NPN base-to-emitter voltage when biased on: about 0.6–0.7 V
- CEPT operation requires a copy of FCC Public Notice DA 16-1048
- Three VEs must certify a passing exam for a license grant
- 13-WPM CW is about 52 Hz wide; FT8 is about 50 Hz wide; a 4,800 Hz shift 9,600-baud ASCII FM
  signal is 15.36 kHz wide
- Acceptable maximum IMD for an idling PSK signal: −30 dB

**Formulas**
- `f = 1 / (2π√(LC))`; half-power bandwidth `BW = f / Q`
- Parallel resonant `Q = R / X`; series resonant `Q = X / R` (reciprocals of each other)
- `τ = R × C` — combine parallel capacitors by adding, parallel resistors by the reciprocal rule,
  before plugging in
- Phase angle in a series RLC circuit: `angle = arctan((XL − XC) / R)`
- FM modulation index = frequency deviation ÷ modulating signal frequency
- Deviation ratio = maximum carrier deviation ÷ highest modulating frequency the system handles
- Op-amp inverting-stage gain magnitude = RF ÷ R1
- ERP/EIRP: start with transmitter power, subtract every dB of loss, add antenna gain (dBd for ERP,
  dBi for EIRP), then convert the net dB back to watts
- Q-section (quarter-wave transformer) impedance is the geometric mean of the two impedances it
  joins: `Z = √(Z1 × Z2)`

**Conventions with no logic behind them**
- Rectangular notation: `+j` is inductive reactance, `−j` is capacitive — the sign alone tells you
  which
- Pure inductor: voltage leads current by 90°. Pure capacitor: current leads voltage by 90°
- Colpitts feedback comes through a capacitive divider; Pierce feedback comes through a quartz
  crystal
- A shorted quarter-wave stub presents very high impedance; a shorted half-wave stub presents very
  low impedance (the same as the short itself); the pattern flips at every quarter wave
- A low-pass Pi-network is capacitor–inductor–capacitor (C-L-C); a high-pass T-network is the mirror
  image, series capacitors with a shunt inductor
- A NAND gate outputs 0 only if every input is 1; a two-input XNOR gate outputs 0 if exactly one
  input is 1
- North of Line A in the contiguous 48 states, amateurs may not transmit 420–430 MHz

---

## Traps that catch people

- **Series resonance gives minimum impedance ≈ R; parallel resonance gives maximum impedance ≈ R** —
  same "approximately equal to circuit resistance" answer, opposite magnitude context. (E5A03/E5A04)
- **A shorted quarter-wave stub looks like an open circuit (very high impedance); a shorted
  half-wave stub looks like a short again (very low impedance).** (E9F04/E9F09)
- **Ferrite's higher permeability means fewer turns for a given inductance; powdered iron has the
  better temperature stability** — easy to swap these two facts by mistake. (E6D05/E6D08)
- **Modulation index divides by the actual modulating frequency; deviation ratio divides by the
  highest modulating frequency the system is designed for** — same formula shape, different
  denominator. (E8B01/E8B09)
- **dBd is not the same number as dBi** — subtract 2.15 dB to convert from an isotropic reference to
  a dipole reference. (E9A12)
- **MPE limits are always about *exposure*, never "emission,"** and a neighbor's property always
  falls under the tighter *uncontrolled* limit, not the controlled one that applies to you. (E0A02)
- **Third-order intercept is a theoretical extrapolation, not a real operating condition** — no
  actual signal reaches that amplitude; it's a way of expressing how much IMD headroom a receiver
  has. (E4D10)
- **EME's maximum separation is set by "Moon visible by both stations" (~12,000 miles), not by
  perigee or apogee — but path *loss* (a separate question) really is least at perigee.** (E3A01/E3A03)
- **The business-message rule has no dollar threshold** — it's allowed only when neither the amateur
  nor their employer has any pecuniary interest in the communication at all. (E1F07)
- **In rectangular notation, the minus sign alone makes an impedance capacitive** — `50 − j25` is
  capacitive reactance, not inductive. (E5C01/E5C06)

---

## Sources and currency

Questions are reproduced verbatim from the NCVEC 2024–2028 Element 4 pool, which the NCVEC Question
Pool Committee **released into the public domain**. Answer keys were spot-checked against the
official NCVEC release document.

**Errata applied.** Four questions have been withdrawn since the original December 7, 2023 release
and are correctly absent here: **E2A13, E4D05, E6D07, E9E10**. Question numbering in the pool is
therefore not perfectly contiguous around these; that's expected, not an error.

The current pool is effective **July 1, 2024 through June 30, 2028**, current through the **4th
errata (issued February 4, 2026)**. After expiration, check NCVEC for the replacement.

**A study guide is not a substitute for practice tests.** These explain the material so the answers
stick, and having the full pool in front of you means you can self-test as you go. But running full
randomized 50-question mock exams is what tells you whether you're ready. Aim for consistent scores
in the mid-80s before booking a session — that leaves margin for exam-day nerves.
