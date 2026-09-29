# E7 — Practical Circuits

**8 of your 50 exam questions · 8 groups (E7A–E7H) · 99 questions in the pool**

The largest subelement in the Extra pool by a wide margin: eight groups covering digital logic,
RF and audio amplifiers, filters and matching networks, power supplies and voltage regulators,
modulation and demodulation circuits, software defined radio fundamentals, operational amplifiers,
and oscillators. It still only counts for eight of your 50 questions — one per group, same as
everywhere else — but with 99 questions feeding those eight slots it holds nearly a fifth of the
entire pool.

Much of it is memorization (gate logic, filter names, Colpitts/Hartley/Pierce feedback paths), but
a real chunk requires circuit reasoning: dividing a frequency with flip-flops, computing op-amp
gain from a resistor ratio, and reading the Figure E7-1 and E7-2 schematics for bias and feedback
components. This is the single highest-yield subelement on the exam — budget extra time for it.

---

## E7A — Digital circuits: digital circuit principles and logic circuits; classes of logic elements; positive and negative logic; frequency dividers; truth tables

*One exam question comes from this group. 11 questions in the pool.*

**Multivibrator family, by how they hold state.** A **flip-flop is bistable** — two stable states,
switched by an input. A **monostable multivibrator switches temporarily to an alternate state for a
set time** and then returns on its own (a one-shot). An **astable multivibrator continuously
alternates between two states without an external clock signal** — it free-runs.

**Counting and dividing.** A **decade counter produces one output pulse for every 10 input
pulses**. A single **flip-flop divides a pulse train's frequency by 2**; since each flip-flop only
halves the frequency, dividing by 16 (2⁴) takes **4 flip-flops**.

**Gate logic — read the output condition carefully.** A **NAND gate outputs 0 only if all inputs
are 1** (it is an AND gate with an inverted output). An **OR gate outputs 1 if any input is 1**. A
two-input **exclusive NOR (XNOR) gate outputs 0 if one and only one of its inputs is 1** — it is
high only when the inputs *agree*, the mirror image of XOR.

**Vocabulary.** A **truth table is a list of inputs and corresponding outputs for a digital
device**. **“Positive logic” means high voltage represents a 1, low voltage a 0** — logic level
defined by which voltage is asserted, not by what the circuit is doing.

#### All 11 pool questions for E7A

**E7A01**

Which circuit is bistable?

- A. An AND gate
- B. An OR gate
- **C. A flip-flop**  ←
- D. A bipolar amplifier

**E7A02**

What is the function of a decade counter?

- **A. It produces one output pulse for every 10 input pulses**  ←
- B. It decodes a decimal number for display on a seven-segment LED display
- C. It produces 10 output pulses for every input pulse
- D. It decodes a binary number for display on a seven-segment LED display

**E7A03**

Which of the following can divide the frequency of a pulse train by 2?

- A. An XOR gate
- **B. A flip-flop**  ←
- C. An OR gate
- D. A multiplexer

**E7A04**

How many flip-flops are required to divide a signal frequency by 16?

- **A. 4**  ←
- B. 6
- C. 8
- D. 16

**E7A05**

Which of the following circuits continuously alternates between two states without an external clock signal?

- A. Monostable multivibrator
- B. J-K flip-flop
- C. T flip-flop
- **D. Astable multivibrator**  ←

**E7A06**

What is a characteristic of a monostable multivibrator?

- **A. It switches temporarily to an alternate state for a set time**  ←
- B. It produces a continuous square wave
- C. It stores one bit of data
- D. It maintains a constant output voltage, regardless of variations in the input voltage

**E7A07**

What logical operation does a NAND gate perform?

- A. It produces a 0 at its output only if all inputs are 0
- B. It produces a 1 at its output only if all inputs are 1
- C. It produces a 0 at its output if some but not all inputs are 1
- **D. It produces a 0 at its output only if all inputs are 1**  ←

**E7A08**

What logical operation does an OR gate perform?

- **A. It produces a 1 at its output if any input is 1**  ←
- B. It produces a 0 at its output if all inputs are 1
- C. It produces a 0 at its output if some but not all inputs are 1
- D. It produces a 1 at its output if all inputs are 0

**E7A09**

What logical operation is performed by a two-input exclusive NOR gate?

- A. It produces a 0 at its output only if all inputs are 0
- B. It produces a 1 at its output only if all inputs are 1
- **C. It produces a 0 at its output if one and only one of its inputs is 1**  ←
- D. It produces a 1 at its output if one and only one input is 1

**E7A10**

What is a truth table?

- A. A list of inputs and corresponding outputs for an op-amp
- **B. A list of inputs and corresponding outputs for a digital device**  ←
- C. A diagram showing logic states when the digital gate output is true
- D. A table of logic symbols that indicate the logic states of an op-amp

**E7A11**

What does “positive logic” mean in reference to logic devices?

- A. The logic devices have high noise immunity
- **B. High voltage represents a 1, low voltage a 0**  ←
- C. The logic circuit is in the “true” condition
- D. 1s and 0s are defined as different positive voltage levels

---

## E7B — Amplifiers: class of operation; vacuum tube and solid-state circuits; distortion and intermodulation; spurious and parasitic suppression; switching-type amplifiers

*One exam question comes from this group. 12 questions in the pool.*

**Conduction angle by class.** Class A conducts the entire 360-degree cycle. Class B conducts
exactly 180 degrees. **Class AB, in a push-pull pair, has each active element conducting more than
180 degrees but less than 360 degrees** — the compromise between A's linearity and B's efficiency.
**Class D is a switching amplifier**, achieving high efficiency because the active device spends its
time at saturation or cutoff rather than in a lossy linear region — the same reason switching
amplifiers generally beat linear ones on efficiency.

