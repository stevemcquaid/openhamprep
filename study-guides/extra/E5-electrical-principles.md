# E5 — Electrical Principles

**4 of your 50 exam questions · 4 groups (E5A–E5D) · 49 questions in the pool**

The math-and-abstraction subelement of the Extra pool: resonance and Q, RL/RC time constants, phase
angle in reactive circuits, rectangular/polar coordinate systems for impedance, and how real
components misbehave at RF. It builds directly on General's G5 — same reactance and resonance
vocabulary — but goes a level deeper: quantitative Q and bandwidth calculations, phase-angle
arithmetic with arctangent, and formal rectangular/polar notation for impedance.

As with G5, the arithmetic is fixed — the same handful of RLC and phase-angle problems recur with the
same numbers every renewal cycle — so working each calculation once by hand is worth more than
memorizing the answer letter. E5C's three figure-based questions (E5C10–E5C12) reference a pool
diagram this guide cannot reproduce; know the underlying R/X-plane geometry and you can still answer
them by calculation.

---

## E5A — Resonance and Q: characteristics of resonant circuits; series and parallel resonance; definitions and effects of Q; half-power bandwidth

*One exam question comes from this group. 13 questions in the pool.*

**Resonance is where XL and XC cancel,** leaving the circuit's opposition determined by resistance
alone — but *only* at the input/overall level. Inside the loop it's a different story: at series
resonance, current is **maximum** and impedance is **minimum**, approximately equal to the circuit
resistance (E5A03). At parallel resonance, input current is **minimum** and impedance is
**maximum** — also expressed in the pool as "approximately equal to circuit resistance," because at
parallel resonance the tank looks like the resistance across it, which is large (E5A04). Read the
question carefully: series and parallel resonance give opposite-sounding but individually-correct
"equal to circuit resistance" answers.

**Voltage and current multiply inside a resonant circuit even though they cancel at the terminals.** A
high-Q series RLC circuit at resonance can show reactive voltages **higher than the source voltage**
(E5A01) — that's the mechanism, and increasing Q makes it worse: internal voltages increase with Q
(E5A13). The parallel-resonant mirror image is circulating tank current: at resonance the current
circulating between L and C is at a **maximum** (E5A06), even though the current the source has to
supply at the input is at a **minimum** (E5A07) — the tank is recycling energy internally rather than
drawing it from the line.

**At resonance, voltage and current are in phase** (E5A08) — that's the definition; the reactive
terms have cancelled, so the circuit looks purely resistive.

**Q formulas run opposite for series and parallel circuits.** For a parallel resonant circuit,
Q = **resistance divided by reactance** (E5A09); the series form is the reciprocal, Q = reactance
divided by resistance. Higher Q means a **narrower matching bandwidth** (E5A05) — Q and bandwidth
trade off directly.

**Resonant frequency:** `f = 1 / (2π√(LC))`. With R = 22 Ω, L = 50 µH, C = 40 pF, f ≈ **3.56 MHz**
(E5A02); with R = 33 Ω, L = 50 µH, C = 10 pF, f ≈ **7.12 MHz** (E5A10) — note R never enters the
resonant-frequency formula; it only matters for computing Q afterward.

**Half-power bandwidth:** `BW = f / Q`. At 7.1 MHz with Q = 150, BW ≈ **47.3 kHz** (E5A11); at
3.7 MHz with Q = 118, BW ≈ **31.4 kHz** (E5A12).

#### All 13 pool questions for E5A

**E5A01**

What can cause the voltage across reactances in a series RLC circuit to be higher than the voltage applied to the entire circuit?

- **A. Resonance**  ←
- B. Capacitance
- C. Low quality factor (Q)
- D. Resistance

**E5A02**

What is the resonant frequency of an RLC circuit if R is 22 ohms, L is 50 microhenries, and C is 40 picofarads?

- A. 44.72 MHz
- B. 22.36 MHz
- **C. 3.56 MHz**  ←
- D. 1.78 MHz

**E5A03**

What is the magnitude of the impedance of a series RLC circuit at resonance?

