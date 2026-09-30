# E8 — Signals and Emissions

**4 of your 50 exam questions · 4 groups (E8A–E8D) · 48 questions in the pool**

E8 covers the signal-processing side of Extra: how a waveform is built and measured (Fourier
analysis, RMS, PEP vs. average power, A/D and D/A conversion), how modulation encodes information
(FM modulation index and deviation ratio, FDM/TDM, OFDM), how digital modes are defined and bounded
(symbol rate, bandwidth, error correction, constellation diagrams), and what goes wrong when a
transmitter is driven or keyed badly (key clicks, AFSK overmodulation, spread spectrum).

This is General's G8 (Signals and Emissions) with the training wheels off: G8 mostly asked you to
recognize a definition, while E8 asks you to compute a modulation index from two numbers, read a
constellation diagram, and know specific memorized bandwidth figures (13-WPM CW, FT8, a 9600-baud
ASCII FSK link). E8C, with 15 questions, is the single largest group in this subelement and worth
learning as its own mini-topic; the other three groups are compact, built mostly from single
memorized facts.

## Table of Contents

- [E8A — Fourier analysis; RMS measurements; average RF power and peak envelope power (PEP); analog/digital conversion](#e8a--fourier-analysis-rms-measurements-average-rf-power-and-peak-envelope-power-pep-analogdigital-conversion)
  - [All 11 pool questions for E8A](#all-11-pool-questions-for-e8a)
- [E8B — Modulation and demodulation: modulation methods; modulation index and deviation ratio; frequency- and time-division multiplexing; orthogonal frequency-division multiplexing (OFDM)](#e8b--modulation-and-demodulation-modulation-methods-modulation-index-and-deviation-ratio-frequency--and-time-division-multiplexing-orthogonal-frequency-division-multiplexing-ofdm)
  - [All 11 pool questions for E8B](#all-11-pool-questions-for-e8b)
- [E8C — Digital signals: digital communication modes; information rate vs. bandwidth; error correction; constellation diagrams](#e8c--digital-signals-digital-communication-modes-information-rate-vs-bandwidth-error-correction-constellation-diagrams)
  - [All 15 pool questions for E8C](#all-15-pool-questions-for-e8c)
- [E8D — Keying defects and overmodulation of digital signals; digital codes; spread spectrum](#e8d--keying-defects-and-overmodulation-of-digital-signals-digital-codes-spread-spectrum)
  - [All 11 pool questions for E8D](#all-11-pool-questions-for-e8d)

---

## E8A — Fourier analysis; RMS measurements; average RF power and peak envelope power (PEP); analog/digital conversion

*One exam question comes from this group. 11 questions in the pool.*

**Fourier's big idea, tested directly:** a square wave decomposes into a sine wave at the
fundamental frequency plus its **odd harmonics** — that decomposition technique is **Fourier
analysis** (not "vector," "numerical," or "differential" analysis, which are all distractors).

**Time domain vs. frequency domain.** A signal described in the **time domain** is **amplitude at
different times** — essentially a scope trace, as opposed to a frequency-domain view (amplitude or
power vs. frequency, the way a spectrum analyzer displays a signal).

**A/D conversion vocabulary.** **Successive approximation** is a named type of analog-to-digital
conversion. **Dither** is a **small amount of noise deliberately added to the input signal to
reduce quantization noise** — counterintuitive, but adding noise smooths out the stair-step error
inherent in sampling. An **8-bit** converter encodes **256** discrete input levels (2⁸ — the number
of bits sets the level count, not the other way around). A **low-pass filter at a digital-to-analog
converter's output removes spurious sampling artifacts** left over from the conversion process.
**Direct or flash conversion** converters are used in **software defined radios** because their
**very high speed allows digitizing high frequencies** directly. **Total harmonic distortion** is
the standard measure of an analog-to-digital converter's quality.

**RMS and power.** A **true-RMS** meter is worth the extra cost because it correctly measures RMS
for **both sinusoidal and non-sinusoidal signals** — an average-responding meter calibrated for
sine waves reads wrong on anything else. For an **unprocessed single-sideband phone signal**, the
ratio of **PEP to average power is about 2.5 to 1**, and that ratio is set by **speech
characteristics** (voice has a high peak-to-average ratio) — not by frequency, carrier suppression,
or amplifier gain.

#### All 11 pool questions for E8A

**E8A01**

What technique shows that a square wave is made up of a sine wave and its odd harmonics?

- A. Fourier analysis
- B. Vector analysis
- C. Numerical analysis
- D. Differential analysis
-
- Answer: A

**E8A02**

Which of the following is a type of analog-to-digital conversion?

- A. Successive approximation
- B. Harmonic regeneration
- C. Level shifting
- D. Phase reversal
-
- Answer: A

**E8A03**

Which of the following describes a signal in the time domain?

- A. Power at intervals of phase
- B. Amplitude at different times
- C. Frequency at different times
- D. Discrete impulses in time order
-
- Answer: B

**E8A04**

What is “dither” with respect to analog-to-digital converters?

- A. An abnormal condition where the converter cannot settle on a value to represent the signal
- B. A small amount of noise added to the input signal to reduce quantization noise
- C. An error caused by irregular quantization step size
- D. A method of decimation by randomly skipping samples
-
- Answer: B

**E8A05**

What is the benefit of making voltage measurements with a true-RMS calculating meter?

- A. An inverse Fourier transform can be used
- B. The signal’s RMS noise factor is also calculated
- C. The calculated RMS value can be converted directly into phasor form
- D. RMS is measured for both sinusoidal and non-sinusoidal signals
-
- Answer: D

**E8A06**

What is the approximate ratio of PEP-to-average power in an unprocessed single-sideband phone signal?

- A. 2.5 to 1
- B. 25 to 1
- C. 1 to 1
- D. 13 to 1
-
- Answer: A

**E8A07**

What determines the PEP-to-average power ratio of an unprocessed single-sideband phone signal?

- A. The frequency of the modulating signal
- B. Speech characteristics
- C. The degree of carrier suppression
- D. Amplifier gain
-
- Answer: B

**E8A08**

Why are direct or flash conversion analog-to-digital converters used for a software defined radio?

- A. Very low power consumption decreases frequency drift
- B. Immunity to out-of-sequence coding reduces spurious responses
- C. Very high speed allows digitizing high frequencies
- D. All these choices are correct
-
- Answer: C

**E8A09**

How many different input levels can be encoded by an analog-to-digital converter with 8-bit resolution?

- A. 8
- B. 8 multiplied by the gain of the input amplifier
- C. 256 divided by the gain of the input amplifier
- D. 256
-
- Answer: D

**E8A10**

What is the purpose of a low-pass filter used at the output of a digital-to-analog converter?

- A. Lower the input bandwidth to increase the effective resolution
- B. Improve accuracy by removing out-of-sequence codes from the input
- C. Remove spurious sampling artifacts from the output signal
- D. All these choices are correct
-
- Answer: C

**E8A11**

Which of the following is a measure of the quality of an analog-to-digital converter?

- A. Total harmonic distortion
- B. Peak envelope power
- C. Reciprocal mixing
- D. Power factor
-
- Answer: A

---

## E8B — Modulation and demodulation: modulation methods; modulation index and deviation ratio; frequency- and time-division multiplexing; orthogonal frequency-division multiplexing (OFDM)

*One exam question comes from this group. 11 questions in the pool.*

**Modulation index, the formula tested six ways.** For FM, modulation index = **frequency
deviation ÷ modulating signal frequency**. Run the pool's own numbers through it: 3000 Hz deviation
over a 1000 Hz tone gives **3**; 6 kHz deviation over a 2 kHz tone also gives **3**. Same formula,
same order — deviation goes on top, modulating frequency goes on the bottom, never the reverse.

**Deviation ratio uses the same formula, but with the worst case on both sides:** **maximum carrier
deviation ÷ highest modulating frequency** the system is designed to handle. 5 kHz over 3 kHz gives
**1.67**; 7.5 kHz over 3.5 kHz gives **2.14**. And a phase-modulated (as opposed to
frequency-modulated) signal's modulation index **does not depend on the RF carrier frequency** at
all — a favorite "not what you'd expect" answer.

**Multiplexing, three ways to share a channel.** **FDM** divides the transmitted signal into
**separate frequency bands, each carrying a different data stream** — split by frequency. **TDM**
instead gives two or more signals **discrete time slots** of the same transmission — split by
time. **OFDM** is the modern digital-mode workhorse: a **digital modulation technique using
subcarriers at frequencies chosen to avoid intersymbol interference** — "orthogonal" means those
subcarriers don't interfere with each other even though they overlap in frequency. OFDM is used
for **digital modes** on the amateur bands, full stop; the other choices (extremely low-power
contacts, EME, "not allowed") are all distractors.

#### All 11 pool questions for E8B

**E8B01**

What is the modulation index of an FM signal?

- A. The ratio of frequency deviation to modulating signal frequency
- B. The ratio of modulating signal amplitude to frequency deviation
- C. The modulating signal frequency divided by the bandwidth of the transmitted signal
- D. The bandwidth of the transmitted signal divided by the modulating signal frequency
-
- Answer: A

**E8B02**

How does the modulation index of a phase-modulated emission vary with RF carrier frequency?

- A. It increases as the RF carrier frequency increases
- B. It decreases as the RF carrier frequency increases
- C. It varies with the square root of the RF carrier frequency
- D. It does not depend on the RF carrier frequency
-
- Answer: D

**E8B03**

What is the modulation index of an FM phone signal having a maximum frequency deviation of 3000 Hz either side of the carrier frequency if the highest modulating frequency is 1000 Hz?

- A. 3
- B. 0.3
- C. 6
- D. 0.6
-
- Answer: A

**E8B04**

What is the modulation index of an FM phone signal having a maximum carrier deviation of plus or minus 6 kHz if the highest modulating frequency is 2 kHz?

- A. 0.3
- B. 3
- C. 0.6
- D. 6
-
- Answer: B

**E8B05**

What is the deviation ratio of an FM phone signal having a maximum frequency swing of plus or minus 5 kHz if the highest modulation frequency is 3 kHz?

- A. 6
- B. 0.167
- C. 0.6
- D. 1.67
-
- Answer: D

**E8B06**

What is the deviation ratio of an FM phone signal having a maximum frequency swing of plus or minus 7.5 kHz if the highest modulation frequency is 3.5 kHz?

- A. 2.14
- B. 0.214
- C. 0.47
- D. 47
-
- Answer: A

**E8B07**

Orthogonal frequency-division multiplexing (OFDM) is a technique used for which types of amateur communication?

- A. Digital modes
- B. Extremely low-power contacts
- C. EME
- D. OFDM signals are not allowed on amateur bands
-
- Answer: A

**E8B08**

What describes orthogonal frequency-division multiplexing (OFDM)?

- A. A frequency modulation technique that uses non-harmonically related frequencies
- B. A bandwidth compression technique using Fourier transforms
- C. A digital mode for narrow-band, slow-speed transmissions
- D. A digital modulation technique using subcarriers at frequencies chosen to avoid intersymbol interference
-
- Answer: D

**E8B09**

What is deviation ratio?

- A. The ratio of the audio modulating frequency to the center carrier frequency
- B. The ratio of the maximum carrier frequency deviation to the highest audio modulating frequency
- C. The ratio of the carrier center frequency to the audio modulating frequency
- D. The ratio of the highest audio modulating frequency to the average audio modulating frequency
-
- Answer: B

**E8B10**

What is frequency division multiplexing (FDM)?

- A. The transmitted signal jumps from band to band at a predetermined rate
- B. Dividing the transmitted signal into separate frequency bands that each carry a different data stream
- C. The transmitted signal is divided into packets of information
- D. Two or more information streams are merged into a digital combiner, which then pulse position modulates the transmitter
-
- Answer: B

**E8B11**

What is digital time division multiplexing?

- A. Two or more data streams are assigned to discrete sub-carriers on an FM transmitter
- B. Two or more signals are arranged to share discrete time slots of a data transmission
- C. Two or more data streams share the same channel by transmitting time of transmission as the sub-carrier
- D. Two or more signals are quadrature modulated to increase bandwidth efficiency
-
- Answer: B

---

## E8C — Digital signals: digital communication modes; information rate vs. bandwidth; error correction; constellation diagrams

*One exam question comes from this group. 15 questions in the pool.*

**QAM, in one sentence:** **Quadrature Amplitude Modulation** transmits data by **modulating the
amplitude of two carriers of the same frequency but 90 degrees out of phase** — two independent
amplitude channels riding in quadrature. The **constellation diagram** of a QAM or QPSK signal
shows exactly that: **the possible phase and amplitude states for each symbol**, one point per
valid combination.

**Symbol rate and baud are the same thing** — don't overthink the relationship question. **Symbol
rate** itself is defined as **the rate at which the waveform changes to convey information**.

**PSK.** A PSK signal's phase should change **at the zero crossing of the RF signal**, because
doing so **minimizes bandwidth**. **PSK31** specifically minimizes its bandwidth through **use of
sinusoidal data pulses** rather than sharp-edged linear pulses, which splatter energy into
harmonics.

**Bandwidth numbers worth memorizing outright:** 13-WPM CW runs about **52 Hz** wide; an **FT8**
signal is about **50 Hz** wide; a 4,800-Hz frequency shift, 9,600-baud ASCII FM transmission is
**15.36 kHz** wide. For plain CW, bandwidth is set by **keying speed and shape factor (rise and
fall time)** — not IF bandwidth, not Q, not modulation index.

**Error correction and codes.** **ARQ** corrects errors by **requesting a retransmission** when
errors are detected — contrast this with *forward* error correction, which corrects without asking
for a resend. **Gray code** is the digital code where **only one bit changes between sequential
code values**, which limits how bad a single symbol error can be. Data rate can be **increased
without increasing bandwidth** by **using a more efficient digital code** — packing more
information per symbol, not by adding power or redundancy.

**Mesh networking**, a newer addition to the pool: nodes on an amateur mesh network address each
other with ordinary **Internet Protocol (IP)** addresses, and they form the mesh through
**discovery and link establishment protocols** — no trunking system, no talk groups, no central
controller.

#### All 15 pool questions for E8C

**E8C01**

What is Quadrature Amplitude Modulation or QAM?

- A. A technique for digital data compression used in digital television which removes redundancy in the data by comparing bit amplitudes
- B. Transmission of data by modulating the amplitude of two carriers of the same frequency but 90 degrees out of phase
- C. A method of performing single sideband modulation by shifting the phase of the carrier and modulation components of the signal
- D. A technique for analog modulation of television video signals using phase modulation and compression
-
- Answer: B

**E8C02**

What is the definition of symbol rate in a digital transmission?

- A. The number of control characters in a message packet
- B. The maximum rate at which the forward error correction code can make corrections
- C. The rate at which the waveform changes to convey information
- D. The number of characters carried per second by the station-to-station link
-
- Answer: C

**E8C03**

Why should the phase of a PSK signal be changed at the zero crossing of the RF signal?

- A. To minimize bandwidth
- B. To simplify modulation
- C. To improve carrier suppression
- D. All these choices are correct
-
- Answer: A

**E8C04**

What technique minimizes the bandwidth of a PSK31 signal?

- A. Zero-sum character encoding
- B. Reed-Solomon character encoding
- C. Use of sinusoidal data pulses
- D. Use of linear data pulses
-
- Answer: C

**E8C05**

What is the approximate bandwidth of a 13-WPM International Morse Code transmission?

- A. 13 Hz
- B. 26 Hz
- C. 52 Hz
- D. 104 Hz
-
- Answer: C

**E8C06**

What is the bandwidth of an FT8 signal?

- A. 10 Hz
- B. 50 Hz
- C. 600 Hz
- D. 2.4 kHz
-
- Answer: B

**E8C07**

What is the bandwidth of a 4,800-Hz frequency shift, 9,600-baud ASCII FM transmission?

- A. 15.36 kHz
- B. 9.6 kHz
- C. 4.8 kHz
- D. 5.76 kHz
-
- Answer: A

**E8C08**

How does ARQ accomplish error correction?

- A. Special binary codes provide automatic correction
- B. Special polynomial codes provide automatic correction
- C. If errors are detected, redundant data is substituted
- D. If errors are detected, a retransmission is requested
-
- Answer: D

**E8C09**

Which digital code allows only one bit to change between sequential code values?

- A. Binary Coded Decimal Code
- B. Extended Binary Coded Decimal Interchange Code
- C. Extended ASCII
- D. Gray code
-
- Answer: D

**E8C10**

How can data rate be increased without increasing bandwidth?

- A. It is impossible
- B. Increasing analog-to-digital conversion resolution
- C. Using a more efficient digital code
- D. Using forward error correction
-
- Answer: C

**E8C11**

What is the relationship between symbol rate and baud?

- A. They are the same
- B. Baud is twice the symbol rate
- C. Baud rate is half the symbol rate
- D. The relationship depends on the specific code used
-
- Answer: A

**E8C12**

What factors affect the bandwidth of a transmitted CW signal?

- A. IF bandwidth and Q
- B. Modulation index and output power
- C. Keying speed and shape factor (rise and fall time)
- D. All these choices are correct
-
- Answer: C

**E8C13**

What is described by the constellation diagram of a QAM or QPSK signal?

- A. How many carriers may be present at the same time
- B. The possible phase and amplitude states for each symbol
- C. Frequency response of the signal stream
- D. The number of bits used for error correction in the protocol
-
- Answer: B

**E8C14**

What type of addresses do nodes have in a mesh network?

- A. Email
- B. Trust server
- C. Internet Protocol (IP)
- D. Talk group
-
- Answer: C

**E8C15**

What technique do individual nodes use to form a mesh network?

- A. Forward error correction and Viterbi codes
- B. Acting as store-and-forward digipeaters
- C. Discovery and link establishment protocols
- D. Custom code plugs for the local trunking systems
-
- Answer: C

---

## E8D — Keying defects and overmodulation of digital signals; digital codes; spread spectrum

*One exam question comes from this group. 11 questions in the pool.*

**Spread spectrum, two flavors.** **Direct sequence** uses a **high-speed binary bit stream to
shift the phase of an RF carrier**. **Frequency hopping** instead **rapidly varies the transmitted
frequency according to a pseudorandom sequence**. Either way, a spread-spectrum receiver resists
interference because **signals not using the spread-spectrum algorithm are suppressed in the
receiver** — it is the despreading process itself that rejects interference, not raw transmitter
power.

**Key clicks are a keying-speed problem.** An **extremely short rise or fall time** on a CW signal
is the primary cause of **key clicks** — snapping the carrier on and off too abruptly splatters
energy into adjacent frequencies. The fix is the opposite of what you might guess: **increase the
keying waveform's rise and fall times**, softening the edges rather than sharpening them.

**AFSK overmodulation** is usually caused by **excessive transmit audio levels** driving the radio
too hard, and the standard way to evaluate the resulting distortion is **Intermodulation
Distortion (IMD)**. An idling PSK signal should hold its IMD to **-30 dB** or better — a positive
IMD figure (+5, +10, +15 dB) would mean the signal is badly overdriven and splattering across the
band.

**Digital codes.** **Parity bits** added to ASCII characters let **some types of errors be
detected** — not corrected, and not a bigger character set or a faster rate. **Baudot** uses
**5 data bits per character** and needs **two shift characters** (letters/figures) to cover its
limited symbol space; **ASCII** uses **7 or 8 bits** and needs **no shift code** at all — which is
also exactly why ASCII can do something Baudot can't: **transmit both uppercase and lowercase
text**.

#### All 11 pool questions for E8D

**E8D01**

Why are received spread spectrum signals resistant to interference?

- A. Signals not using the spread spectrum algorithm are suppressed in the receiver
- B. The high power used by a spread spectrum transmitter keeps its signal from being easily overpowered
- C. Built-in error correction codes minimize interference
- D. If the receiver detects interference, it will signal the transmitter to change frequencies
-
- Answer: A

**E8D02**

What spread spectrum communications technique uses a high-speed binary bit stream to shift the phase of an RF carrier?

- A. Frequency hopping
- B. Direct sequence
- C. Binary phase-shift keying
- D. Phase compandored spread spectrum
-
- Answer: B

**E8D03**

Which describes spread spectrum frequency hopping?

- A. If interference is detected by the receiver, it will signal the transmitter to change frequencies
- B. RF signals are clipped to generate a wide band of harmonics which provides redundancy to correct errors
- C. A binary bit stream is used to shift the phase of an RF carrier very rapidly in a pseudorandom sequence
- D. Rapidly varying the frequency of a transmitted signal according to a pseudorandom sequence
-
- Answer: D

**E8D04**

What is the primary effect of extremely short rise or fall time on a CW signal?

- A. More difficult to copy
- B. The generation of RF harmonics
- C. The generation of key clicks
- D. More difficult to tune
-
- Answer: C

**E8D05**

What is the most common method of reducing key clicks?

- A. Increase keying waveform rise and fall times
- B. Insert low-pass filters at the transmitter output
- C. Reduce keying waveform rise and fall times
- D. Insert high-pass filters at the transmitter output
-
- Answer: A

**E8D06**

What is the advantage of including parity bits in ASCII characters?

- A. Faster transmission rate
- B. Signal-to-noise ratio is improved
- C. A larger character set is available
- D. Some types of errors can be detected
-
- Answer: D

**E8D07**

What is a common cause of overmodulation of AFSK signals?

- A. Excessive numbers of retries
- B. Excessive frequency deviation
- C. Bit errors in the modem
- D. Excessive transmit audio levels
-
- Answer: D

**E8D08**

What parameter evaluates distortion of an AFSK signal caused by excessive input audio levels?

- A. Signal-to-noise ratio
- B. Baud error rate
- C. Repeat Request Rate (RRR)
- D. Intermodulation Distortion (IMD)
-
- Answer: D

**E8D09**

What is considered an acceptable maximum IMD level for an idling PSK signal?

- A. +5 dB
- B. +10 dB
- C. +15 dB
- D. -30 dB
-
- Answer: D

**E8D10**

What are some of the differences between the Baudot digital code and ASCII?

- A. Baudot uses 4 data bits per character, ASCII uses 7 or 8; Baudot uses 1 character as a letters/figures shift code, ASCII has no letters/figures code
- B. Baudot uses 5 data bits per character, ASCII uses 7 or 8; Baudot uses 2 characters as letters/figures shift codes, ASCII has no letters/figures shift code
- C. Baudot uses 6 data bits per character, ASCII uses 7 or 8; Baudot has no letters/figures shift code, ASCII uses 2 letters/figures shift codes
- D. Baudot uses 7 data bits per character, ASCII uses 8; Baudot has no letters/figures shift code, ASCII uses 2 letters/figures shift codes
-
- Answer: B

**E8D11**

What is one advantage of using ASCII code for data communications?

- A. It includes built-in error correction features
- B. It contains fewer information bits per character than any other code
- C. It is possible to transmit both uppercase and lowercase text
- D. It uses one character as a shift code to send numeric and special characters
-
- Answer: C