**Class A bias point.** The operating point of a **Class A common emitter amplifier sits
approximately halfway between saturation and cutoff** — centered on the load line so the full
waveform swings without clipping.

**RF switching amplifiers need a low-pass output filter** to strip the harmonic content that
switching (square-wave-like) operation generates — without it, a switching PA is a spray of
harmonics. Feeding a **Class C amplifier a single-sideband phone signal produces distortion and
excessive bandwidth**, because Class C is non-linear and only reproduces constant-envelope signals
(CW, FM) faithfully.

**Stability.** Unwanted oscillations in an RF power amplifier are prevented by **installing
parasitic suppressors and/or neutralizing the stage**. A **grounded-grid amplifier's defining trait
is low input impedance** — it is driven into the cathode, and that low impedance is part of why the
configuration is inherently stable without separate neutralization.

**Emitter follower (common collector).** Its signature is **input and output signals in-phase** —
no phase inversion, unlike a common-emitter stage — paired with high input impedance and low output
impedance, which is why it is used as a buffer.

**Figure E7-1 (common-emitter amplifier).** **R1 and R2 form a voltage divider that sets the DC
bias** on the base. **R3, in the emitter leg, provides self bias** (emitter degeneration) rather
than acting as a load or feedback element on its own.

#### All 12 pool questions for E7B

**E7B01**

For what portion of the signal cycle does each active element in a push-pull, Class AB amplifier conduct?

- **A. More than 180 degrees but less than 360 degrees**  ←
- B. Exactly 180 degrees
- C. The entire cycle
- D. Less than 180 degrees

**E7B02**

What is a Class D amplifier?

- **A. An amplifier that uses switching technology to achieve high efficiency**  ←
- B. A low power amplifier that uses a differential amplifier for improved linearity
- C. An amplifier that uses drift-mode FETs for high efficiency
- D. An amplifier biased to be relatively free from distortion

**E7B03**

What circuit is required at the output of an RF switching amplifier?

- **A. A filter to remove harmonic content**  ←
- B. A high-pass filter to compensate for low gain at low frequencies
- C. A matched load resistor to prevent damage by switching transients
- D. A temperature compensating load resistor to improve linearity

**E7B04**

What is the operating point of a Class A common emitter amplifier?

- **A. Approximately halfway between saturation and cutoff**  ←
- B. Approximately halfway between the emitter voltage and the base voltage
- C. At a point where the bias resistor equals the load resistor
- D. At a point where the load line intersects the zero bias current curve

**E7B05**

What can be done to prevent unwanted oscillations in an RF power amplifier?

- A. Tune the stage for minimum loading
- B. Tune both the input and output for maximum power
- **C. Install parasitic suppressors and/or neutralize the stage**  ←
- D. Use a phase inverter in the output filter

**E7B06**

What is a characteristic of a grounded-grid amplifier?

- A. High power gain
- **B. Low input impedance**  ←
- C. High electrostatic damage protection
- D. Low bandwidth

**E7B07**

Which of the following is the likely result of using a Class C amplifier to amplify a single-sideband phone signal?

- A. Reduced intermodulation products
- B. Increased overall intelligibility
- C. Reduced third-order intermodulation
- **D. Signal distortion and excessive bandwidth**  ←

**E7B08**

Why are switching amplifiers more efficient than linear amplifiers?

- A. Switching amplifiers operate at higher voltages
- **B. The switching device is at saturation or cutoff most of the time**  ←
- C. Linear amplifiers have high gain resulting in higher harmonic content
- D. Switching amplifiers use push-pull circuits

**E7B09**

What is characteristic of an emitter follower (or common collector) amplifier?

- A. Low input impedance and phase inversion from input to output
- B. Differential inputs and single output
- C. Acts as an OR circuit if one input is grounded
- **D. Input and output signals in-phase**  ←

**E7B10**

In Figure E7-1, what is the purpose of R1 and R2?

- A. Load resistors
- **B. Voltage divider bias**  ←
- C. Self bias
- D. Feedback

**E7B11**

In Figure E7-1, what is the purpose of R3?

- A. Fixed bias
- B. Emitter bypass
- C. Output load resistor
- **D. Self bias**  ←

**E7B12**

What type of amplifier circuit is shown in Figure E7-1?

- A. Common base
- B. Common collector
- **C. Common emitter**  ←
- D. Emitter follower

---

## E7C — Filters and matching networks: types of networks; types of filters; filter applications; filter characteristics; impedance matching

*One exam question comes from this group. 11 questions in the pool.*

**Pi-network arrangement.** In a **low-pass Pi-network, a capacitor connects the input to ground,
another capacitor connects the output to ground, and an inductor runs between input and output** —
capacitor, inductor, capacitor, forming the shape of the Greek letter. A **T-network with series
capacitors and a shunt inductor is a high-pass** response — the mirror-image component arrangement
of the low-pass case.

**Pi-L network.** Adding an inductor to a Pi-network to make a **Pi-L-network gives greater harmonic
suppression**. Structurally, a **Pi-L network is a Pi-network with an additional output series
inductor**.

**Impedance matching, conceptually.** A matching circuit transforms a complex impedance to a
resistive one by **canceling the reactive part of the impedance and changing the resistive part to
the desired value** — it is not about dissipating power in resistors or introducing negative
resistance.