- A. High, compared to the circuit resistance
- B. Approximately equal to capacitive reactance
- C. Approximately equal to inductive reactance
- **D. Approximately equal to circuit resistance**  ←

**E5A04**

What is the magnitude of the impedance of a parallel RLC circuit at resonance?

- **A. Approximately equal to circuit resistance**  ←
- B. Approximately equal to inductive reactance
- C. Low compared to the circuit resistance
- D. High compared to the circuit resistance

**E5A05**

What is the result of increasing the Q of an impedance-matching circuit?

- **A. Matching bandwidth is decreased**  ←
- B. Matching bandwidth is increased
- C. Losses increase
- D. Harmonics increase

**E5A06**

What is the magnitude of the circulating current within the components of a parallel LC circuit at resonance?

- A. It is at a minimum
- **B. It is at a maximum**  ←
- C. It equals 1 divided by the quantity 2 times pi, times the square root of (inductance L multiplied by capacitance C)
- D. It equals 2 times pi, times the square root of (inductance L multiplied by capacitance C)

**E5A07**

What is the magnitude of the current at the input of a parallel RLC circuit at resonance?

- **A. Minimum**  ←
- B. Maximum
- C. R/L
- D. L/R

**E5A08**

What is the phase relationship between the current through and the voltage across a series resonant circuit at resonance?

- A. The voltage leads the current by 90 degrees
- B. The current leads the voltage by 90 degrees
- **C. The voltage and current are in phase**  ←
- D. The voltage and current are 180 degrees out of phase

**E5A09**

How is the Q of an RLC parallel resonant circuit calculated?

- A. Reactance of either the inductance or capacitance divided by the resistance
- B. Reactance of either the inductance or capacitance multiplied by the resistance
- **C. Resistance divided by the reactance of either the inductance or capacitance**  ←
- D. Reactance of the inductance multiplied by the reactance of the capacitance

**E5A10**

What is the resonant frequency of an RLC circuit if R is 33 ohms, L is 50 microhenries, and C is 10 picofarads?

- **A. 7.12 MHz**  ←
- B. 23.5 kHz
- C. 7.12 kHz
- D. 23.5 MHz

**E5A11**

What is the half-power bandwidth of a resonant circuit that has a resonant frequency of 7.1 MHz and a Q of 150?

- A. 157.8 Hz
- B. 315.6 Hz
- **C. 47.3 kHz**  ←
- D. 23.67 kHz

**E5A12**

What is the half-power bandwidth of a resonant circuit that has a resonant frequency of 3.7 MHz and a Q of 118?

- A. 436.6 kHz
- B. 218.3 kHz
- **C. 31.4 kHz**  ←
- D. 15.7 kHz

**E5A13**

What is an effect of increasing Q in a series resonant circuit?

- A. Fewer components are needed for the same performance
- B. Parasitic effects are minimized
- **C. Internal voltages increase**  ←
- D. Phase shift can become uncontrolled

---

## E5B — Time constants and phase relationships: RL and RC time constants; phase angle in reactive circuits and components; admittance and susceptance

*One exam question comes from this group. 12 questions in the pool.*

**One time constant** is how long an RC circuit takes to charge to **63.2%** of the applied voltage,
or discharge to **36.8%** of its initial voltage (E5B01) — those two numbers (63.2 and its complement
36.8) are the whole definition; memorize them as a pair.

**Time constant math:** `τ = R × C`. Components combine before you plug in — capacitors in parallel
**add**, resistors in parallel use the **reciprocal** rule. Two 220 µF caps in parallel give 440 µF;
two 1-megohm resistors in parallel give 500 kΩ; `τ = 500,000 Ω × 0.00044 F = 220 seconds` (E5B04).

**Admittance, conductance, and susceptance** are the reactive-circuit cousins of resistance and
conductance in a DC circuit. **Admittance (Y) is the inverse of impedance (Z)** (E5B12); its
imaginary part is **susceptance**, symbol **B** (E5B02, E5B06). To convert an impedance in **polar
form** to admittance: **take the reciprocal of the magnitude and change the sign of the angle**
(E5B03). Converting pure reactance to susceptance also uses a reciprocal: the magnitude of a
reactance is **replaced by its reciprocal** when expressed as susceptance (E5B05).

