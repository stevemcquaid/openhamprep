# G6 — Circuit Components

**2 of your 35 exam questions · 2 groups (G6A–G6B) · 23 questions in the pool**

The smallest subelement along with G0. Pure component trivia: no math, no reasoning, just a short
list of facts. Because it is short, it is worth learning completely — two easy questions.

## Table of Contents

- [G6A — Resistors; capacitors; inductors; diodes and transistors; vacuum tubes; batteries](#g6a--resistors-capacitors-inductors-diodes-and-transistors-vacuum-tubes-batteries)
  - [All 12 pool questions for G6A](#all-12-pool-questions-for-g6a)
- [G6B — Integrated circuits; MMICs; display devices; RF connectors; ferrite cores](#g6b--integrated-circuits-mmics-display-devices-rf-connectors-ferrite-cores)
  - [All 11 pool questions for G6B](#all-11-pool-questions-for-g6b)
- [Bottom line for G6](#bottom-line-for-g6)

---

## G6A — Resistors; capacitors; inductors; diodes and transistors; vacuum tubes; batteries

*One exam question comes from this group. 12 questions in the pool.*

**Diode forward voltage, both asked:** germanium **0.3 V**, silicon **0.7 V**.

**Capacitors.** Electrolytics give **high capacitance for a given volume** (they are *not* tight
tolerance and *not* low leakage, whatever the distractors say). Low-voltage ceramics are
**comparatively low cost**.

**Why no wire-wound resistors at RF?** Their **inductance makes circuit performance
unpredictable** — a wire-wound resistor is literally a coil. Relatedly, an **inductor operated above
its self-resonant frequency becomes capacitive**, because stray capacitance between turns takes over.

**Transistors.** A bipolar transistor used as a **switch** operates at **saturation and cutoff** —
fully on, fully off; the linear region between them is for amplifiers. A **MOSFET's gate is separated
from the channel by a thin insulating layer**, which is the "oxide" in the name and the reason
MOSFETs are static-sensitive.

**Vacuum tubes.** The **control grid regulates electron flow** between cathode and plate; the
**screen grid reduces grid-to-plate capacitance**. The control grid controls, the screen grid
screens.

**Batteries.** A 12 V lead-acid battery should not be discharged below **10.5 V**. **Low internal
resistance allows high discharge current**, because the terminal voltage does not collapse under
load.

#### All 12 pool questions for G6A

**G6A01**

What is the minimum allowable discharge voltage for maximum life of a standard 12-volt lead-acid battery?

- A. 6 volts
- B. 8.5 volts
- C. 10.5 volts
- D. 12 volts
-
- Answer: C

**G6A02**

What is an advantage of batteries with low internal resistance?

- A. Long life
- B. High discharge current
- C. High voltage
- D. Rapid recharge
-
- Answer: B

**G6A03**

What is the approximate forward threshold voltage of a germanium diode?

- A. 0.1 volt
- B. 0.3 volts
- C. 0.7 volts
- D. 1.0 volts
-
- Answer: B

**G6A04**

Which of the following is characteristic of an electrolytic capacitor?

- A. Tight tolerance
- B. Much less leakage than any other type
- C. High capacitance for a given volume
- D. Inexpensive RF capacitor
-
- Answer: C

**G6A05**

What is the approximate forward threshold voltage of a silicon junction diode?

- A. 0.1 volt
- B. 0.3 volts
- C. 0.7 volts
- D. 1.0 volts
-
- Answer: C

**G6A06**

Why should wire-wound resistors not be used in RF circuits?

- A. The resistor’s tolerance value would not be adequate
- B. The resistor’s inductance could make circuit performance unpredictable
- C. The resistor could overheat
- D. The resistor’s internal capacitance would detune the circuit
-
- Answer: B

**G6A07**

What are the operating points for a bipolar transistor used as a switch?

- A. Saturation and cutoff
- B. The active region (between cutoff and saturation)
- C. Peak and valley current points
- D. Enhancement and depletion modes
-
- Answer: A

**G6A08**

Which of the following is characteristic of low voltage ceramic capacitors?

- A. Tight tolerance
- B. High stability
- C. High capacitance for given volume
- D. Comparatively low cost
-
- Answer: D

**G6A09**

Which of the following describes MOSFET construction?

- A. The gate is formed by a back-biased junction
- B. The gate is separated from the channel by a thin insulating layer
- C. The source is separated from the drain by a thin insulating layer
- D. The source is formed by depositing metal on silicon
-
- Answer: B

**G6A10**

Which element of a vacuum tube regulates the flow of electrons between cathode and plate?

- A. Control grid
- B. Suppressor grid
- C. Screen grid
- D. Trigger electrode
-
- Answer: A

**G6A11**

What happens when an inductor is operated above its self-resonant frequency?

- A. Its reactance increases
- B. Harmonics are generated
- C. It becomes capacitive
- D. Catastrophic failure is likely
-
- Answer: C

**G6A12**

What is the primary purpose of a screen grid in a vacuum tube?

- A. To reduce grid-to-plate capacitance
- B. To increase efficiency
- C. To increase the control grid resistance
- D. To decrease plate resistance
-
- Answer: A

---

## G6B — Integrated circuits; MMICs; display devices; RF connectors; ferrite cores

*One exam question comes from this group. 11 questions in the pool.*

**Ferrite cores are the most-tested item here** — three questions. Performance at different
frequencies is set by the **composition, or "mix," of materials** (not size or shape). A ferrite bead
reduces common-mode current on a coax shield **by creating an impedance in the current's path** — it
is a lossy choke, not a shield and not a cancellation effect. And the advantages of a ferrite
toroidal inductor are **all these choices are correct**.

**ICs.** **MMIC** is **Monolithic Microwave Integrated Circuit** — the other expansions offered are
invented. An **operational amplifier is analog**. **CMOS beats TTL on low power consumption**.

**An LED is forward biased when emitting light** — conducting is what makes it glow.

**Connectors, roughly a frequency ladder:**

| Connector | Fact |
|---|---|
| **RCA phono** | **Low frequency or DC** connections |
| **BNC** | Low SWR to about **4 GHz** |
| **SMA** | **Small threaded**, good to **several GHz** |
| **Type N** | **Moisture-resistant**, useful to **10 GHz** |

Type N is the weatherproof one that goes highest. It is *not* a nickel-plated PL-259 — that is a
distractor.

#### All 11 pool questions for G6B

**G6B01**

What determines the performance of a ferrite core at different frequencies?

- A. Its conductivity
- B. Its thickness
- C. The composition, or “mix,” of materials used
- D. The ratio of outer diameter to inner diameter
-
- Answer: C

**G6B02**

What is meant by the term MMIC?

- A. Multi-Mode Integrated Circuit
- B. Monolithic Microwave Integrated Circuit
- C. Metal Monolayer Integrated Circuit
- D. Mode Modulated Integrated Circuit
-
- Answer: B

**G6B03**

Which of the following is an advantage of CMOS integrated circuits compared to TTL integrated circuits?

- A. Low power consumption
- B. High power handling capability
- C. Better suited for RF amplification
- D. Better suited for power supply regulation
-
- Answer: A

**G6B04**

What is a typical upper frequency limit for low SWR operation of 50-ohm BNC connectors?

- A. 50 MHz
- B. 500 MHz
- C. 4 GHz
- D. 40 GHz
-
- Answer: C

**G6B05**

What is an advantage of using a ferrite core toroidal inductor?

- A. Large values of inductance may be obtained
- B. The magnetic properties of the core may be optimized for a specific range of frequencies
- C. Most of the magnetic field is contained in the core
- D. All these choices are correct
-
- Answer: D

**G6B06**

What kind of device is an integrated circuit operational amplifier?

- A. Digital
- B. MMIC
- C. Programmable Logic
- D. Analog
-
- Answer: D

**G6B07**

Which of the following describes a type N connector?

- A. A moisture-resistant RF connector useful to 10 GHz
- B. A small bayonet connector used for data circuits
- C. A low noise figure VHF connector
- D. A nickel plated version of the PL-259
-
- Answer: A

**G6B08**

How is an LED biased when emitting light?

- A. In the tunnel-effect region
- B. At the Zener voltage
- C. Reverse biased
- D. Forward biased
-
- Answer: D

**G6B10**

How does a ferrite bead or core reduce common-mode RF current on the shield of a coaxial cable?

- A. By creating an impedance in the current’s path
- B. It converts common-mode current to differential mode current
- C. By creating an out-of-phase current to cancel the common-mode current
- D. Ferrites expel magnetic fields
-
- Answer: A

**G6B11**

What is an SMA connector?

- A. A type-S to type-M adaptor
- B. A small threaded connector suitable for signals up to several GHz
- C. A connector designed for serial multiple access signals
- D. A type of push-on connector intended for high-voltage applications
-
- Answer: B

**G6B12**

Which of these connector types is commonly used for low frequency or dc signal connections to a transceiver?

- A. PL-259
- B. BNC
- C. RCA Phono
- D. Type N
-
- Answer: C

---

## Bottom line for G6

Silicon **0.7 V**, germanium **0.3 V**. Electrolytics give **capacitance per volume**; ceramics are
**cheap**. No wire-wound resistors at RF because of **inductance**; above self-resonance an inductor
goes **capacitive**. A switching transistor runs at **saturation and cutoff**; a MOSFET gate sits
behind **a thin insulator**. **Control grid controls, screen grid reduces grid-to-plate capacitance.**
Lead-acid stops at **10.5 V**. Ferrite performance comes from the **mix**; a bead works by **adding
impedance**. **Type N** is the weatherproof 10 GHz connector.
