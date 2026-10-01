# T7 — Practical Circuits

**4 of your 35 exam questions · 4 groups (T7A–T7D) · 44 questions in the pool**

This subelement is where the exam turns from rules and theory to the actual gear on your desk: what
the parts of a station do, what goes wrong with a transmitter or receiver and how you fix it, how you
measure and troubleshoot an antenna system, and how you use a basic voltmeter/ammeter/ohmmeter and a
soldering iron. It's the largest Technician subelement by question count, but also one of the
lightest to prepare for — almost nothing here is math, and most items are a single practical term
matched to a single plain-English definition or a common-sense troubleshooting step.

## Table of Contents

- [T7A — Station equipment: receivers, transceivers, transmitter amplifiers, RF preamplifiers, transverters; Basic radio circuit concepts and terminology: sensitivity, selectivity, mixers, oscillators, Push-To-Talk (PTT), VFO, modulation](#t7a--station-equipment-receivers-transceivers-transmitter-amplifiers-rf-preamplifiers-transverters-basic-radio-circuit-concepts-and-terminology-sensitivity-selectivity-mixers-oscillators-push-to-talk-ptt-vfo-modulation)
  - [All 11 pool questions for T7A](#all-11-pool-questions-for-t7a)
- [T7B — Symptoms, causes, and cures of common transmitter and receiver problems: overload and overdrive, distortion, interference and consumer electronics, RF feedback](#t7b--symptoms-causes-and-cures-of-common-transmitter-and-receiver-problems-overload-and-overdrive-distortion-interference-and-consumer-electronics-rf-feedback)
  - [All 11 pool questions for T7B](#all-11-pool-questions-for-t7b)
- [T7C — Antenna and transmission line measurements and troubleshooting: measuring SWR, effects of high SWR, causes of feed line failures; Basic coaxial cable characteristics; Use of dummy loads when testing](#t7c--antenna-and-transmission-line-measurements-and-troubleshooting-measuring-swr-effects-of-high-swr-causes-of-feed-line-failures-basic-coaxial-cable-characteristics-use-of-dummy-loads-when-testing)
  - [All 11 pool questions for T7C](#all-11-pool-questions-for-t7c)
- [T7D — Using basic test instruments: voltmeter, ammeter, and ohmmeter; Soldering](#t7d--using-basic-test-instruments-voltmeter-ammeter-and-ohmmeter-soldering)
  - [All 11 pool questions for T7D](#all-11-pool-questions-for-t7d)

---

## T7A — Station equipment: receivers, transceivers, transmitter amplifiers, RF preamplifiers, transverters; Basic radio circuit concepts and terminology: sensitivity, selectivity, mixers, oscillators, Push-To-Talk (PTT), VFO, modulation

*One exam question comes from this group. 11 questions in the pool.*

**Sensitivity vs. selectivity, the classic pair:** **sensitivity** is a receiver's ability to
**detect the presence of a signal** (pull in weak stations); **selectivity** is its ability to
**discriminate between multiple signals** (reject everything next to the one you want). A
**transceiver** simply **combines a receiver and transmitter** in one unit. A **mixer converts a
signal from one frequency to another**, while an **oscillator generates a signal at a specific
frequency** — the mixer moves a signal, the oscillator makes one. A **transverter converts the RF
input and output of a transceiver to another band** (RF = radio frequency) entirely.

**Controls and add-ons.** A transceiver's **PTT input switches it from receive to transmit when
grounded**. An **RF power amplifier** can be added to a transceiver's output to **increase the
transmitted output power**. On some VHF (very high frequency) power amplifiers, the **SSB/CW-FM mode switch sets the
amplifier for proper operation in the selected mode** (SSB = single sideband) — it isn't changing the transmitted signal's
mode itself or shifting the amplifier's frequency range, just biasing/configuring the amp correctly
for how it's being driven. The **VFO (Variable Frequency Oscillator) sets the receive and transmit
frequency** of a transceiver. Finally, **modulation is combining speech (or other information) with
an RF carrier signal** for transmission.

#### All 11 pool questions for T7A

**T7A01**

Which term describes the ability of a receiver to detect the presence of a signal?

- A. RF gain
- B. Sensitivity
- C. Selectivity
- D. Total Harmonic Distortion
-
- Answer: B

**T7A02**

What is a transceiver?

- A. A device that combines a receiver and transmitter
- B. A device for matching feed line impedance to 50 ohms
- C. A device for automatically sending and decoding Morse code
- D. A device for converting receiver and transmitter frequencies to another band
-
- Answer: A

**T7A03**

Which of the following is used to convert a signal from one frequency to another?

- A. Phase splitter
- B. Mixer
- C. Inverter
- D. Amplifier
-
- Answer: B

**T7A04**

Which term describes the ability of a receiver to discriminate between multiple signals?

- A. Discrimination ratio
- B. Sensitivity
- C. Selectivity
- D. Harmonic distortion
-
- Answer: C

**T7A05**

What is the name of a circuit that generates a signal at a specific frequency?

- A. Reactance modulator
- B. Phase modulator
- C. Low-pass filter
- D. Oscillator
-
- Answer: D

**T7A06**

What device converts the RF input and output of a transceiver to another band?

- A. High-pass filter
- B. Low-pass filter
- C. Transverter
- D. Phase converter
-
- Answer: C

**T7A07**

What is the function of a transceiver's PTT input?

- A. Input for a key used to send CW
- B. Switches transceiver from receive to transmit when grounded
- C. Provides a transmit tuning tone when grounded
- D. Input for a preamplifier tuning tone
-
- Answer: B

**T7A08**

Which of the following describes combining speech with an RF carrier signal?

- A. Impedance matching
- B. Oscillation
- C. Modulation
- D. Low-pass filtering
-
- Answer: C

**T7A09**

What is the function of the switch which selects either SSB or CW-FM on some VHF power amplifiers?

- A. Change the mode of the transmitted signal
- B. Set the amplifier for proper operation in the selected mode
- C. Change the frequency range of the amplifier to operate in the proper segment of the band
- D. Reduce the received signal noise
-
- Answer: B

**T7A10**

What can be added to the output of a transceiver to increase the transmitted output power?

- A. A potentiometer
- B. An RF power amplifier
- C. An impedance multiplier
- D. All these choices are correct
-
- Answer: B

**T7A11**

What is the function of the Variable Frequency Oscillator (VFO) circuit in a transceiver?

- A. Set the receive and transmit frequency
- B. Provide automatic frequency control
- C. Inject a variable frequency to allow CW reception
- D. Generate and demodulate single sideband signals
-
- Answer: A

---

## T7B — Symptoms, causes, and cures of common transmitter and receiver problems: overload and overdrive, distortion, interference and consumer electronics, RF feedback

*One exam question comes from this group. 11 questions in the pool.*

**Fixing your own transmit audio.** If told your FM (frequency modulation) handheld or mobile is **over-deviating**, **talk
farther away from the microphone**. If a report says your FM repeater audio is **distorted or
unintelligible**, the cause could be off-frequency, too-loud/too-close mic technique, or a bad
location — **all these choices are correct**. To **eliminate distorted voice transmissions** caused
by RF getting into the audio chain, add a **clip-on ferrite "choke" to the microphone cable** to stop
the transmitted signal from feeding back into the transmitter (classic **RF feedback** fix).

**Diagnosing low power and interference causes.** **Low RF power output** from a solid-state
transceiver is often caused by **high SWR** (SWR = standing wave ratio). **Radio frequency interference** in general can come
from **fundamental overload, harmonics, or spurious emissions** — **all these choices are correct**.
When a **broadcast AM/FM radio unintentionally receives a ham transmission** (AM = amplitude modulation), the fault is on the
victim's end: **the receiver is unable to reject strong signals outside the AM or FM band**
(fundamental overload of that receiver), not anything wrong with your transmitter.

**Curing interference to others and from others.** To reduce interference *from* your station to a
nearby non-amateur receiver, **block the amateur signal with a filter at the antenna input of the
affected receiver**. If a neighbor reports your transmissions interfere with their radio/TV (television), first
**make sure your own station is functioning properly and doesn't interfere with your own radio or TV**
when tuned to the same channel — good amateur practice starts with checking yourself. To reduce
interference to a **2-meter transceiver from a nearby commercial FM station**, install a **band-reject
filter**. If something in a **neighbor's home** is causing harmful interference to *your* station,
work with the neighbor, remind them (politely) of FCC (Federal Communications Commission) rules, and make sure your own station meets
good-practice standards — again **all these choices are correct**. For non-fiber-optic **cable TV
interference**, the first step is to **be sure all TV feed line coaxial connectors are installed
properly** — a loose or poorly shielded connector is the most common real-world culprit.

#### All 11 pool questions for T7B

**T7B01**

What can you do if you are told your FM handheld or mobile transceiver is over-deviating?

- A. Talk louder into the microphone
- B. Let the transceiver cool off
- C. Change to a higher power level
- D. Talk farther away from the microphone
-
- Answer: D

**T7B02**

What would cause a broadcast AM or FM radio to receive an amateur radio transmission unintentionally?

- A. The receiver is unable to reject strong signals outside the AM or FM band
- B. The microphone gain of the transmitter is turned up too high
- C. The audio amplifier of the transmitter is overloaded
- D. The deviation of an FM transmitter is set too low
-
- Answer: A

**T7B03**

Which of the following can cause radio frequency interference?

- A. Fundamental overload
- B. Harmonics
- C. Spurious emissions
- D. All these choices are correct
-
- Answer: D

**T7B04**

Which of the following might be the cause of low RF power output from a solid-state transceiver?

- A. Poor amplifier noise figure
- B. Poor amplifier linearity
- C. Low SWR
- D. High SWR
-
- Answer: D

**T7B05**

Which of the following might reduce interference by an amateur station to a non-amateur over-the-air radio receiver?

- A. Block the amateur signal with a filter at the antenna input of the affected receiver
- B. Block the interfering signal with a filter on the amateur transmitter
- C. Switch the transmitter from FM to SSB
- D. Switch the transmitter to a narrow-band mode
-
- Answer: A

**T7B06**

Which of the following actions should you take if a neighbor tells you that your station's transmissions are interfering with their radio or TV reception?

- A. Make sure that your station is functioning properly and that it does not cause interference to your own radio or television when it is tuned to the same channel
- B. Immediately turn off your transmitter and contact the nearest FCC office for assistance
- C. Install a harmonic doubler on the output of your transmitter and tune it until the interference is eliminated
- D. All these choices are correct
-
- Answer: A

**T7B07**

Which of the following can reduce interference to a 2-meter band transceiver from a nearby commercial FM station?

- A. Installing an RF preamplifier
- B. Using double-shielded coaxial cable
- C. Installing bypass capacitors on the microphone cable
- D. Installing a band-reject filter
-
- Answer: D

**T7B08**

What should you do if something in a neighbor's home is causing harmful interference to your amateur station?

- A. Work with your neighbor to identify the offending device
- B. Politely inform your neighbor that FCC rules prohibit the use of devices that cause interference
- C. Make sure your station meets the standards of good amateur practice
- D. All these choices are correct
-
- Answer: D

**T7B09**

What should be the first step to resolve non-fiber optic cable TV interference caused by your amateur radio transmission?

- A. Add a low-pass filter to the TV antenna input
- B. Add a high-pass filter to the TV antenna input
- C. Add a preamplifier to the TV antenna input
- D. Be sure all TV feed line coaxial connectors are installed properly
-
- Answer: D

**T7B10**

What might be a problem if you receive a report that your audio signal through an FM repeater is distorted or unintelligible?

- A. Your transmitter is slightly off frequency
- B. You are speaking too loudly or too close to the microphone
- C. You are in a bad location
- D. All these choices are correct
-
- Answer: D

**T7B11**

Which of the following can eliminate distorted voice transmissions?

- A. Adding extra feedline to the antenna to lower SWR
- B. Turning the radio on and off to reset the computer-controlled circuitry
- C. Adding a clip-on ferrite "choke" to the microphone cable to prevent the transmitted signal from feeding back into the transmitter
- D. Turning the squelch control fully clockwise to prevent the transmitted signal from triggering the squelch circuit
-
- Answer: C

---

## T7C — Antenna and transmission line measurements and troubleshooting: measuring SWR, effects of high SWR, causes of feed line failures; Basic coaxial cable characteristics; Use of dummy loads when testing

*One exam question comes from this group. 11 questions in the pool.*

**Dummy loads.** The primary purpose of a dummy load is **to prevent transmitting signals over the
air when making tests** — it lets you key up without putting a signal on the antenna. A typical RF (radio frequency)
dummy load is **a 50-ohm non-inductive resistor mounted on a heat sink**, which safely dissipates the
transmitter's power as heat instead of radiating it.

**SWR basics.** An **antenna analyzer** is used to determine whether an antenna is resonant at the
desired frequency. On an **SWR meter**, a reading of **1:1 indicates a perfect impedance match**
between antenna and feed line; a reading of **4:1 indicates an impedance mismatch**. Most solid-state
transmitters **reduce output power as SWR increases** beyond a certain level **to protect the RF
output amplifier transistors** — this is self-protection, not an FCC (Federal Communications Commission) spectral-purity requirement.
Power lost in a feed line **is converted into heat**, not radiated as harmonics or otherwise. The
instrument used to determine SWR (standing wave ratio) is a **directional wattmeter**.

**Coaxial cable care.** Coax cable failure is commonly caused by **moisture contamination** —
water getting into the line raises loss and can corrode the conductors. That's also why the outer
jacket should resist ultraviolet light: **UV light can damage the jacket and allow water to enter the
cable**, not because UV interacts electrically with the signal. An advantage of **foam-dielectric**
coax over solid-dielectric coax is that it **has less loss per foot**.

#### All 11 pool questions for T7C

**T7C01**

What is the primary purpose of a dummy load?

- A. To prevent transmitting signals over the air when making tests
- B. To prevent over-modulation of a transmitter
- C. To improve the efficiency of an antenna
- D. To improve the signal-to-noise ratio of a receiver
-
- Answer: A

**T7C02**

Which of the following is used to determine if an antenna is resonant at the desired operating frequency?

- A. A VTVM
- B. An antenna analyzer
- C. A Q meter
- D. A frequency counter
-
- Answer: B

**T7C03**

What does a typical RF dummy load consist of?

- A. A low-voltage power supply and an AC relay
- B. A 50-ohm non-inductive resistor mounted on a heat sink
- C. A low-voltage power supply and a DC relay
- D. A 50-ohm inductive reactance mounted in a shielded enclosure
-
- Answer: B

**T7C04**

What reading on an SWR meter indicates a perfect impedance match between the antenna and the feed line?

- A. 50:50
- B. Zero
- C. 1:1
- D. Full Scale
-
- Answer: C

**T7C05**

Why do most solid-state transmitters reduce output power as SWR increases beyond a certain level?

- A. To protect the RF output amplifier transistors
- B. To comply with FCC rules on spectral purity
- C. Because power supplies cannot supply enough current at high SWR
- D. To lower the SWR on the transmission line
-
- Answer: A

**T7C06**

What does an SWR reading of 4:1 indicate?

- A. Loss of -4 dB
- B. Good impedance match
- C. Gain of +4 dB
- D. Impedance mismatch
-
- Answer: D

**T7C07**

What happens to power lost in a feed line?

- A. It increases the SWR
- B. It is radiated as harmonics
- C. It is converted into heat
- D. It distorts the signal
-
- Answer: C

**T7C08**

Which instrument can be used to determine SWR?

- A. Voltmeter
- B. Ohmmeter
- C. Iambic pentameter
- D. Directional wattmeter
-
- Answer: D

**T7C09**

Which of the following causes failure of coaxial cables?

- A. Moisture contamination
- B. Solder flux contamination
- C. Rapid fluctuation in transmitter output power
- D. Operation at 100% duty cycle for an extended period
-
- Answer: A

**T7C10**

Why should the outer jacket of coaxial cable be resistant to ultraviolet light?

- A. Ultraviolet light can increase the resistance of the conductors
- B. Ultraviolet light can increase losses in the cable's jacket
- C. Ultraviolet and RF signals can mix, causing interference
- D. Ultraviolet light can damage the jacket and allow water to enter the cable
-
- Answer: D

**T7C11**

What is an advantage of foam-dielectric versus solid-dielectric coaxial cable?

- A. It is more resistant to moisture contamination
- B. It has higher voltage breakdown
- C. It has less loss per foot
- D. It has a better impedance match to 50 ohms
-
- Answer: C

---

## T7D — Using basic test instruments: voltmeter, ammeter, and ohmmeter; Soldering

*One exam question comes from this group. 11 questions in the pool.*

**Meters and how they're connected.** A **voltmeter measures electric potential** and is connected
**in parallel** with a component to measure applied voltage. An **ammeter measures electric current**,
and when a multimeter is configured to measure current it's connected **in series** with the
component. An **ohmmeter measures resistance by applying a small current and measuring the resulting
voltage** across the unknown. A multimeter can be **damaged by attempting to measure voltage while it's
set to the resistance setting** — the meter's own internal source meets an external voltage it wasn't
built to handle. A multimeter is used to measure **voltage and resistance** (the pool's correct answer
here is the specific pair, not "all these choices are correct").

**Ohmmeters and capacitors.** If an ohmmeter is connected across a large, discharged capacitor, you'll
see **increasing resistance with time** — the meter's small current charges the cap, so the apparent
resistance climbs as charging current tapers off. A key precaution when measuring **in-circuit
resistance** with an ohmmeter: **ensure that the circuit is not powered**, since an energized circuit
will feed current back into the meter and give a false (or damaging) reading.

**Soldering.** **Acid-core solder should not be used** for radio and electronic work — it's meant for
plumbing/sheet metal and its residue corrodes electronic joints; rosin-core is the right choice. A
**cold solder joint** has a characteristic **rough or lumpy surface**, in contrast to the smooth,
shiny surface of a good joint.

#### All 11 pool questions for T7D

**T7D01**

Which instrument would you use to measure electric potential?

- A. An ammeter
- B. A voltmeter
- C. A potentiometer
- D. An ohmmeter
-
- Answer: B

**T7D02**

How is a voltmeter connected to a component to measure applied voltage?

- A. In series
- B. In parallel
- C. In quadrature
- D. In phase
-
- Answer: B

**T7D03**

When configured to measure current, how is a multimeter connected to a component?

- A. In series
- B. In parallel
- C. In quadrature
- D. In phase
-
- Answer: A

**T7D04**

Which instrument is used to measure electric current?

- A. An ohmmeter
- B. An electrometer
- C. A voltmeter
- D. An ammeter
-
- Answer: D

**T7D05**

How does an ohmmeter measure the resistance of a circuit or component?

- A. By applying a small current and measuring the resulting voltage
- B. By placing a variable resistor in parallel with the circuit
- C. By placing a variable resistor in series with the circuit
- D. By applying a variable voltage and measuring the resulting current change
-
- Answer: A

**T7D06**

Which of the following can damage a multimeter?

- A. Attempting to measure resistance using the voltage setting
- B. Failing to connect one of the probes to ground
- C. Attempting to measure voltage when using the resistance setting
- D. Not allowing it to warm up properly
-
- Answer: C

**T7D07**

Which of the following measurements are made using a multimeter?

- A. Signal strength and noise
- B. Impedance and reactance
- C. Voltage and resistance
- D. All these choices are correct
-
- Answer: C

**T7D08**

Which of the following types of solder should not be used for radio and electronic applications?

- A. Acid-core solder
- B. Lead-tin solder
- C. Rosin-core solder
- D. Tin-copper solder
-
- Answer: A

**T7D09**

What is the characteristic appearance of a cold tin-lead solder joint?

- A. Dark black spots
- B. A bright or shiny surface
- C. A rough or lumpy surface
- D. A greenish tinge
-
- Answer: C

**T7D10**

What reading indicates that an ohmmeter is connected across a large, discharged capacitor?

- A. Increasing resistance with time
- B. Decreasing resistance with time
- C. Steady full-scale reading
- D. Alternating between open and short circuit
-
- Answer: A

**T7D11**

Which of the following precautions should be taken when measuring in-circuit resistance with an ohmmeter?

- A. Ensure that the applied voltages are correct
- B. Ensure that the circuit is not powered
- C. Ensure that the circuit is grounded
- D. Ensure that the circuit is operating at the correct frequency
-
- Answer: B