**Phase angle in a series RLC circuit:** find net reactance `X = XL − XC`, then
`angle = arctan(X / R)`. A **positive** result (XL > XC, net inductive) means **voltage leads
current**; a **negative** result (XC > XL, net capacitive) means **voltage lags current** — the same
"ELI the ICE man" rule from General class, extended to mixed circuits with the arctangent layered on
top. Three worked examples appear verbatim in the pool:

| XC | R | XL | Net X | Angle | Result |
|---|---|---|---|---|---|
| 500 Ω | 1 kΩ | 250 Ω | −250 Ω | 14.0° | Voltage **lags** current (E5B07) |
| 300 Ω | 100 Ω | 100 Ω | −200 Ω | 63° | Voltage **lags** current (E5B08) |
| 25 Ω | 100 Ω | 75 Ω | +50 Ω | 27° | Voltage **leads** current (E5B11) |

**Pure component phase relationships**, the building blocks behind that table: in a capacitor,
**current leads voltage by 90°** (E5B09); in an inductor, **voltage leads current by 90°** (E5B10).

#### All 12 pool questions for E5B

**E5B01**

What is the term for the time required for the capacitor in an RC circuit to be charged to 63.2% of the applied voltage or to discharge to 36.8% of its initial voltage?

- A. An exponential rate of one
- **B. One time constant**  ←
- C. One exponential period
- D. A time factor of one

**E5B02**

What letter is commonly used to represent susceptance?

- A. G
- B. X
- C. Y
- **D. B**  ←

**E5B03**

How is impedance in polar form converted to an equivalent admittance?

- A. Take the reciprocal of the angle and change the sign of the magnitude
- **B. Take the reciprocal of the magnitude and change the sign of the angle**  ←
- C. Take the square root of the magnitude and add 180 degrees to the angle
- D. Square the magnitude and subtract 90 degrees from the angle

**E5B04**

What is the time constant of a circuit having two 220-microfarad capacitors and two 1-megohm resistors, all in parallel?

- A. 55 seconds
- B. 110 seconds
- C. 440 seconds
- **D. 220 seconds**  ←

**E5B05**

What is the effect on the magnitude of pure reactance when it is converted to susceptance?

- A. It is unchanged
- B. The sign is reversed
- C. It is shifted by 90 degrees
- **D. It is replaced by its reciprocal**  ←

**E5B06**

What is susceptance?

- A. The magnetic impedance of a circuit
- B. The ratio of magnetic field to electric field
- **C. The imaginary part of admittance**  ←
- D. A measure of the efficiency of a transformer

**E5B07**

What is the phase angle between the voltage across and the current through a series RLC circuit if XC is 500 ohms, R is 1 kilohm, and XL is 250 ohms?

- A. 68.2 degrees with the voltage leading the current
- B. 14.0 degrees with the voltage leading the current
- **C. 14.0 degrees with the voltage lagging the current**  ←
- D. 68.2 degrees with the voltage lagging the current

**E5B08**

What is the phase angle between the voltage across and the current through a series RLC circuit if XC is 300 ohms, R is 100 ohms, and XL is 100 ohms?

- **A. 63 degrees with the voltage lagging the current**  ←
- B. 63 degrees with the voltage leading the current
- C. 27 degrees with the voltage leading the current
- D. 27 degrees with the voltage lagging the current

**E5B09**

What is the relationship between the AC current through a capacitor and the voltage across a capacitor?

- A. Voltage and current are in phase
- B. Voltage and current are 180 degrees out of phase
- C. Voltage leads current by 90 degrees
- **D. Current leads voltage by 90 degrees**  ←

**E5B10**

What is the relationship between the AC current through an inductor and the voltage across an inductor?

- **A. Voltage leads current by 90 degrees**  ←
- B. Current leads voltage by 90 degrees
- C. Voltage and current are 180 degrees out of phase
- D. Voltage and current are in phase

**E5B11**

What is the phase angle between the voltage across and the current through a series RLC circuit if XC is 25 ohms, R is 100 ohms, and XL is 75 ohms?