**Filter types.** A **Chebyshev filter has ripple in the passband and a sharp cutoff** — it trades
passband flatness for steepness. An **elliptical filter has an extremely sharp cutoff with one or
more notches in the stop band** — it goes further than Chebyshev by adding stopband ripple (notches)
for an even sharper transition.

**Applications.** A **helical filter is most frequently used as a band-pass or notch filter in VHF
and UHF transceivers**. A **crystal lattice filter is a filter for low-level signals made using
quartz crystals** — narrow, high-Q IF filtering. A **cavity filter is used in a 2-meter band repeater
duplexer**, where it separates closely-spaced transmit and receive frequencies.

**Measuring selectivity.** **Shape factor measures a filter's ability to reject signals in adjacent
channels** — the ratio of a filter's stopband width to its passband width; the closer to 1, the more
rectangular (and better) the response.

#### All 11 pool questions for E7C

**E7C01**

How are the capacitors and inductors of a low-pass filter Pi-network arranged between the network’s input and output?

- A. Two inductors are in series between the input and output, and a capacitor is connected between the two inductors and ground
- B. Two capacitors are in series between the input and output, and an inductor is connected between the two capacitors and ground
- C. An inductor is connected between the input and ground, another inductor is connected between the output and ground, and a capacitor is connected between the input and output
- **D. A capacitor is connected between the input and ground, another capacitor is connected between the output and ground, and an inductor is connected between the input and output**  ←

**E7C02**

What is the frequency response of a T-network with series capacitors and a shunt inductor?

- A. Low-pass
- **B. High-pass**  ←
- C. Band-pass
- D. Notch

**E7C03**

What is the purpose of adding an inductor to a Pi-network to create a Pi-L-network?

- **A. Greater harmonic suppression**  ←
- B. Higher efficiency
- C. To eliminate one capacitor
- D. Greater transformation range

**E7C04**

How does an impedance-matching circuit transform a complex impedance to a resistive impedance?

- A. It introduces negative resistance to cancel the resistive part of impedance
- B. It introduces transconductance to cancel the reactive part of impedance
- **C. It cancels the reactive part of the impedance and changes the resistive part to the desired value**  ←
- D. Reactive currents are dissipated in matched resistances

**E7C05**

Which filter type has ripple in the passband and a sharp cutoff?

- A. A Butterworth filter
- B. An active LC filter
- C. A passive op-amp filter
- **D. A Chebyshev filter**  ←

**E7C06**

What are the characteristics of an elliptical filter?

- A. Gradual passband rolloff with minimal stop-band ripple
- B. Extremely flat response over its pass band with gradually rounded stop-band corners
- **C. Extremely sharp cutoff with one or more notches in the stop band**  ←
- D. Gradual passband rolloff with extreme stop-band ripple

**E7C07**

Which describes a Pi-L network?

- A. A Phase Inverter Load network
- **B. A Pi-network with an additional output series inductor**  ←
- C. A network with only three discrete parts
- D. A matching network in which all components are isolated from ground

**E7C08**

Which of the following is most frequently used as a band-pass or notch filter in VHF and UHF transceivers?

- A. A Sallen-Key filter
- **B. A helical filter**  ←
- C. A swinging choke filter
- D. A finite impulse response filter

**E7C09**

What is a crystal lattice filter?

- A. A power supply filter made with interlaced quartz crystals
- B. An audio filter made with four quartz crystals that resonate at 1 kHz intervals
- C. A filter using lattice-shaped quartz crystals for high-Q performance
- **D. A filter for low-level signals made using quartz crystals**  ←

**E7C10**

Which of the following filters is used in a 2-meter band repeater duplexer?

- A. A crystal filter
- **B. A cavity filter**  ←
- C. A DSP filter
- D. An L-C filter

**E7C11**

Which of the following measures a filter’s ability to reject signals in adjacent channels?

- A. Passband ripple
- B. Phase response
- **C. Shape factor**  ←
- D. Noise factor

---

## E7D — Power supplies and voltage regulators; solar array charge controllers

*One exam question comes from this group. 15 questions in the pool.*

**Linear vs. switchmode, the core distinction.** A **linear regulator varies the conduction of a
control element to maintain a constant output voltage** — a pass transistor acting like a variable
resistor. A **switchmode regulator varies the duty cycle of pulses fed into a filter** instead —
switching a device fully on and off and controlling the average by timing, which is far more
efficient.

**Regulator topologies.** A **three-terminal voltage regulator is a series regulator**. A **shunt
regulator works by loading (diverting current away from) the unregulated voltage source** rather
than sitting in series with the load. A **Zener diode is the standard stable voltage reference** that
both types build around.

**Figure E7-2 (a series linear regulator).** **Q1 controls the current to keep the output voltage
constant** — the pass transistor. **C2 bypasses rectifier output ripple around D1**, keeping ripple
off the Zener reference so the regulated output stays clean. The whole circuit is a **linear
voltage regulator**.

**Regulator specs, precisely worded.** **Dropout voltage is the minimum input-to-output voltage
required to maintain regulation** — how close the input can sag to the output before regulation is
lost. **Power dissipated by a series linear regulator equals the voltage difference from input to
output, multiplied by the output current** — the classic (Vin − Vout) × Iout, which is exactly why
linear regulators run hot and switchers don't.

**Batteries and switchers.** **Battery operating time equals capacity in amp-hours divided by
average current.** A **switching power supply is cheaper and lighter than an equivalent linear
supply because its high-frequency inverter design uses much smaller transformers and filter
components for the same output power** — size and weight scale inversely with operating frequency.

