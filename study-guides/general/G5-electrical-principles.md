# G5 — Electrical Principles

**3 of your 35 exam questions · 3 groups (G5A–G5C) · 40 questions in the pool**

The math subelement. The good news is that it is a small, fixed set of formulas and the numbers in
the pool never change — the exam will hand you the same arithmetic printed below. Work each
calculation by hand once and you will recognize every one of them on exam day.

## Table of Contents

- [G5A — Reactance; inductance; capacitance; impedance; impedance transformation; resonance](#g5a--reactance-inductance-capacitance-impedance-impedance-transformation-resonance)
  - [All 12 pool questions for G5A](#all-12-pool-questions-for-g5a)
- [G5B — The decibel; dividers; power calculations; RMS values; PEP calculations](#g5b--the-decibel-dividers-power-calculations-rms-values-pep-calculations)
  - [All 14 pool questions for G5B](#all-14-pool-questions-for-g5b)
- [G5C — Resistors, capacitors, and inductors in series and parallel; transformers](#g5c--resistors-capacitors-and-inductors-in-series-and-parallel-transformers)
  - [All 14 pool questions for G5C](#all-14-pool-questions-for-g5c)
- [Bottom line for G5](#bottom-line-for-g5)

---

## G5A — Reactance; inductance; capacitance; impedance; impedance transformation; resonance

*One exam question comes from this group. 12 questions in the pool.*

**Definitions.** *Reactance* is opposition to **alternating** current caused by **capacitance or
inductance** — for both components, the answer is reactance, not conductance or reluctance.
*Impedance* is the ratio of **voltage to current**. *Admittance* is the **inverse of impedance**.
Reactance is measured in **ohms** and carries the letter **X**.

**How reactance varies with frequency** — do not flip these:

| Component | As frequency rises |
|---|---|
| **Inductor** | Reactance **increases** |
| **Capacitor** | Reactance **decreases** |

Sanity check from physics: a capacitor blocks DC (infinite reactance at 0 Hz) and passes RF; an
inductor passes DC and chokes RF. That picture gets you both answers every time. Note also that
**amplitude is irrelevant** — several distractors offer "as the amplitude increases."

**Resonance** is where **inductive and capacitive reactance cancel**. In a **series** LC circuit at
resonance, impedance is **very low**.

**Impedance matching** at RF can be done with a transformer, a Pi-network, or a length of
transmission line: **all these choices are correct**.

#### All 12 pool questions for G5A

**G5A01**

What happens when inductive and capacitive reactance are equal in a series LC circuit?

- A. Resonance causes impedance to be very high
- B. Impedance is equal to the geometric mean of the inductance and capacitance
- C. Resonance causes impedance to be very low
- D. Impedance is equal to the arithmetic mean of the inductance and capacitance
-
- Answer: C

**G5A02**

What is reactance?

- A. Opposition to the flow of direct current caused by resistance
- B. Opposition to the flow of alternating current caused by capacitance or inductance
- C. Reinforcement of the flow of direct current caused by resistance
- D. Reinforcement of the flow of alternating current caused by capacitance or inductance
-
- Answer: B

**G5A03**

Which of the following is opposition to the flow of alternating current in an inductor?

- A. Conductance
- B. Reluctance
- C. Admittance
- D. Reactance
-
- Answer: D

**G5A04**

Which of the following is opposition to the flow of alternating current in a capacitor?

- A. Conductance
- B. Reluctance
- C. Reactance
- D. Admittance
-
- Answer: C

**G5A05**

How does an inductor react to AC?

- A. As the frequency of the applied AC increases, the reactance decreases
- B. As the amplitude of the applied AC increases, the reactance increases
- C. As the amplitude of the applied AC increases, the reactance decreases
- D. As the frequency of the applied AC increases, the reactance increases
-
- Answer: D

**G5A06**

How does a capacitor react to AC?

- A. As the frequency of the applied AC increases, the reactance decreases
- B. As the frequency of the applied AC increases, the reactance increases
- C. As the amplitude of the applied AC increases, the reactance increases
- D. As the amplitude of the applied AC increases, the reactance decreases
-
- Answer: A

**G5A07**

What is the term for the inverse of impedance?

- A. Conductance
- B. Susceptance
- C. Reluctance
- D. Admittance
-
- Answer: D

**G5A08**

What is impedance?

- A. The ratio of current to voltage
- B. The product of current and voltage
- C. The ratio of voltage to current
- D. The product of current and reactance
-
- Answer: C

**G5A09**

What unit is used to measure reactance?

- A. Farad
- B. Ohm
- C. Ampere
- D. Siemens
-
- Answer: B

**G5A10**

Which of the following devices can be used for impedance matching at radio frequencies?

- A. A transformer
- B. A Pi-network
- C. A length of transmission line
- D. All these choices are correct
-
- Answer: D

**G5A11**

What letter is used to represent reactance?

- A. Z
- B. X
- C. B
- D. Y
-
- Answer: B

**G5A12**

What occurs in an LC circuit at resonance?

- A. Current and voltage are equal
- B. Resistance is cancelled
- C. The circuit radiates all its energy in the form of radio waves
- D. Inductive reactance and capacitive reactance cancel
-
- Answer: D

---

## G5B — The decibel; dividers; power calculations; RMS values; PEP calculations

*One exam question comes from this group. 14 questions in the pool.*

**Decibels.** **3 dB is a factor of 2** in power. A **1 dB loss is 20.6%**. (For the S-meter
questions in G4D you also want 6 dB = 4x and 20 dB = 100x.)

**Power.** Three forms of one law — use whichever matches the two values you are given:

```
P = V x I          P = V^2 / R          P = I^2 x R
```

400 V across 800 ohms gives 160,000/800 = **200 W**. A 12 V bulb drawing 0.2 A gives **2.4 W**.
7.0 mA through 1,250 ohms gives 0.000049 x 1250 = **61 milliwatts** — watch the units there.

**RMS.** `V_RMS = V_peak x 0.707` and `V_peak = V_RMS x 1.414`. RMS matters because it is the AC
value that **produces the same power in a resistor as the same DC voltage**. So 120 V RMS is 169.7 V
peak and **339.4 V peak-to-peak**; 17 V peak is **12 V RMS**.

**PEP from peak-to-peak volts — always the same three steps:**

```
1. Vpp / 2        = Vpeak
2. Vpeak x 0.707  = Vrms
3. Vrms^2 / R     = PEP
```

200 Vpp into 50 ohms gives 100 peak, 70.7 RMS, **100 W**. 500 Vpp into 50 ohms gives **625 W**.
Backwards, `V = sqrt(P x R)`, so 1200 W into 50 ohms is **245 V RMS**.

**For an unmodulated carrier, PEP equals average power — the ratio is 1.00.** A constant-amplitude
sine wave has nothing to peak above, so 1060 W average is **1060 W PEP**.

#### All 14 pool questions for G5B

**G5B01**

What dB change represents a factor of two increase or decrease in power?

- A. Approximately 2 dB
- B. Approximately 3 dB
- C. Approximately 6 dB
- D. Approximately 9 dB
-
- Answer: B

**G5B02**

How does the total current relate to the individual currents in a circuit of parallel resistors?

- A. It equals the average of the branch currents
- B. It decreases as more parallel branches are added to the circuit
- C. It equals the sum of the currents through each branch
- D. It is the sum of the reciprocal of each individual voltage drop
-
- Answer: C

**G5B03**

How many watts of electrical power are consumed if 400 VDC is supplied to an 800-ohm load?

- A. 0.5 watts
- B. 200 watts
- C. 400 watts
- D. 3200 watts
-
- Answer: B

**G5B04**

How many watts of electrical power are consumed by a 12 VDC light bulb that draws 0.2 amperes?

- A. 2.4 watts
- B. 24 watts
- C. 6 watts
- D. 60 watts
-
- Answer: A

**G5B05**

How many watts are consumed when a current of 7.0 milliamperes flows through a 1,250-ohm resistance?

- A. Approximately 61 milliwatts
- B. Approximately 61 watts
- C. Approximately 11 milliwatts
- D. Approximately 11 watts
-
- Answer: A

**G5B06**

What is the PEP produced by 200 volts peak-to-peak across a 50-ohm dummy load?

- A. 1.4 watts
- B. 100 watts
- C. 353.5 watts
- D. 400 watts
-
- Answer: B

**G5B07**

What value of an AC signal produces the same power dissipation in a resistor as a DC voltage of the same value?

- A. The peak-to-peak value
- B. The peak value
- C. The RMS value
- D. The reciprocal of the RMS value
-
- Answer: C

**G5B08**

What is the peak-to-peak voltage of a sine wave with an RMS voltage of 120 volts?

- A. 84.8 volts
- B. 169.7 volts
- C. 240.0 volts
- D. 339.4 volts
-
- Answer: D

**G5B09**

What is the RMS voltage of a sine wave with a value of 17 volts peak?

- A. 8.5 volts
- B. 12 volts
- C. 24 volts
- D. 34 volts
-
- Answer: B

**G5B10**

What percentage of power loss is equivalent to a loss of 1 dB?

- A. 10.9 percent
- B. 12.2 percent
- C. 20.6 percent
- D. 25.9 percent
-
- Answer: C

**G5B11**

What is the ratio of PEP to average power for an unmodulated carrier?

- A. 0.707
- B. 1.00
- C. 1.414
- D. 2.00
-
- Answer: B

**G5B12**

What is the RMS voltage across a 50-ohm dummy load dissipating 1200 watts?

- A. 173 volts
- B. 245 volts
- C. 346 volts
- D. 692 volts
-
- Answer: B

**G5B13**

What is the output PEP of an unmodulated carrier if the average power is 1060 watts?

- A. 530 watts
- B. 1060 watts
- C. 1500 watts
- D. 2120 watts
-
- Answer: B

**G5B14**

What is the output PEP of 500 volts peak-to-peak across a 50-ohm load?

- A. 8.75 watts
- B. 625 watts
- C. 2500 watts
- D. 5000 watts
-
- Answer: B

---

## G5C — Resistors, capacitors, and inductors in series and parallel; transformers

*One exam question comes from this group. 14 questions in the pool.*

**The combination rules, and the one exception:**

| | Series | Parallel |
|---|---|---|
| Resistors | Add | Reciprocal |
| Inductors | Add | Reciprocal |
| **Capacitors** | **Reciprocal** | **Add** |

**Capacitors are backwards from everything else.** That is the single most important fact in this
group. Reciprocal formula: `1/Total = 1/A + 1/B + ...`; for two components `Total = (A x B)/(A + B)`;
for *n* identical components, just divide by *n*.

**Sanity check that catches most errors:** a parallel resistance is always smaller than the smallest
resistor, and a series capacitance is always smaller than the smallest capacitor. If your answer
came out bigger, you used the wrong rule.

To **increase capacitance add a capacitor in parallel**; to **increase inductance add an inductor in
series**.

**Transformers.** Voltage appears on the secondary through **mutual inductance**, and voltage follows
the turns ratio directly: 500:1500 turns with 120 VAC in gives **360 V**. Feed a 4:1 step-down
transformer backwards and the input is **multiplied by 4**.

**Impedance ratio is the turns ratio squared**, so go the other way with a square root: matching 600
ohms to 50 ohms needs `sqrt(12)` = **3.5 to 1**. Finally, the **primary of a step-up transformer uses
thicker wire because it carries higher current** — power in equals power out, so the low-voltage side
is always the high-current side.

#### All 14 pool questions for G5C

**G5C01**

What causes a voltage to appear across the secondary winding of a transformer when an AC voltage source is connected across its primary winding?

- A. Capacitive coupling
- B. Displacement current coupling
- C. Mutual inductance
- D. Mutual capacitance
-
- Answer: C

**G5C02**

What is the output voltage if an input signal is applied to the secondary winding of a 4:1 voltage step-down transformer instead of the primary winding?

- A. The input voltage is multiplied by 4
- B. The input voltage is divided by 4
- C. Additional resistance must be added in series with the primary to prevent overload
- D. Additional resistance must be added in parallel with the secondary to prevent overload
-
- Answer: A

**G5C03**

What is the total resistance of a 10-, a 20-, and a 50-ohm resistor connected in parallel?

- A. 5.9 ohms
- B. 0.17 ohms
- C. 17 ohms
- D. 80 ohms
-
- Answer: A

**G5C04**

What is the approximate total resistance of a 100- and a 200-ohm resistor in parallel?

- A. 300 ohms
- B. 150 ohms
- C. 75 ohms
- D. 67 ohms
-
- Answer: D

**G5C05**

Why is the primary winding wire of a voltage step-up transformer usually a larger size than that of the secondary winding?

- A. To improve the coupling between the primary and secondary
- B. To accommodate the higher current of the primary
- C. To prevent parasitic oscillations due to resistive losses in the primary
- D. To ensure that the volume of the primary winding is equal to the volume of the secondary winding
-
- Answer: B

**G5C06**

What is the voltage output of a transformer with a 500-turn primary and a 1500-turn secondary when 120 VAC is applied to the primary?

- A. 360 volts
- B. 120 volts
- C. 40 volts
- D. 25.5 volts
-
- Answer: A

**G5C07**

What transformer turns ratio matches an antenna’s 600-ohm feed point impedance to a 50-ohm coaxial cable?

- A. 3.5 to 1
- B. 12 to 1
- C. 24 to 1
- D. 144 to 1
-
- Answer: A

**G5C08**

What is the equivalent capacitance of two 5.0-nanofarad capacitors and one 750-picofarad capacitor connected in parallel?

- A. 576.9 nanofarads
- B. 1,733 picofarads
- C. 3,583 picofarads
- D. 10.750 nanofarads
-
- Answer: D

**G5C09**

What is the capacitance of three 100-microfarad capacitors connected in series?

- A. 0.33 microfarads
- B. 3.0 microfarads
- C. 33.3 microfarads
- D. 300 microfarads
-
- Answer: C

**G5C10**

What is the inductance of three 10-millihenry inductors connected in parallel?

- A. 0.30 henries
- B. 3.3 henries
- C. 3.3 millihenries
- D. 30 millihenries
-
- Answer: C

**G5C11**

What is the inductance of a circuit with a 20-millihenry inductor connected in series with a 50-millihenry inductor?

- A. 7 millihenries
- B. 14.3 millihenries
- C. 70 millihenries
- D. 1,000 millihenries
-
- Answer: C

**G5C12**

What is the capacitance of a 20-microfarad capacitor connected in series with a 50-microfarad capacitor?

- A. 0.07 microfarads
- B. 14.3 microfarads
- C. 70 microfarads
- D. 1,000 microfarads
-
- Answer: B

**G5C13**

Which of the following components should be added to a capacitor to increase the capacitance?

- A. An inductor in series
- B. An inductor in parallel
- C. A capacitor in parallel
- D. A capacitor in series
-
- Answer: C

**G5C14**

Which of the following components should be added to an inductor to increase the inductance?

- A. A capacitor in series
- B. A capacitor in parallel
- C. An inductor in parallel
- D. An inductor in series
-
- Answer: D

---

## Bottom line for G5

**Inductive reactance rises with frequency, capacitive falls.** At resonance they **cancel**; series
LC goes to **very low** impedance. **3 dB is 2x power**; **1 dB loss is 20.6%**. `P = V^2/R` and
`P = I^2 R`. **RMS = peak x 0.707.** For PEP: halve the peak-to-peak, multiply by 0.707, square, and
divide by R. **PEP equals average power for an unmodulated carrier.** **Capacitors combine backwards**
from resistors and inductors. Transformer **voltage follows turns; impedance follows turns squared**.