- A. 27 degrees with the voltage lagging the current
- **B. 27 degrees with the voltage leading the current**  ←
- C. 63 degrees with the voltage lagging the current
- D. 63 degrees with the voltage leading the current

**E5B12**

What is admittance?

- **A. The inverse of impedance**  ←
- B. The term for the gain of a field effect transistor
- C. The inverse of reactance
- D. The term for the on-impedance of a field effect transistor

---

## E5C — Coordinate systems and phasors in electronics: rectangular coordinates; polar coordinates; phasors; logarithmic axes

*One exam question comes from this group. 12 questions in the pool.*

**Rectangular notation** writes impedance as `R ± jX`: the real part is resistance, the imaginary
part is reactance, with **+j for inductive** and **−j for capacitive**. A pure 100 Ω capacitive
reactance is **0 − j100** (E5C01); 50 − j25 Ω means **50 Ω resistance in series with 25 Ω of
capacitive reactance** (E5C06) — the minus sign is what makes it capacitive, not inductive.

**On the rectangular R-X plane**, resistance is the **X axis (horizontal)** and reactance is the
**Y axis (vertical)** (E5C09); a pure resistance, having no reactive component, plots **on the
horizontal axis** (E5C07).

**Polar notation** describes the same impedance as **magnitude and phase angle** instead of two
rectangular components (E5C02). A pure inductive reactance sits at a **positive 90°** angle in polar
form (E5C03) — capacitive reactance mirrors it at −90°, the same ± convention as the j-sign in
rectangular form. **Polar coordinates** are the standard way to display the phase angle of any
circuit that mixes R, L, and/or C (E5C08), and a **phasor diagram** is the picture used to show the
phase relationship between multiple impedances at one frequency (E5C05).

**Frequency response graphs use a logarithmic Y-axis** (E5C04) — RF quantities like gain and response
span orders of magnitude, so log scaling is standard.

**The three figure questions (E5C10–E5C12)** ask you to locate a computed impedance on the pool's
Figure E5-1 R-X plane. You can't see the figure here, but the underlying arithmetic is ordinary:
compute XC = 1/(2πfC) or XL = 2πfL at the given frequency, pair it with the given resistance, and
that (R, X) pair is the point you're looking for. The pool's stated answers are **Point 4** (400 Ω
resistor with a 38 pF capacitor at 14 MHz), **Point 3** (300 Ω resistor with an 18 µH inductor at
3.505 MHz), and **Point 1** (300 Ω resistor with a 19 pF capacitor at 21.200 MHz).

#### All 12 pool questions for E5C

**E5C01**

Which of the following represents pure capacitive reactance of 100 ohms in rectangular notation?

- **A. 0 - j100**  ←
- B. 0 + j100
- C. 100 - j0
- D. 100 + j0

**E5C02**

How are impedances described in polar coordinates?

- A. By X and R values
- B. By real and imaginary parts
- **C. By magnitude and phase angle**  ←
- D. By Y and G values

**E5C03**

Which of the following represents a pure inductive reactance in polar coordinates?

- A. A positive 45 degree phase angle
- B. A negative 45 degree phase angle
- **C. A positive 90 degree phase angle**  ←
- D. A negative 90 degree phase angle

**E5C04**

What type of Y-axis scale is most often used for graphs of circuit frequency response?

- A. Linear
- B. Scatter
- C. Random
- **D. Logarithmic**  ←

**E5C05**

What kind of diagram is used to show the phase relationship between impedances at a given frequency?

- A. Venn diagram
- B. Near field diagram
- **C. Phasor diagram**  ←
- D. Far field diagram

**E5C06**

What does the impedance 50 - j25 ohms represent?

- A. 50 ohms resistance in series with 25 ohms inductive reactance
- **B. 50 ohms resistance in series with 25 ohms capacitive reactance**  ←
- C. 25 ohms resistance in series with 50 ohms inductive reactance
- D. 25 ohms resistance in series with 50 ohms capacitive reactance

**E5C07**

Where is the impedance of a pure resistance plotted on rectangular coordinates?