**Solar and safety odds and ends.** An **inverter on a solar panel converts the panel's DC output to
AC**. **Equal-value resistors across series-connected filter capacitors equalize the voltage across
each capacitor** (and, per the pool's own answer, also discharge them and provide a minimum load —
“all these choices are correct”). A **step-start circuit in a high-voltage supply lets the filter
capacitors charge gradually**, preventing the inrush current that would otherwise arc across the
input switch or relay contacts.

#### All 15 pool questions for E7D

**E7D01**

How does a linear electronic voltage regulator work?

- A. It has a ramp voltage as its output
- B. It eliminates the need for a pass transistor
- C. The control element duty cycle is proportional to the line or load conditions
- **D. The conduction of a control element is varied to maintain a constant output voltage**  ←

**E7D02**

How does a switchmode voltage regulator work?

- A. By alternating the output between positive and negative voltages
- **B. By varying the duty cycle of pulses input to a filter**  ←
- C. By varying the conductivity of a pass element
- D. By switching between two Zener diode reference voltages

**E7D03**

What device is used as a stable voltage reference?

- **A. A Zener diode**  ←
- B. A digital-to-analog converter
- C. An SCR
- D. An analog-to-digital converter

**E7D04**

Which of the following describes a three-terminal voltage regulator?

- A. A series current source
- **B. A series regulator**  ←
- C. A shunt regulator
- D. A shunt current source

**E7D05**

Which of the following types of linear voltage regulator operates by loading the unregulated voltage source?

- A. A constant current source
- B. A series regulator
- C. A shunt current source
- **D. A shunt regulator**  ←

**E7D06**

What is the purpose of Q1 in the circuit shown in Figure E7-2?

- A. It provides negative feedback to improve regulation
- B. It provides a constant load for the voltage source
- **C. It controls the current to keep the output voltage constant**  ←
- D. It provides regulation by switching or “chopping” the input DC voltage

**E7D07**

What is the purpose of C2 in the circuit shown in Figure E7-2?

- **A. It bypasses rectifier output ripple around D1**  ←
- B. It is a brute force filter for the output
- C. To prevent self-oscillation
- D. To provide fixed DC bias for Q1

**E7D08**

What type of circuit is shown in Figure E7-2?

- A. Switching voltage regulator
- B. Common emitter amplifier
- **C. Linear voltage regulator**  ←
- D. Common base amplifier

**E7D09**

How is battery operating time calculated?

- A. Average current divided by capacity in amp-hours
- B. Average current divided by internal resistance
- **C. Capacity in amp-hours divided by average current**  ←
- D. Internal resistance divided by average current

**E7D10**

Why is a switching type power supply less expensive and lighter than an equivalent linear power supply?

- A. The inverter design does not require an output filter circuit
- B. The control circuitry uses less current, therefore smaller heat sinks are required
- **C. The high frequency inverter design uses much smaller transformers and filter components for an equivalent power output**  ←
- D. It recovers power from the unused portion of the AC cycle, thus using fewer components

**E7D11**

What is the purpose of an inverter connected to a solar panel output?

- A. Reduce AC ripple on the output
- B. Maintain voltage with varying illumination levels
- C. Prevent discharge when panel is not illuminated
- **D. Convert the panel’s output from DC to AC**  ←

**E7D12**

What is the dropout voltage of a linear voltage regulator?

- A. Minimum input voltage for rated power dissipation
- B. Maximum output voltage drop when the input voltage is varied over its specified range
- **C. Minimum input-to-output voltage required to maintain regulation**  ←
- D. Maximum that the output voltage may decrease at rated load

**E7D13**

Which of the following calculates power dissipated by a series linear voltage regulator?

- A. Input voltage multiplied by input current
- B. Input voltage divided by output current
- **C. Voltage difference from input to output multiplied by output current**  ←
- D. Output voltage multiplied by output current

**E7D14**

What is the purpose of connecting equal-value resistors across power supply filter capacitors connected in series?

- A. Equalize the voltage across each capacitor
- B. Discharge the capacitors when voltage is removed
- C. Provide a minimum load on the supply
- **D. All these choices are correct**  ←

**E7D15**

What is the purpose of a step-start circuit in a high-voltage power supply?

- A. To provide a dual-voltage output for reduced power applications
- B. To compensate for variations of the incoming line voltage
- C. To prevent arcing across the input power switch or relay contacts
- **D. To allow the filter capacitors to charge gradually**  ←

---

## E7E — Modulation and demodulation: reactance, phase, and balanced modulators; detectors; mixers

*One exam question comes from this group. 11 questions in the pool.*

**Generating FM/PM.** FM phone signals are generated by **reactance modulation of a local
oscillator** — varying a reactive element (varying capacitance for PM/FM specifically) to shift the
oscillator's frequency in step with audio. A **reactance modulator produces PM or FM signals by
varying a capacitance**. On the receive side, a **frequency discriminator is a circuit for detecting
FM signals**.

**Generating SSB.** **One way to produce SSB is a balanced modulator followed by a filter** — the
filter method: generate double-sideband, then strip one sideband.

**Pre-emphasis / de-emphasis, the FM pair.** A **pre-emphasis network is added to an FM speech
channel to boost the higher audio frequencies** at the transmitter; the receiver applies the
complementary **de-emphasis**. **De-emphasis is used for compatibility with transmitters using phase
modulation** — a PM transmitter's output already looks like FM with built-in pre-emphasis, so the
receiver's de-emphasis matches it either way.

**Baseband.** “Baseband” is **the frequency range occupied by a message signal prior to
modulation** — the raw audio or data before it rides on a carrier.

