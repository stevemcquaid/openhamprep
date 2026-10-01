# E4 — Amateur Practices

**5 of your 50 exam questions · 5 groups (E4A–E4E) · 63 questions in the pool**

E4 is the most technical, reasoning-heavy subelement in the Extra pool: test equipment, measurement
technique and its limitations, receiver performance, and the noise and interference that make or break
a station on a crowded band. Unlike a rules-and-numbers subelement, very little of this bank is pure
memorization — most questions reward understanding *why* an answer is correct, which also makes the
distractors easier to eliminate once the underlying concept clicks.

Read the concept notes before the questions in each group; they're written to make the terminology and
the physics predictable rather than to be memorized as standalone facts.

## Table of Contents

- [E4A — Test equipment: analog and digital instruments; spectrum analyzers; antenna analyzers; oscilloscopes; RF measurements](#e4a--test-equipment-analog-and-digital-instruments-spectrum-analyzers-antenna-analyzers-oscilloscopes-rf-measurements)
  - [All 11 pool questions for E4A](#all-11-pool-questions-for-e4a)
- [E4B — Measurement technique and limitations: instrument accuracy and performance limitations; probes; techniques to minimize errors; measurement of Q; instrument calibration; S parameters; vector network analyzers; RF signals](#e4b--measurement-technique-and-limitations-instrument-accuracy-and-performance-limitations-probes-techniques-to-minimize-errors-measurement-of-q-instrument-calibration-s-parameters-vector-network-analyzers-rf-signals)
  - [All 11 pool questions for E4B](#all-11-pool-questions-for-e4b)
- [E4C — Receiver performance: phase noise, noise floor, image rejection, minimum detectable signal (MDS), increasing signal-to-noise ratio and dynamic range, noise figure, reciprocal mixing; selectivity; SDR non-linearity; use of attenuators at low frequencies](#e4c--receiver-performance-phase-noise-noise-floor-image-rejection-minimum-detectable-signal-mds-increasing-signal-to-noise-ratio-and-dynamic-range-noise-figure-reciprocal-mixing-selectivity-sdr-non-linearity-use-of-attenuators-at-low-frequencies)
  - [All 14 pool questions for E4C](#all-14-pool-questions-for-e4c)
- [E4D — Receiver performance characteristics: dynamic range; intermodulation and cross-modulation interference; third-order intercept; desensitization; preselector; sensitivity; link margin](#e4d--receiver-performance-characteristics-dynamic-range-intermodulation-and-cross-modulation-interference-third-order-intercept-desensitization-preselector-sensitivity-link-margin)
  - [All 13 pool questions for E4D](#all-13-pool-questions-for-e4d)
- [E4E — Noise and interference: external RF interference; electrical and computer noise; line noise; DSP filtering and noise reduction; common-mode current; surge protectors; single point ground panel](#e4e--noise-and-interference-external-rf-interference-electrical-and-computer-noise-line-noise-dsp-filtering-and-noise-reduction-common-mode-current-surge-protectors-single-point-ground-panel)
  - [All 14 pool questions for E4E](#all-14-pool-questions-for-e4e)
- [Bottom line for E4](#bottom-line-for-e4)

---

## E4A — Test equipment: analog and digital instruments; spectrum analyzers; antenna analyzers; oscilloscopes; RF measurements

*One exam question comes from this group. 11 questions in the pool.*

E4A is instrument identification plus a handful of hands-on techniques — mostly straightforward
recall once you know what each piece of gear actually does. **Digital oscilloscopes are limited by the
sampling rate of their analog-to-digital converter**, not by circuit Q or ADC reference frequency;
sample too slowly and **aliasing** produces a false, jittery low-frequency ghost of the real waveform.
**Spectrum analyzers plot amplitude on the vertical axis and frequency on the horizontal** (a scope
plots amplitude vs. time) — that distinction is exactly why a spectrum analyzer, not a scope, is the
tool for viewing SSB (single sideband) spurious signals and intermodulation distortion products, which show up as
sidebands at specific frequencies rather than as time-domain distortion.

**Probe compensation** is done by displaying a square wave and trimming the probe until the top of the
wave is as flat as possible. Good probe technique also means **keeping the ground lead as short as
possible** to avoid ringing and inaccurate high-frequency readings. A **prescaler divides a high
frequency down** so that a slower frequency counter can display it. For measuring ripple on a linear
power supply's output, use **Line trigger** — it locks the sweep to the AC (alternating current) line frequency that's
causing the ripple in the first place.

**Antenna analyzers** go well beyond a simple SWR (standing wave ratio) bridge: they **compute SWR and impedance
automatically**, and the same instrument can also read out **resonant frequency, cable length, and
velocity factor** — which is why "all these choices are correct" keeps showing up as the answer for
antenna-analyzer capability questions in this group.

#### All 11 pool questions for E4A

**E4A01**

Which of the following limits the highest frequency signal that can be accurately displayed on a digital oscilloscope?

- A. Sampling rate of the analog-to-digital converter
- B. Analog-to-digital converter reference frequency
- C. Q of the circuit
- D. All these choices are correct
-
- Answer: A

**E4A02**

Which of the following parameters does a spectrum analyzer display on the vertical and horizontal axes?

- A. Signal amplitude and time
- B. Signal amplitude and frequency
- C. SWR and frequency
- D. SWR and time
-
- Answer: B

**E4A03**

Which of the following test instruments is used to display spurious signals and/or intermodulation distortion products generated by an SSB transmitter?

- A. Differential resolver
- B. Spectrum analyzer
- C. Logic analyzer
- D. Network analyzer
-
- Answer: B

**E4A04**

How is compensation of an oscilloscope probe performed?

- A. A square wave is displayed, and the probe is adjusted until the horizontal portions of the displayed wave are as nearly flat as possible
- B. A high frequency sine wave is displayed, and the probe is adjusted for maximum amplitude
- C. A frequency standard is displayed, and the probe is adjusted until the deflection time is accurate
- D. A DC voltage standard is displayed, and the probe is adjusted until the displayed voltage is accurate
-
- Answer: A

**E4A05**

What is the purpose of using a prescaler with a frequency counter?

- A. Amplify low-level signals for more accurate counting
- B. Multiply a higher frequency signal so a low-frequency counter can display the operating frequency
- C. Prevent oscillation in a low-frequency counter circuit
- D. Reduce the signal frequency to within the counter's operating range
-
- Answer: D

**E4A06**

What is the effect of aliasing on a digital oscilloscope when displaying a waveform?

- A. A false, jittery low-frequency version of the waveform is displayed
- B. The waveform DC offset will be inaccurate
- C. Calibration of the vertical scale is no longer valid
- D. Excessive blanking occurs, which prevents display of the waveform
-
- Answer: A

**E4A07**

Which of the following is an advantage of using an antenna analyzer compared to an SWR bridge?

- A. Antenna analyzers automatically tune your antenna for resonance
- B. Antenna analyzers compute SWR and impedance automatically
- C. Antenna analyzers display a time-varying representation of the modulation envelope
- D. All these choices are correct
-
- Answer: B

**E4A08**

Which of the following is used to measure SWR?

- A. Directional wattmeter
- B. Vector network analyzer
- C. Antenna analyzer
- D. All these choices are correct
-
- Answer: D

**E4A09**

Which of the following is good practice when using an oscilloscope probe?

- A. Minimize the length of the probe's ground connection
- B. Never use a high-impedance probe to measure a low-impedance circuit
- C. Never use a DC-coupled probe to measure an AC circuit
- D. All these choices are correct
-
- Answer: A

**E4A10**

Which trigger mode is most effective when using an oscilloscope to measure a linear power supply’s output ripple?

- A. Single-shot
- B. Edge
- C. Level
- D. Line
-
- Answer: D

**E4A11**

Which of the following can be measured with an antenna analyzer?

- A. Velocity factor
- B. Cable length
- C. Resonant frequency of a tuned circuit
- D. All these choices are correct
-
- Answer: D

---

## E4B — Measurement technique and limitations: instrument accuracy and performance limitations; probes; techniques to minimize errors; measurement of Q; instrument calibration; S parameters; vector network analyzers; RF signals

*One exam question comes from this group. 11 questions in the pool.*

This group pairs S-parameter vocabulary with a few calculation and technique questions.
**S-parameters are labeled by port**: the subscript digits simply identify which port the signal
enters and exits. **S21** (output at port 2, input at port 1) is **forward gain**; **S11** is the
**input port return loss, or reflection coefficient** — just another way of expressing VSWR (voltage standing wave ratio) at that
port. To **calibrate a vector network analyzer**, you connect three known test loads: **short
circuit, open circuit, and 50 ohms**. Once calibrated, a two-port VNA reports things like **filter
frequency response**, along with input impedance, output impedance, and reflection coefficient;
measuring **phase noise** or **pulse rise time** is outside what a VNA does.

**Frequency counter accuracy** is set almost entirely by the **time base accuracy** — the reference
oscillator everything else in the counter is compared against. **Voltmeter sensitivity expressed in
ohms per volt**, multiplied by the full-scale reading, gives the meter's **input impedance** on that
range — the standard VOM (volt-ohm-milliammeter) loading calculation. For a **directional power meter**, absorbed power is
simply forward minus reflected power: 100 W − 25 W = **75 W**. The **Q of a series-tuned circuit** is
read from the **bandwidth of its frequency response** — a narrower response means a higher Q. And the
correct way to **measure SSB intermodulation distortion** (SSB = single sideband) is a two-tone test: modulate the
transmitter with two **AF** (audio frequency) tones that are **non-harmonically related** and observe the RF (radio frequency) output on a
spectrum analyzer.

#### All 11 pool questions for E4B

**E4B01**

Which of the following factors most affects the accuracy of a frequency counter?

- A. Input attenuator accuracy
- B. Time base accuracy
- C. Decade divider accuracy
- D. Temperature coefficient of the logic
-
- Answer: B

**E4B02**

What is the significance of voltmeter sensitivity expressed in ohms per volt?

- A. The full scale reading of the voltmeter multiplied by its ohms per volt rating is the input impedance of the voltmeter
- B. The reading in volts multiplied by the ohms per volt rating will determine the power drawn by the device under test
- C. The reading in ohms divided by the ohms per volt rating will determine the voltage applied to the circuit
- D. The full scale reading in amps divided by ohms per volt rating will determine the size of shunt needed
-
- Answer: A

**E4B03**

Which S parameter is equivalent to forward gain?

- A. S11
- B. S12
- C. S21
- D. S22
-
- Answer: C

**E4B04**

Which S parameter represents input port return loss or reflection coefficient (equivalent to VSWR)?

- A. S11
- B. S12
- C. S21
- D. S22
-
- Answer: A

**E4B05**

What three test loads are used to calibrate an RF vector network analyzer?

- A. 50 ohms, 75 ohms, and 90 ohms
- B. Short circuit, open circuit, and 50 ohms
- C. Short circuit, open circuit, and resonant circuit
- D. 50 ohms through 1/8 wavelength, 1/4 wavelength, and 1/2 wavelength of coaxial cable
-
- Answer: B

**E4B06**

How much power is being absorbed by the load when a directional power meter connected between a transmitter and a terminating load reads 100 watts forward power and 25 watts reflected power?

- A. 100 watts
- B. 125 watts
- C. 112.5 watts
- D. 75 watts
-
- Answer: D

**E4B07**

What do the subscripts of S parameters represent?

- A. The port or ports at which measurements are made
- B. The relative time between measurements
- C. Relative quality of the data
- D. Frequency order of the measurements
-
- Answer: A

**E4B08**

Which of the following can be used to determine the Q of a series-tuned circuit?

- A. The ratio of inductive reactance to capacitive reactance
- B. The frequency shift
- C. The bandwidth of the circuit's frequency response
- D. The resonant frequency of the circuit
-
- Answer: C

**E4B09**

Which of the following can be measured by a two-port vector network analyzer?

- A. Phase noise
- B. Filter frequency response
- C. Pulse rise time
- D. Forward power
-
- Answer: B

**E4B10**

Which of the following methods measures intermodulation distortion in an SSB transmitter?

- A. Modulate the transmitter using two RF signals having non-harmonically related frequencies and observe the RF output with a spectrum analyzer
- B. Modulate the transmitter using two AF signals having non-harmonically related frequencies and observe the RF output with a spectrum analyzer
- C. Modulate the transmitter using two AF signals having harmonically related frequencies and observe the RF output with a peak reading wattmeter
- D. Modulate the transmitter using two RF signals having harmonically related frequencies and observe the RF output with a logic analyzer
-
- Answer: B

**E4B11**

Which of the following can be measured with a vector network analyzer?

- A. Input impedance
- B. Output impedance
- C. Reflection coefficient
- D. All these choices are correct
-
- Answer: D

---

## E4C — Receiver performance: phase noise, noise floor, image rejection, minimum detectable signal (MDS), increasing signal-to-noise ratio and dynamic range, noise figure, reciprocal mixing; selectivity; SDR non-linearity; use of attenuators at low frequencies

*One exam question comes from this group. 14 questions in the pool.*

The receiver-performance math-and-vocabulary group — arguably the most reasoning-heavy part
of E4, and worth understanding rather than memorizing outright. **Noise figure** is the ratio, in dB,
of the noise a real receiver generates to the theoretical minimum noise of a perfect receiver at the
same temperature and bandwidth. That theoretical minimum, in a **1 Hz bandwidth at room temperature**,
works out to **-174 dBm** — the noise floor of a perfect receiver. **Widening the receive bandwidth
raises the noise floor**: going from 50 Hz to 1,000 Hz is a 20x increase in bandwidth, and
10·log₁₀(20) ≈ **13 dB** more noise. **MDS**, the minimum discernible signal, is the weakest signal the
receiver can still pull out of that noise floor.

**Selectivity tools, front to back**: a **front-end filter or preselector** knocks down strong
out-of-band signals before they reach the mixer; a **high IF** makes it easier for that front-end
circuitry to reject **image responses**; a **narrow-band roofing filter**, sitting right after the
first mixer, improves **blocking dynamic range** by attenuating strong signals close to the receive
frequency; and having a choice of IF (intermediate frequency) **bandwidths lets the receiver match the modulation**, maximizing
signal-to-noise ratio and minimizing adjacent-signal interference. The **IF Shift** control shifts the
receive passband to dodge an adjacent interfering station without moving the transmit frequency.

**SDR-specific**: an SDR (software-defined radio) receiver overloads once the input exceeds the **reference voltage of its
analog-to-digital converter** — the digital equivalent of clipping. **Phase noise on an SDR's master
clock oscillator** doesn't just blur the display; it can **combine with a strong signal on a nearby
frequency to generate interference** on the frequency you're trying to receive, which is the same
underlying mechanism as **reciprocal mixing**: local-oscillator phase noise mixing with an adjacent
strong signal to bury a weaker desired one.

**Two terms worth keeping straight**: **desensitization** is an overall loss of sensitivity caused by
a strong signal nearby in frequency; **capture effect** (FM-specific) is one strong signal fully
suppressing a weaker one on the *same* frequency. Finally, **input attenuation on the lower HF bands** (HF = high frequency)
barely hurts signal-to-noise ratio, because **atmospheric noise there already exceeds the receiver's
own internally generated noise** — attenuating both together costs signal margin but not real
sensitivity.

#### All 14 pool questions for E4C

**E4C01**

What is an effect of excessive phase noise in an SDR receiver’s master clock oscillator?

- A. It limits the receiver’s ability to receive strong signals
- B. It can affect the receiver’s frequency calibration
- C. It decreases the receiver’s third-order intercept point
- D. It can combine with strong signals on nearby frequencies to generate interference
-
- Answer: D

**E4C02**

Which of the following receiver circuits can be effective in eliminating interference from strong out-of-band signals?

- A. A front-end filter or preselector
- B. A narrow IF filter
- C. A notch filter
- D. A properly adjusted product detector
-
- Answer: A

**E4C03**

What is the term for the suppression in an FM receiver of one signal by another stronger signal on the same frequency?

- A. Desensitization
- B. Cross-modulation interference
- C. Capture effect
- D. Frequency discrimination
-
- Answer: C

**E4C04**

What is the noise figure of a receiver?

- A. The ratio of atmospheric noise to phase noise
- B. The ratio of the noise bandwidth in hertz to the theoretical bandwidth of a resistive network
- C. The ratio in dB of the noise generated in the receiver to atmospheric noise
- D. The ratio in dB of the noise generated by the receiver to the theoretical minimum noise
-
- Answer: D

**E4C05**

What does a receiver noise floor of -174 dBm represent?

- A. The receiver noise is 6 dB above the theoretical minimum
- B. The theoretical noise in a 1 Hz bandwidth at the input of a perfect receiver at room temperature
- C. The noise figure of a 1 Hz bandwidth receiver
- D. The receiver noise is 3 dB above theoretical minimum
-
- Answer: B

**E4C06**

How much does increasing a receiver’s bandwidth from 50 Hz to 1,000 Hz increase the receiver’s noise floor?

- A. 3 dB
- B. 5 dB
- C. 10 dB
- D. 13 dB
-
- Answer: D

**E4C07**

What does the MDS of a receiver represent?

- A. The meter display sensitivity
- B. The minimum discernible signal
- C. The modulation distortion specification
- D. The maximum detectable spectrum
-
- Answer: B

**E4C08**

An SDR receiver is overloaded when input signals exceed what level?

- A. One-half of the maximum sample rate
- B. One-half of the maximum sampling buffer size
- C. The maximum count value of the analog-to-digital converter
- D. The reference voltage of the analog-to-digital converter
-
- Answer: D

**E4C09**

Which of the following choices is a good reason for selecting a high IF for a superheterodyne HF or VHF communications receiver?

- A. Fewer components in the receiver
- B. Reduced drift
- C. Easier for front-end circuitry to eliminate image responses
- D. Improved receiver noise figure
-
- Answer: C

**E4C10**

What is an advantage of having a variety of receiver bandwidths from which to select?

- A. The noise figure of the RF amplifier can be adjusted to match the modulation type, thus increasing receiver sensitivity
- B. Receiver power consumption can be reduced when wider bandwidth is not required
- C. Receive bandwidth can be set to match the modulation bandwidth, maximizing signal-to-noise ratio and minimizing interference
- D. Multiple frequencies can be received simultaneously if desired
-
- Answer: C

**E4C11**

Why does input attenuation reduce receiver overload on the lower frequency HF bands with little or no impact on signal-to-noise ratio?

- A. The attenuator has a low-pass filter to increase the strength of lower frequency signals
- B. The attenuator has a noise filter to suppress interference
- C. Signals are attenuated separately from the noise
- D. Atmospheric noise is generally greater than internally generated noise even after attenuation
-
- Answer: D

**E4C12**

How does a narrow-band roofing filter affect receiver performance?

- A. It improves sensitivity by reducing front-end noise
- B. It improves intelligibility by using low Q circuitry to reduce ringing
- C. It improves blocking dynamic range by attenuating strong signals near the receive frequency
- D. All these choices are correct
-
- Answer: C

**E4C13**

What is reciprocal mixing?

- A. Two out-of-band signals mixing to generate an in-band spurious signal
- B. In-phase signals cancelling in a mixer resulting in loss of receiver sensitivity
- C. Two digital signals combining from alternate time slots
- D. Local oscillator phase noise mixing with adjacent strong signals to create interference to desired signals
-
- Answer: D

**E4C14**

What is the purpose of the receiver IF Shift control?

- A. To permit listening on a different frequency from the transmitting frequency
- B. To change frequency rapidly
- C. To reduce interference from stations transmitting on adjacent frequencies
- D. To tune in stations slightly off frequency without changing the transmit frequency
-
- Answer: C

---

## E4D — Receiver performance characteristics: dynamic range; intermodulation and cross-modulation interference; third-order intercept; desensitization; preselector; sensitivity; link margin

*One exam question comes from this group. 13 questions in the pool.*

E4D pairs receiver-linearity vocabulary with this subelement's two link-budget calculations
and one unit conversion. **Blocking dynamic range** is the spread, in dB, between the noise floor and
the input level that causes **1 dB of gain compression** — the point where a strong signal starts
squashing the receiver's gain. Poor dynamic range shows up as **spurious signals from cross-modulation
and desensitization caused by strong adjacent signals** — the everyday symptom of a receiver being
overloaded by something *near* the frequency you're listening to, not *on* it.

**Third-order intercept (TOI/IP3)** is a theoretical extrapolation, not a real operating condition: a
third-order intercept of 40 dBm means a pair of hypothetical 40 dBm input tones would theoretically
generate a third-order intermodulation product with the **same output amplitude as either input
tone** — the higher the intercept point, the more real-world IMD (intermodulation distortion) headroom the receiver actually has.
**Odd-order products** (chiefly third-order) matter because, unlike even-order products, they fall
**close to the two original signals in frequency** — so odd-order products of two in-band signals are
also likely to land **in-band**, right where you're trying to listen.

**Repeater intermodulation** happens when two transmitters' output signals **mix together in the
final amplifier** of one or both radios — a classic problem at shared repeater sites. The fix is a
**properly terminated circulator** at the transmitter output, which keeps the other transmitter's
energy from ever reaching the offending final amplifier. More generally, intermodulation in any
circuit traces back to **nonlinear circuits or devices**. A **preselector** attacks the same problem
from the receive side by **increasing rejection of signals outside the band being received**, and
inserting **attenuation ahead of the first RF stage** (RF = radio frequency) is the standard cure for **desensitization**.

**The arithmetic**: link margin and received signal level are both link-budget problems — add transmit
power and antenna gains, subtract losses and (for margin) the receiver's required sensitivity plus
S/N ratio, all in dB. For the unit conversion, remember **0 dBm = 1 mW**; each 10 dB step is a factor
of 10 in power, so **-100 dBm** is ten such steps down from 1 mW, landing at **0.1 picowatt**.

#### All 13 pool questions for E4D

**E4D01**

What is meant by the blocking dynamic range of a receiver?

- A. The difference in dB between the noise floor and the level of an incoming signal that will cause 1 dB of gain compression
- B. The minimum difference in dB between the levels of two FM signals that will cause one signal to block the other
- C. The difference in dB between the noise floor and the third-order intercept point
- D. The minimum difference in dB between two signals which produce third-order intermodulation products greater than the noise floor
-
- Answer: A

**E4D02**

Which of the following describes problems caused by poor dynamic range in a receiver?

- A. Spurious signals caused by cross modulation and desensitization from strong adjacent signals
- B. Oscillator instability requiring frequent retuning and loss of ability to recover the opposite sideband
- C. Poor weak signal reception caused by insufficient local oscillator injection
- D. Oscillator instability and severe audio distortion of all but the strongest received signals
-
- Answer: A

**E4D03**

What creates intermodulation interference between two repeaters in close proximity?

- A. The output signals cause feedback in the final amplifier of one or both transmitters
- B. The output signals mix in the final amplifier of one or both transmitters
- C. The input frequencies are harmonically related
- D. The output frequencies are harmonically related
-
- Answer: B

**E4D04**

Which of the following is used to reduce or eliminate intermodulation interference in a repeater caused by a nearby transmitter?

- A. A band-pass filter in the feed line between the transmitter and receiver
- B. A properly terminated circulator at the output of the repeater’s transmitter
- C. Utilizing a Class C final amplifier
- D. Utilizing a Class D final amplifier
-
- Answer: B

**E4D06**

What is the term for the reduction in receiver sensitivity caused by a strong signal near the received frequency?

- A. Reciprocal mixing
- B. Quieting
- C. Desensitization
- D. Cross modulation interference
-
- Answer: C

**E4D07**

Which of the following reduces the likelihood of receiver desensitization?

- A. Insert attenuation before the first RF stage
- B. Raise the receiver’s IF frequency
- C. Increase the receiver’s front-end gain
- D. Switch from fast AGC to slow AGC
-
- Answer: A

**E4D08**

What causes intermodulation in an electronic circuit?

- A. Negative feedback
- B. Lack of neutralization
- C. Nonlinear circuits or devices
- D. Positive feedback
-
- Answer: C

**E4D09**

What is the purpose of the preselector in a communications receiver?

- A. To store frequencies that are often used
- B. To provide broadband attenuation before the first RF stage to prevent intermodulation
- C. To increase the rejection of signals outside the band being received
- D. To allow selection of the optimum RF amplifier device
-
- Answer: C

**E4D10**

What does a third-order intercept level of 40 dBm mean with respect to receiver performance?

- A. Signals less than 40 dBm will not generate audible third-order intermodulation products
- B. The receiver can tolerate signals up to 40 dB above the noise floor without producing third-order intermodulation products
- C. A pair of 40 dBm input signals will theoretically generate a third-order intermodulation product that has the same output amplitude as either of the input signals
- D. A pair of 1 mW input signals will produce a third-order intermodulation product that is 40 dB stronger than the input signal
-
- Answer: C

**E4D11**

Why are odd-order intermodulation products, created within a receiver, of particular interest compared to other products?

- A. Odd-order products of two signals in the band being received are also likely to be within the band
- B. Odd-order products are more likely to overload the IF filters
- C. Odd-order products are an indication of poor image rejection
- D. Odd-order intermodulation produces three products for every input signal within the band of interest
-
- Answer: A

**E4D12**

What is the link margin in a system with a transmit power level of 10 W (+40 dBm), a system antenna gain of 10 dBi, a cable loss of 3 dB, a path loss of 136 dB, a receiver minimum discernable signal of -103 dBm, and a required signal-to-noise ratio of 6 dB?

- A. -8dB
- B. -14dB
- C. +8dB
- D. +14dB
-
- Answer: C

**E4D13**

What is the received signal level with a transmit power of 10 W (+40 dBm), a transmit antenna gain of 6 dBi, a receive antenna gain of 3 dBi, and a path loss of 100 dB?

- A. -51 dBm
- B. -54 dBm
- C. -57 dBm
- D. -60 dBm
-
- Answer: A

**E4D14**

What power level does a receiver minimum discernible signal of -100 dBm represent?

- A. 100 microwatts
- B. 0.1 microwatt
- C. 0.001 microwatts
- D. 0.1 picowatts
-
- Answer: D

---

## E4E — Noise and interference: external RF interference; electrical and computer noise; line noise; DSP filtering and noise reduction; common-mode current; surge protectors; single point ground panel

*One exam question comes from this group. 14 questions in the pool.*

The noise-and-grounding group — mostly cause-and-effect pairs, plus a couple of terms worth
keeping straight. **Noise blankers** target **impulse noise** (ignition pulses, switching transients)
by gating it out in the time domain, but that gating can **distort strong signals so they appear to
cause spurious emissions** — the tradeoff to remember. **Digital/DSP noise reduction** (DSP = digital signal processing) works on a
broader menu: **broadband white noise, ignition noise, and power line noise** are all reducible by it.
An **automatic notch filter (ANF)**, tuned for CW (continuous wave) work, has the opposite failure mode — because it's
simply hunting for any steady carrier, it can **notch out the desired CW signal right along with the
interfering one**.

**Common-mode current** is the culprit behind most cable-related RFI (radio-frequency interference): it's the current that **flows
equally, in the same direction, on every conductor of a cable** (as opposed to differential-mode
current, which flows in opposite directions on a pair). On a shielded cable, it's specifically
**common-mode current on the shield and conductors together** that lets the cable radiate or pick up
interference — the shield alone doesn't stop it. That's also the logic behind the **single point
ground panel**: bonding everything to one point is what **prevents common-mode transients from
finding multiple paths** through a multi-wire station, and the **AC surge protector belongs on that
same panel** rather than at the service entrance or a random outlet.

**Suppression by source**: automotive charging-system noise gets **ferrite chokes on the charging
leads**; a line-driven AC (alternating current) motor gets a **brute-force AC-line filter in series with its power leads**;
**computer network equipment** tends to produce **unstable modulated or unmodulated signals at
specific frequencies** rather than hum or clicking. Two "regularly-spaced pulses" sources are worth
telling apart: **corroded metal connections mixing and reradiating nearby AM broadcast signals** (AM = amplitude modulation)
explains spurious signals showing up on MF/HF (medium frequency / high frequency), while **switch-mode power supplies** are the classic
source of **carriers spaced at regular intervals across a wide frequency range**.

#### All 14 pool questions for E4E

**E4E01**

What problem can occur when using an automatic notch filter (ANF) to remove interfering carriers while receiving CW signals?

- A. Removal of the CW signal as well as the interfering carrier
- B. Any nearby signal passing through the DSP system will overwhelm the desired signal
- C. Excessive ringing
- D. All these choices are correct
-
- Answer: A

**E4E02**

Which of the following types of noise can often be reduced by a digital noise reduction?

- A. Broadband white noise
- B. Ignition noise
- C. Power line noise
- D. All these choices are correct
-
- Answer: D

**E4E03**

Which of the following types of noise are removed by a noise blanker?

- A. Broadband white noise
- B. Impulse noise
- C. Hum and buzz
- D. All these choices are correct
-
- Answer: B

**E4E04**

How can conducted noise from an automobile battery charging system be suppressed?

- A. By installing filter capacitors in series with the alternator leads
- B. By installing a noise suppression resistor and a blocking capacitor at the battery
- C. By installing a high-pass filter in series with the radio’s power lead and a low-pass filter in parallel with the antenna feed line
- D. By installing ferrite chokes on the charging system leads
-
- Answer: D

**E4E05**

What is used to suppress radio frequency interference from a line-driven AC motor?

- A. A high-pass filter in series with the motor’s power leads
- B. A brute-force AC-line filter in series with the motor’s power leads
- C. A bypass capacitor in series with the motor’s field winding
- D. A bypass choke in parallel with the motor’s field winding
-
- Answer: B

**E4E06**

What type of electrical interference can be caused by computer network equipment?

- A. A loud AC hum in the audio output of your station’s receiver
- B. A clicking noise at intervals of a few seconds
- C. The appearance of unstable modulated or unmodulated signals at specific frequencies
- D. A whining-type noise that continually pulses off and on
-
- Answer: C

**E4E07**

Which of the following can cause shielded cables to radiate or receive interference?

- A. Low inductance ground connections at both ends of the shield
- B. Common-mode currents on the shield and conductors
- C. Use of braided shielding material
- D. Tying all ground connections to a common point resulting in differential-mode currents in the shield
-
- Answer: B

**E4E08**

What current flows equally on all conductors of an unshielded multiconductor cable?

- A. Differential-mode current
- B. Common-mode current
- C. Reactive current only
- D. Magnetically-coupled current only
-
- Answer: B

**E4E09**

What undesirable effect can occur when using a noise blanker?

- A. Received audio in the speech range might have an echo effect
- B. The audio frequency bandwidth of the received signal might be compressed
- C. Strong signals may be distorted and appear to cause spurious emissions
- D. FM signals can no longer be demodulated
-
- Answer: C

**E4E10**

Which of the following can create intermittent loud roaring or buzzing AC line interference?

- A. Arcing contacts in a thermostatically controlled device
- B. A defective doorbell or doorbell transformer inside a nearby residence
- C. A malfunctioning illuminated advertising display
- D. All these choices are correct
-
- Answer: D

**E4E11**

What could be the cause of local AM broadcast band signals combining to generate spurious signals on the MF or HF bands?

- A. One or more of the broadcast stations is transmitting an over-modulated signal
- B. Nearby corroded metal connections are mixing and reradiating the broadcast signals
- C. You are receiving skywave signals from a distant station
- D. Your station receiver IF amplifier stage is overloaded
-
- Answer: B

**E4E12**

What causes interference received as a series of carriers at regular intervals across a wide frequency range?

- A. Switch-mode power supplies
- B. Radar transmitters
- C. Wireless security camera transmitters
- D. Electric fences
-
- Answer: A

**E4E13**

Where should a station AC surge protector be installed?

- A. At the AC service panel
- B. At an AC outlet
- C. On the single point ground panel
- D. On a ground rod outside the station
-
- Answer: C

**E4E14**

What is the purpose of a single point ground panel?

- A. Remove AC power in case of a short-circuit
- B. Prevent common-mode transients in multi-wire systems
- C. Eliminate air gaps between protected and non-protected circuits
- D. Ensure all lightning protectors activate at the same time
-
- Answer: D

---

## Bottom line for E4

**Scopes and analyzers.** Sampling rate limits a digital scope's usable frequency, and undersampling
causes **aliasing**; a spectrum analyzer plots **amplitude vs. frequency**; probe compensation is
checked with a **flat-topped square wave**; **Line trigger** locks to AC (alternating current) ripple; an antenna analyzer
**computes SWR and impedance automatically** (SWR = standing wave ratio) and can also read resonant frequency, cable length, and
velocity factor.

**S-parameters and VNAs.** Subscripts name **ports**; **S21 is forward gain**, **S11 is input return
loss/VSWR** (VSWR = voltage standing wave ratio); VNA (vector network analyzer) calibration loads are **short, open, and 50 ohms**. **Time base accuracy** drives
frequency-counter accuracy; ohms-per-volt times full-scale reading gives a voltmeter's **input
impedance**; **Q comes from bandwidth**; SSB (single sideband) IMD (intermodulation distortion) is checked with a two-tone, non-harmonic **AF** (audio frequency) test.

**Receiver performance.** Noise figure is measured against the **-174 dBm/Hz** theoretical floor; a
20x bandwidth increase costs **13 dB** more noise; **MDS** (minimum detectable signal) is the weakest discernible signal; a **high
IF** (IF = intermediate frequency) improves image rejection; a **roofing filter** improves blocking dynamic range; **SDR overload** (SDR = software-defined radio)
is set by the ADC's (analog-to-digital converter) **reference voltage**; **capture effect** is same-frequency FM (frequency modulation) suppression,
**desensitization** is nearby-frequency suppression, and **reciprocal mixing** is LO (local oscillator) phase noise
combining with an adjacent strong signal.

**Dynamic range and links.** **Blocking dynamic range** is measured to **1 dB compression**;
**third-order intercept** is a theoretical equal-amplitude point; **odd-order IMD products land
in-band**; repeater intermod comes from **mixing in a final amplifier**, cured with a **terminated
circulator**; a **preselector** rejects out-of-band signals; **-100 dBm = 0.1 picowatt**.

**Noise and grounding.** Noise blankers cut **impulse noise** but can distort strong signals; DSP (digital signal processing)
noise reduction also handles broadband and line noise; **common-mode current** — equal, same-direction
current on every conductor — is what makes cables radiate or pick up interference; the **single point
ground panel** is where the surge protector lives and where common-mode transients get stopped.