- A. On the vertical axis
- B. On a line through the origin, slanted at 45 degrees
- C. On a horizontal line, offset vertically above the horizontal axis
- **D. On the horizontal axis**  ←

**E5C08**

What coordinate system is often used to display the phase angle of a circuit containing resistance, inductive, and/or capacitive reactance?

- A. Maidenhead grid
- B. Faraday grid
- C. Elliptical coordinates
- **D. Polar coordinates**  ←

**E5C09**

When using rectangular coordinates to graph the impedance of a circuit, what do the axes represent?

- **A. The X axis represents the resistive component, and the Y axis represents the reactive component**  ←
- B. The X axis represents the reactive component, and the Y axis represents the resistive component
- C. The X axis represents the phase angle, and the Y axis represents the magnitude
- D. The X axis represents the magnitude, and the Y axis represents the phase angle

**E5C10**

Which point on Figure E5-1 best represents the impedance of a series circuit consisting of a 400-ohm resistor and a 38-picofarad capacitor at 14 MHz?

- A. Point 2
- **B. Point 4**  ←
- C. Point 5
- D. Point 6

**E5C11**

Which point in Figure E5-1 best represents the impedance of a series circuit consisting of a 300-ohm resistor and an 18-microhenry inductor at 3.505 MHz?

- A. Point 1
- **B. Point 3**  ←
- C. Point 7
- D. Point 8

**E5C12**

Which point on Figure E5-1 best represents the impedance of a series circuit consisting of a 300-ohm resistor and a 19-picofarad capacitor at 21.200 MHz?

- **A. Point 1**  ←
- B. Point 3
- C. Point 7
- D. Point 8

---

## E5D — RF effects in components and circuits: skin effect; real and reactive power; electrical length of conductors

*One exam question comes from this group. 12 questions in the pool.*

**Skin effect:** as frequency rises, RF current crowds toward the conductor's **surface**, shrinking
the effective cross-section, so **resistance increases as frequency increases** (E5D01). That's why
**short leads matter at VHF and above** — short leads **minimize inductive reactance** (E5D02), and
at microwave frequencies short connections specifically **reduce phase shift along the connection**
(E5D04); at those frequencies even a short wire is an appreciable fraction of a wavelength.

**Real component parasitics — three separate failure modes to keep straight:**

| Component | RF weakness | Cause |
|---|---|---|
| Electrolytic capacitor | Unsuitable at RF | **Inductance** (E5D05) |
| Film capacitor | Primary RF loss | **Dielectric loss** (E5D08) |
| Any inductor | Self-resonance | **Inter-turn capacitance** (E5D06) |

Self-resonance in general is what happens when a component's **nominal reactance combines with its
parasitic reactance** (E5D07) — an inductor's designed-in inductance plus its unwanted inter-turn
capacitance together form a resonant circuit at some frequency, above which the inductor stops
behaving like an inductor (compare General's G6A11: above self-resonance, an inductor becomes
capacitive).

**Electrical length grows with conductor diameter** — a fatter conductor is electrically longer than
a thin one of the same physical length (E5D10), a detail that matters when cutting elements to a
precise fraction of a wavelength.

**Real power vs. reactive power.** Real power is dissipated only by the **resistive** part of an
impedance: `P = I² × R`. A 100 Ω resistor in series with a 100 Ω inductive reactance, drawing 1 A,
dissipates `1² × 100 = 100 W` of **real power** (E5D11) — the reactance contributes zero watts
despite carrying the same current. That's because **reactive power is wattless, nonproductive power**
(E5D12): current and voltage in a pure reactance are **90 degrees out of phase** (E5D03), so their
product averages to zero over a cycle. In an ideal inductor or capacitor, that energy is not
dissipated as heat — it is **stored in the magnetic or electric field** and handed back to the
circuit every half-cycle (E5D09).

#### All 12 pool questions for E5D

**E5D01**

What is the result of conductor skin effect?

- **A. Resistance increases as frequency increases because RF current flows closer to the surface**  ←
- B. Resistance decreases as frequency increases because electron mobility increases
- C. Resistance increases as temperature increases because of the change in thermal coefficient
- D. Resistance decreases as temperature increases because of the change in thermal coefficient

**E5D02**