**Mixers.** A mixer's output contains **the two input frequencies along with their sum and
difference frequencies** — that sum/difference pair is what makes frequency conversion possible.
Drive a mixer too hard and **spurious mixer products are generated** — overload distortion inside
the mixer itself, a classic strong-signal problem.

**Detectors.** A **diode envelope detector works by rectification and filtering of RF signals** —
simple AM demodulation. **SSB signals are demodulated with a product detector**, which needs a
locally-generated carrier (BFO) to reconstruct the missing carrier that SSB deliberately suppresses.

#### All 11 pool questions for E7E

**E7E01**

Which of the following can be used to generate FM phone signals?

- A. Balanced modulation of the audio amplifier
- **B. Reactance modulation of a local oscillator**  ←
- C. Reactance modulation of the final amplifier
- D. Balanced modulation of a local oscillator

**E7E02**

What is the function of a reactance modulator?

- A. Produce PM or FM signals by varying a resistance
- B. Produce AM signals by varying an inductance
- C. Produce AM signals by varying a resistance
- **D. Produce PM or FM signals by varying a capacitance**  ←

**E7E03**

What is a frequency discriminator?

- A. An FM generator circuit
- B. A circuit for filtering closely adjacent signals
- C. An automatic band-switching circuit
- **D. A circuit for detecting FM signals**  ←

**E7E04**

What is one way to produce a single-sideband phone signal?

- **A. Use a balanced modulator followed by a filter**  ←
- B. Use a reactance modulator followed by a mixer
- C. Use a loop modulator followed by a mixer
- D. Use a product detector with a DSB signal

**E7E05**

What is added to an FM speech channel to boost the higher audio frequencies?

- A. A de-emphasis network
- B. A harmonic enhancer
- C. A heterodyne enhancer
- **D. A pre-emphasis network**  ←

**E7E06**

Why is de-emphasis used in FM communications receivers?

- **A. For compatibility with transmitters using phase modulation**  ←
- B. To reduce impulse noise reception
- C. For higher efficiency
- D. To remove third-order distortion products

**E7E07**

What is meant by the term “baseband” in radio communications?

- A. The lowest frequency band that the transmitter or receiver covers
- **B. The frequency range occupied by a message signal prior to modulation**  ←
- C. The unmodulated bandwidth of the transmitted signal
- D. The basic oscillator frequency in an FM transmitter that is multiplied to increase the deviation and carrier frequency

**E7E08**

What are the principal frequencies that appear at the output of a mixer?

- A. Two and four times the input frequency
- B. The square root of the product of input frequencies
- **C. The two input frequencies along with their sum and difference frequencies**  ←
- D. 1.414 and 0.707 times the input frequency

**E7E09**

What occurs when the input signal levels to a mixer are too high?

- **A. Spurious mixer products are generated**  ←
- B. Mixer blanking occurs
- C. Automatic limiting occurs
- D. Excessive AGC voltage levels are generated

**E7E10**

How does a diode envelope detector function?

- **A. By rectification and filtering of RF signals**  ←
- B. By breakdown of the Zener voltage
- C. By mixing signals with noise in the transition region of the diode
- D. By sensing the change of reactance in the diode with respect to frequency

**E7E11**

Which type of detector is used for demodulating SSB signals?

- A. Discriminator
- B. Phase detector
- **C. Product detector**  ←
- D. Phase comparator

---

## E7F — Software defined radio fundamentals: digital signal processing (DSP) filtering, modulation, and demodulation; analog-digital conversion; digital filters

*One exam question comes from this group. 14 questions in the pool.*

**Direct sampling.** “Direct sampling” means **incoming RF is digitized by an analog-to-digital
converter without being mixed with a local oscillator signal** — no analog IF stage at all, the ADC
sees the RF spectrum directly.

**DSP filters, matched to their job.** An **adaptive filter removes unwanted noise from a received
SSB signal**, continuously adjusting itself to the noise environment. A **Hilbert-transform filter
generates an SSB signal**, by producing a 90-degree-shifted version of the audio; equivalently, the
DSP method for generating SSB is described as **signals combined in quadrature phase relationship**
— that is the phasing method done in software.

**Sampling theory.** An analog signal must be sampled **at least twice the rate of its highest
frequency component** to be accurately reproduced — the Nyquist rate. Resolving a 1-volt range to
1-millivolt steps needs **10 bits** (2¹⁰ = 1024 levels, enough to cover 1000 one-millivolt steps).

**Frequency-domain tools.** A **Fast Fourier Transform converts signals from the time domain to the
frequency domain**. **Decimation reduces the effective sample rate by removing samples** — used to
narrow bandwidth and reduce processing load after the signal has already been filtered down. An
**anti-aliasing filter is required in a decimator because it removes high-frequency signal
components that would otherwise be reproduced as (aliased into) lower frequency components** once
the sample rate is reduced.

**SDR performance limits.** **Sample rate determines the maximum receive bandwidth** of a
direct-sampling SDR. In the absence of atmospheric or thermal noise, the **minimum detectable signal
level is set by the reference voltage level and the sample width in bits** — the ADC's own
quantization noise floor becomes the limiting factor.

**FIR filters and taps.** **FIR (Finite Impulse Response) filters can delay all frequency components
of the signal by the same amount** — linear phase, a key advantage over analog or IIR designs.
**Taps in a DSP filter provide incremental signal delays for the filter algorithm**, and **more taps
allow a DSP filter to create a sharper filter response**.

#### All 14 pool questions for E7F

**E7F01**

What is meant by “direct sampling” in software defined radios?

- A. Software is converted from source code to object code during operation of the receiver
- B. I and Q signals are generated by digital processing without the use of RF amplification
- **C. Incoming RF is digitized by an analog-to-digital converter without being mixed with a local oscillator signal**  ←
- D. A switching mixer is used to generate I and Q signals directly from the RF input

**E7F02**

What kind of digital signal processing audio filter is used to remove unwanted noise from a received SSB signal?

- **A. An adaptive filter**  ←
- B. A crystal-lattice filter
- C. A Hilbert-transform filter
- D. A phase-inverting filter

**E7F03**

What type of digital signal processing filter is used to generate an SSB signal?

- A. An adaptive filter
- B. A notch filter
- **C. A Hilbert-transform filter**  ←
- D. An elliptical filter

**E7F04**

Which method generates an SSB signal using digital signal processing?

- A. Mixing products are converted to voltages and subtracted by adder circuits
- B. A frequency synthesizer removes unwanted sidebands
- C. Varying quartz crystal characteristics are emulated in digital form
- **D. Signals are combined in quadrature phase relationship**  ←

**E7F05**

How frequently must an analog signal be sampled to be accurately reproduced?

- A. At least half the rate of the highest frequency component of the signal
- **B. At least twice the rate of the highest frequency component of the signal**  ←
- C. At the same rate as the highest frequency component of the signal
- D. At four times the rate of the highest frequency component of the signal

**E7F06**

What is the minimum number of bits required to sample a signal with a range of 1 volt at a resolution of 1 millivolt?

- A. 4 bits
- B. 6 bits
- C. 8 bits
- **D. 10 bits**  ←

**E7F07**

What function is performed by a Fast Fourier Transform?

- A. Converting analog signals to digital form
- B. Converting digital signals to analog form
- **C. Converting signals from the time domain to the frequency domain**  ←
- D. Converting signals from the frequency domain to the time domain

**E7F08**

What is the function of decimation?

- A. Converting data to binary-coded decimal form
- **B. Reducing the effective sample rate by removing samples**  ←
- C. Attenuating the signal
- D. Removing unnecessary significant digits

**E7F09**

Why is an anti-aliasing filter required in a decimator?

- **A. It removes high-frequency signal components that would otherwise be reproduced as lower frequency components**  ←
- B. It peaks the response of the decimator, improving bandwidth
- C. It removes low-frequency signal components to eliminate the need for DC restoration
- D. It notches out the sampling frequency to avoid sampling errors

**E7F10**

What aspect of receiver analog-to-digital conversion determines the maximum receive bandwidth of a direct-sampling software defined radio (SDR)?

- **A. Sample rate**  ←
- B. Sample width in bits
- C. Integral non-linearity
- D. Differential non-linearity

**E7F11**

What sets the minimum detectable signal level for a direct-sampling software defined receiver in the absence of atmospheric or thermal noise?

- A. Sample clock phase noise
- **B. Reference voltage level and sample width in bits**  ←
- C. Data storage transfer rate
- D. Missing codes and jitter

**E7F12**

Which of the following is generally true of Finite Impulse Response (FIR) filters?

- **A. FIR filters can delay all frequency components of the signal by the same amount**  ←
- B. FIR filters are easier to implement for a given set of passband rolloff requirements
- C. FIR filters can respond faster to impulses
- D. All these choices are correct

**E7F13**

What is the function of taps in a digital signal processing filter?

- A. To reduce excess signal pressure levels
- B. Provide access for debugging software
- C. Select the point at which baseband signals are generated
- **D. Provide incremental signal delays for filter algorithms**  ←

**E7F14**

Which of the following would allow a digital signal processing filter to create a sharper filter response?

- A. Higher data rate
- **B. More taps**  ←
- C. Lower Q
- D. Double-precision math routines

---

## E7G — Operational amplifiers: characteristics and applications

*One exam question comes from this group. 12 questions in the pool.*

**The two impedance facts, memorized as a pair.** An op-amp's **typical output impedance is very
low**; its **typical input impedance is very high**. That pairing is what makes an op-amp such a
clean building block — it barely loads its source and barely sags under its load.

**Filter behavior from feedback.** Adding a **capacitor across the feedback resistor of an inverting
op-amp stage turns it into a low-pass filter** — the capacitor shorts out high-frequency gain as
frequency rises.

**Vocabulary.** **Input offset voltage is the differential input voltage needed to bring the
open-loop output voltage to zero** — a real op-amp isn't perfectly balanced, and this is the input
mismatch that corrects for it. **Gain-bandwidth is the frequency at which the open-loop gain of the
amplifier equals one** (unity) — every op-amp has one, and it is the ceiling on gain × bandwidth for
any feedback configuration built from it.

**Stability in active filters.** To prevent unwanted ringing and audio instability in an op-amp audio
filter, **restrict both gain and Q** — pushing either one too high invites peaking and oscillation.

**Ideal op-amp assumption.** By definition, an **ideal operational amplifier's gain does not vary
with frequency** — the idealization the “gain-bandwidth” concept above exists to correct for in real
devices.

**Gain arithmetic — this is the one place E7 asks you to compute.** For the inverting amplifier of
Figure E7-3, gain magnitude = RF / R1:

| R1 | RF | Gain (RF ÷ R1) |
|---|---|---|
| 10 Ω | 470 Ω | **47** |
| 1,800 Ω | 68 kΩ | **38** |
| 3,300 Ω | 47 kΩ | **14** |
| 1,000 Ω | 10,000 Ω | **10**, applied to 0.23 V in → **−2.3 V** out (inverting stage flips the sign) |