Why is it important to keep lead lengths short for components used in circuits for VHF and above?

- A. To increase the thermal time constant
- **B. To minimize inductive reactance**  ←
- C. To maintain component lifetime
- D. All these choices are correct

**E5D03**

What is the phase relationship between current and voltage for reactive power?

- A. They are out of phase
- B. They are in phase
- **C. They are 90 degrees out of phase**  ←
- D. They are 45 degrees out of phase

**E5D04**

Why are short connections used at microwave frequencies?

- A. To increase neutralizing resistance
- **B. To reduce phase shift along the connection**  ←
- C. To increase compensating capacitance
- D. To reduce noise figure

**E5D05**

What parasitic characteristic causes electrolytic capacitors to be unsuitable for use at RF?

- A. Skin effect
- B. Shunt capacitance
- **C. Inductance**  ←
- D. Dielectric leakage

**E5D06**

What parasitic characteristic creates an inductor’s self-resonance?

- A. Skin effect
- B. Dielectric loss
- C. Coupling
- **D. Inter-turn capacitance**  ←

**E5D07**

What combines to create the self-resonance of a component?

- A. The component’s resistance and reactance
- **B. The component’s nominal and parasitic reactance**  ←
- C. The component’s inductance and capacitance
- D. The component’s electrical length and impedance

**E5D08**

What is the primary cause of loss in film capacitors at RF?

- A. Inductance
- B. Dielectric loss
- C. Self-discharge
- **D. Skin effect**  ←

**E5D09**

What happens to reactive power in ideal inductors and capacitors?

- A. It is dissipated as heat in the circuit
- **B. Energy is stored in magnetic or electric fields, but power is not dissipated**  ←
- C. It is canceled by Coulomb forces in the capacitor and inductor
- D. It is dissipated in the formation of inductive and capacitive fields

**E5D10**

As a conductor’s diameter increases, what is the effect on its electrical length?

- A. Thickness has no effect on electrical length
- B. It varies randomly
- C. It decreases
- **D. It increases**  ←

**E5D11**

How much real power is consumed in a circuit consisting of a 100-ohm resistor in series with a 100-ohm inductive reactance drawing 1 ampere?

- A. 70.7 watts
- **B. 100 watts**  ←
- C. 141.4 watts
- D. 200 watts

**E5D12**

What is reactive power?

- A. Power consumed in circuit Q
- B. Power consumed by an inductor’s wire resistance
- C. The power consumed in inductors and capacitors
- **D. Wattless, nonproductive power**  ←

---

## Bottom line for E5

At resonance, **XL cancels XC**, voltage and current are **in phase**, and impedance is **≈ R** for
both series and parallel circuits — series current is maximum/impedance minimum, parallel input
current is minimum/impedance maximum, tank circulating current is maximum. `f = 1/(2π√(LC))`;
`BW = f/Q`; parallel `Q = R/X`. Higher Q means **narrower bandwidth** and **higher internal voltages**.

One time constant is **63.2%** charge / **36.8%** discharge; `τ = RC` after combining parallel caps
(add) and parallel resistors (reciprocal). **Admittance is 1/Z**; its imaginary part is
**susceptance (B)**; polar-to-admittance takes the **reciprocal magnitude, flipped-sign angle**.
Phase angle is `arctan((XL−XC)/R)`: positive means **voltage leads current** (net inductive), negative
means **voltage lags** (net capacitive). Pure inductor: **voltage leads by 90°**. Pure capacitor:
**current leads by 90°**.

Rectangular form is `R ± jX` (**+j inductive, −j capacitive**), plotted with **R on the horizontal
axis, X on the vertical**. Polar form is **magnitude and angle**; a phasor diagram shows relative
phase; frequency-response graphs use a **logarithmic** Y-axis.

**Skin effect** raises resistance with frequency. Electrolytic capacitors fail at RF from
**inductance**; film capacitors from **dielectric loss**; inductors self-resonate from **inter-turn
capacitance** combining with nominal inductance. Real power is `I²R` and lives only in resistance;
**reactive power is wattless**, stored in the field and returned every half-cycle, **90° out of
phase**.