**Definition.** An **operational amplifier is a high-gain, direct-coupled differential amplifier
with very high input impedance and very low output impedance** — the textbook definition, and just
the two impedance facts above stated together.

#### All 12 pool questions for E7G

**E7G01**

What is the typical output impedance of an op-amp?

- **A. Very low**  ←
- B. Very high
- C. 100 ohms
- D. 10,000 ohms

**E7G02**

What is the frequency response of the circuit in E7-3 if a capacitor is added across the feedback resistor?

- A. High-pass filter
- **B. Low-pass filter**  ←
- C. Band-pass filter
- D. Notch filter

**E7G03**

What is the typical input impedance of an op-amp?

- A. 100 ohms
- B. 10,000 ohms
- C. Very low
- **D. Very high**  ←

**E7G04**

What is meant by the term “op-amp input offset voltage”?

- A. The output voltage of the op-amp minus its input voltage
- B. The difference between the output voltage of the op-amp and the input voltage required in the immediately following stage
- **C. The differential input voltage needed to bring the open loop output voltage to zero**  ←
- D. The potential between the amplifier input terminals of the op-amp in an open loop condition

**E7G05**

How can unwanted ringing and audio instability be prevented in an op-amp audio filter?

- **A. Restrict both gain and Q**  ←
- B. Restrict gain but increase Q
- C. Restrict Q but increase gain
- D. Increase both gain and Q

**E7G06**

What is the gain-bandwidth of an operational amplifier?

- A. The maximum frequency for a filter circuit using that type of amplifier
- **B. The frequency at which the open-loop gain of the amplifier equals one**  ←
- C. The gain of the amplifier at a filter’s cutoff frequency
- D. The frequency at which the amplifier’s offset voltage is zero

**E7G07**

What voltage gain can be expected from the circuit in Figure E7-3 when R1 is 10 ohms and RF is 470 ohms?

- A. 0.21
- B. 4700
- **C. 47**  ←
- D. 24

**E7G08**

How does the gain of an ideal operational amplifier vary with frequency?

- A. It increases linearly with increasing frequency
- B. It decreases linearly with increasing frequency
- C. It decreases logarithmically with increasing frequency
- **D. It does not vary with frequency**  ←

**E7G09**

What will be the output voltage of the circuit shown in Figure E7-3 if R1 is 1,000 ohms, RF is 10,000 ohms, and 0.23 volts DC is applied to the input?

- A. 0.23 volts
- B. 2.3 volts
- C. -0.23 volts
- **D. -2.3 volts**  ←

**E7G10**

What absolute voltage gain can be expected from the circuit in Figure E7-3 when R1 is 1,800 ohms and RF is 68 kilohms?

- A. 1
- B. 0.03
- **C. 38**  ←
- D. 76

**E7G11**

What absolute voltage gain can be expected from the circuit in Figure E7-3 when R1 is 3,300 ohms and RF is 47 kilohms?

- A. 28
- **B. 14**  ←
- C. 7
- D. 0.07

**E7G12**

What is an operational amplifier?

- **A. A high-gain, direct-coupled differential amplifier with very high input impedance and very low output impedance**  ←
- B. A digital audio amplifier whose characteristics are determined by components external to the amplifier
- C. An amplifier used to increase the average output of frequency modulated amateur signals to the legal limit
- D. A RF amplifier used in the UHF and microwave regions

---

## E7H — Oscillators and signal sources: types of oscillators; synthesizers and phase-locked loops; direct digital synthesizers; stabilizing thermal drift; microphonics; high-accuracy oscillators

*One exam question comes from this group. 13 questions in the pool.*

**Three named oscillators, three feedback paths.** The **three common oscillator circuits are
Colpitts, Hartley, and Pierce**. **Colpitts supplies positive feedback through a capacitive
divider** (split capacitors set the feedback fraction). **Pierce supplies positive feedback through a
quartz crystal** — the crystal itself is the feedback/frequency-determining element, which is why
Pierce oscillators are the standard crystal-oscillator topology.

**Microphonics.** A **microphonic is a change in oscillator frequency caused by mechanical
vibration** — physical shock or vibration flexing components and pulling the frequency. It is
reduced by **mechanically isolating the oscillator circuitry from its enclosure**, cutting the
vibration path rather than chasing it electrically.

**Thermal drift.** **NP0 (COG) capacitors reduce thermal drift in crystal oscillators** — their
near-zero temperature coefficient keeps the oscillator's frequency-determining capacitance from
sliding as the circuit warms up.

**Phase-locked loops.** A **PLL is an electronic servo loop consisting of a phase detector, a
low-pass filter, a voltage-controlled oscillator, and a stable reference oscillator**. Its two
signature jobs are **frequency synthesis and FM demodulation** — the same servo loop that locks a
VCO to a reference can also track an FM signal's instantaneous frequency and output the recovered
audio.

**Direct digital synthesis (DDS).** A **DDS uses a phase accumulator, a lookup table, a
digital-to-analog converter, and a low-pass anti-alias filter**. The **lookup table holds amplitude
values that represent the desired waveform** — a phase value steps through the table, and the table
returns the corresponding amplitude sample. DDS's characteristic weakness is **spurious signals at
discrete frequencies** — clean broadband noise it is not; instead it produces spurs at specific,
predictable frequencies tied to the clock and accumulator math.

**Keeping a crystal on its rated frequency.** A crystal oscillates at the frequency printed on the
can only if it is **provided with the specified parallel (load) capacitance** the manufacturer
designed it against — change the load capacitance and the crystal pulls off frequency.

**Microwave-grade accuracy.** For highly accurate and stable oscillators at microwave frequencies,
the accepted techniques are **a GPS signal reference, a rubidium-stabilized reference oscillator, or
a temperature-controlled high-Q dielectric resonator** — the pool's answer is “all these choices are
correct.”

#### All 13 pool questions for E7H

**E7H01**

What are three common oscillator circuits?

- A. Taft, Pierce, and negative feedback
- B. Pierce, Fenner, and Beane
- C. Taft, Hartley, and Pierce
- **D. Colpitts, Hartley, and Pierce**  ←

**E7H02**

What is a microphonic?

- A. An IC used for amplifying microphone signals
- B. Distortion caused by RF pickup on the microphone cable
- **C. Changes in oscillator frequency caused by mechanical vibration**  ←
- D. Excess loading of the microphone by an oscillator

**E7H03**

What is a phase-locked loop?

- A. An electronic servo loop consisting of a ratio detector, reactance modulator, and voltage-controlled oscillator
- B. An electronic circuit also known as a monostable multivibrator
- **C. An electronic servo loop consisting of a phase detector, a low-pass filter, a voltage-controlled oscillator, and a stable reference oscillator**  ←
- D. An electronic circuit consisting of a precision push-pull amplifier with a differential phase input

**E7H04**

How is positive feedback supplied in a Colpitts oscillator?

- A. Through a tapped coil
- B. Through link coupling
- **C. Through a capacitive divider**  ←
- D. Through a neutralizing capacitor

**E7H05**

How is positive feedback supplied in a Pierce oscillator?

- A. Through a tapped coil
- B. Through link coupling
- C. Through a neutralizing capacitor
- **D. Through a quartz crystal**  ←

**E7H06**

Which of these functions can be performed by a phase-locked loop?

- A. Wide-band AF and RF power amplification
- **B. Frequency synthesis and FM demodulation**  ←
- C. Photovoltaic conversion and optical coupling
- D. Comparison of two digital input signals and digital pulse counting

**E7H07**

How can an oscillator’s microphonic responses be reduced?

- A. Use NP0 capacitors
- B. Reduce noise on the oscillator’s power supply
- C. Increase the gain
- **D. Mechanically isolate the oscillator circuitry from its enclosure**  ←

**E7H08**

Which of the following components can be used to reduce thermal drift in crystal oscillators?

- **A. NP0 capacitors**  ←
- B. Toroidal inductors
- C. Wirewound resistors
- D. Non-inductive resistors

**E7H09**

What type of frequency synthesizer circuit uses a phase accumulator, lookup table, digital-to-analog converter, and a low-pass anti-alias filter?

- **A. A direct digital synthesizer**  ←
- B. A hybrid synthesizer
- C. A phase-locked loop synthesizer
- D. A direct conversion synthesizer

**E7H10**

What information is contained in the lookup table of a direct digital synthesizer (DDS)?

- A. The phase relationship between a reference oscillator and the output waveform
- **B. Amplitude values that represent the desired waveform**  ←
- C. The phase relationship between a voltage-controlled oscillator and the output waveform
- D. Frequently used receiver and transmitter frequencies

**E7H11**

What are the major spectral impurity components of direct digital synthesizers?

- A. Broadband noise
- B. Digital conversion noise
- **C. Spurious signals at discrete frequencies**  ←
- D. Harmonics of the local oscillator

**E7H12**

Which of the following ensures that a crystal oscillator operates on the frequency specified by the crystal manufacturer?

- A. Provide the crystal with a specified parallel inductance
- **B. Provide the crystal with a specified parallel capacitance**  ←
- C. Bias the crystal at a specified voltage
- D. Bias the crystal at a specified current

**E7H13**

Which of the following is a technique for providing highly accurate and stable oscillators needed for microwave transmission and reception?

- A. Use a GPS signal reference
- B. Use a rubidium stabilized reference oscillator
- C. Use a temperature-controlled high Q dielectric resonator
- **D. All these choices are correct**  ←

---

## Bottom line for E7

**Flip-flop = bistable; monostable = one-shot; astable = free-running.** One flip-flop halves a
frequency, so 16 needs **4**. NAND is 0 only when all inputs are 1; XNOR is 0 when exactly one input
is 1. **Class AB conducts 180–360°**, Class A sits at the **midpoint of the load line**, and Class C
on SSB means **distortion and splatter**. RF switching amps need a **harmonic filter**. Low-pass Pi:
**C-L-C**; Pi-L adds a **series output inductor** for more suppression. Chebyshev has **passband
ripple**, elliptical has **stopband notches**. Linear regulators **vary a pass element's conduction**
and dissipate **(Vin−Vout)×Iout**; switchers **vary duty cycle** and win on size because of
**high-frequency transformers**. Dropout voltage is the **minimum headroom to stay regulated**. FM is
made with **reactance modulation** of an oscillator; SSB with a **balanced modulator plus filter** or
**quadrature combining**; mixers output **sum and difference**; SSB is recovered with a **product
detector**. Direct sampling means **no LO ahead of the ADC**; Nyquist needs **2× the highest
frequency**; **more taps = sharper** DSP filters. Op-amps have **low output, high input impedance**;
inverting gain is **RF/R1**; adding **C across the feedback resistor makes a low-pass**. Oscillators:
**Colpitts = capacitive divider, Pierce = crystal**; **NP0 caps** fight thermal drift; a **PLL** is a
phase detector, filter, VCO, and reference; **DDS** spurs are **discrete, not broadband**.
