# E2 — Operating Procedures

**5 of your 50 exam questions · 5 groups (E2A–E2E) · 60 questions in the pool**

Operating Procedures is a five-group tour through everything that isn't circuit theory: working
amateur satellites, sending and receiving television over ham bands, running contests and chasing
DX (including by remote control), and the alphabet soup of modern digital modes — first on VHF (very high frequency)/UHF
(APRS (Automatic Packet Reporting System), meteor scatter, EME (earth-moon-earth, or moonbounce)) and then on HF (FT8, FT4, PACTOR, ALE (automatic link establishment), and the rest). None of it
involves math; it is operational knowledge about how each mode and practice actually works.

Unlike the regulatory subelements, there are no Part 97 citations anchoring these questions — the
facts come from operating convention and mode design rather than the rule book. The digital-mode
groups (E2D and E2E) are the largest and most detail-dense, with many similarly-named modes (JT65,
Q65, FT4, FST4, PACTOR I–IV) that the exam deliberately plays off each other, so pay close attention
to which specific fact belongs to which specific mode.

## Table of Contents

- [E2A — Amateur radio in space: amateur satellites; orbital mechanics; frequencies and modes; satellite hardware; satellite operations](#e2a--amateur-radio-in-space-amateur-satellites-orbital-mechanics-frequencies-and-modes-satellite-hardware-satellite-operations)
  - [All 12 pool questions for E2A](#all-12-pool-questions-for-e2a)
- [E2B — Television practices: fast-scan television standards and techniques; slow scan television standards and techniques](#e2b--television-practices-fast-scan-television-standards-and-techniques-slow-scan-television-standards-and-techniques)
  - [All 12 pool questions for E2B](#all-12-pool-questions-for-e2b)
- [E2C — Contest and DX operating; remote operation techniques; log data format; contact confirmation; RF network systems](#e2c--contest-and-dx-operating-remote-operation-techniques-log-data-format-contact-confirmation-rf-network-systems)
  - [All 12 pool questions for E2C](#all-12-pool-questions-for-e2c)
- [E2D — Operating methods: digital modes and procedures for VHF and UHF; APRS; EME procedures; meteor scatter procedures](#e2d--operating-methods-digital-modes-and-procedures-for-vhf-and-uhf-aprs-eme-procedures-meteor-scatter-procedures)
  - [All 11 pool questions for E2D](#all-11-pool-questions-for-e2d)
- [E2E — Operating methods: digital modes and procedures for HF](#e2e--operating-methods-digital-modes-and-procedures-for-hf)
  - [All 13 pool questions for E2E](#all-13-pool-questions-for-e2e)

---

## E2A — Amateur radio in space: amateur satellites; orbital mechanics; frequencies and modes; satellite hardware; satellite operations

*One exam question comes from this group. 12 questions in the pool.*

**Passes and hardware.** An **ascending pass runs south to north**; the exam can also phrase it the
other direction, so lock in that one fact. A satellite's **"mode" is its uplink and downlink
frequency band pair**, and the letters in a mode designator spell out exactly that — **the uplink
and downlink frequency ranges**, nothing about power or polarization. **Keplerian elements** are
simply **the parameters that define a satellite's orbit** — don't confuse them with antenna elements
or spread-spectrum codes.

**Linear transponders invert.** An inverting linear transponder flips the signal: **USB on the
uplink comes down as LSB** (USB = upper sideband; LSB = lower sideband), the **signal's position in the passband is reversed**, and because the
uplink and downlink Doppler shifts run in opposite directions they partly cancel — all three of these
are true at once, so that question answers **"all these choices are correct."** Mechanically, the
transponder **mixes the uplink signal with a local oscillator and transmits the difference
product** — it does not demodulate and remodulate. A linear transponder is mode-agnostic: it relays
**FM, CW, SSB, SSTV, PSK, and packet alike** (FM = frequency modulation; CW = continuous wave; SSB = single sideband; SSTV = slow-scan television; PSK = phase-shift keying) ("all these choices are correct" again). Because the
whole passband shares one downlink, **ERP is limited so a strong uplink signal doesn't rob downlink
power from every other user** (ERP = effective radiated power) sharing that transponder.

**Orbits and antennas.** **L band and S band are the 23- and 13-centimeter bands.** A
**geostationary** satellite is the one that appears to stay fixed in the sky. Spacecraft tumble, so a
linearly polarized ground antenna fades in and out as polarization rotates; a **circularly polarized
antenna** minimizes the effects of that spin modulation and Faraday rotation. Finally, **digital
store-and-forward** satellites simply **hold messages onboard for later download** — a mailbox in
orbit, not a live repeater.

#### All 12 pool questions for E2A

**E2A01**

What is the direction of an ascending pass for an amateur satellite?

- A. From west to east
- B. From east to west
- C. From south to north
- D. From north to south
-
- Answer: C

**E2A02**

Which of the following is characteristic of an inverting linear transponder?

- A. Doppler shift is reduced because the uplink and downlink shifts are in opposite directions
- B. Signal position in the band is reversed
- C. Upper sideband on the uplink becomes lower sideband on the downlink, and vice versa
- D. All these choices are correct
-
- Answer: D

**E2A03**

How is an upload signal processed by an inverting linear transponder?

- A. The signal is detected and remodulated on the reverse sideband
- B. The signal is passed through a nonlinear filter
- C. The signal is reduced to I and Q components, and the Q component is filtered out
- D. The signal is mixed with a local oscillator signal and the difference product is transmitted
-
- Answer: D

**E2A04**

What is meant by the “mode” of an amateur radio satellite?

- A. Whether the satellite is in a low earth or geostationary orbit
- B. The satellite’s uplink and downlink frequency bands
- C. The satellite’s orientation with respect to the Earth
- D. Whether the satellite is in a polar or equatorial orbit
-
- Answer: B

**E2A05**

What do the letters in a satellite’s mode designator specify?

- A. Power limits for uplink and downlink transmissions
- B. The location of the ground control station
- C. The polarization of uplink and downlink signals
- D. The uplink and downlink frequency ranges
-
- Answer: D

**E2A06**

What are Keplerian elements?

- A. Parameters that define the orbit of a satellite
- B. Phase reversing elements in a Yagi antenna
- C. High-emission heater filaments used in magnetron tubes
- D. Encrypting codes used for spread spectrum modulation
-
- Answer: A

**E2A07**

Which of the following types of signals can be relayed through a linear transponder?

- A. FM and CW
- B. SSB and SSTV
- C. PSK and packet
- D. All these choices are correct
-
- Answer: D

**E2A08**

Why should effective radiated power (ERP) be limited to a satellite that uses a linear transponder?

- A. To prevent creating errors in the satellite telemetry
- B. To avoid reducing the downlink power to all other users
- C. To prevent the satellite from emitting out-of-band signals
- D. To avoid interfering with terrestrial QSOs
-
- Answer: B

**E2A09**

What do the terms “L band” and “S band” specify?

- A. The 23- and 13-centimeter bands
- B. The 2-meter and 70-centimeter bands
- C. FM and digital store-and-forward systems
- D. Which sideband to use
-
- Answer: A

**E2A10**

What type of satellite appears to stay in one position in the sky?

- A. HEO
- B. Geostationary
- C. Geomagnetic
- D. LEO
-
- Answer: B

**E2A11**

What type of antenna can be used to minimize the effects of spin modulation and Faraday rotation?

- A. A linearly polarized antenna
- B. A circularly polarized antenna
- C. An isotropic antenna
- D. A log-periodic dipole array
-
- Answer: B

**E2A12**

What is the purpose of digital store-and-forward functions on an amateur radio satellite?

- A. To upload operational software for the transponder
- B. To delay download of telemetry between satellites
- C. To hold digital messages in the satellite for later download
- D. To relay messages between satellites
-
- Answer: C

---

## E2B — Television practices: fast-scan television standards and techniques; slow scan television standards and techniques

*One exam question comes from this group. 12 questions in the pool.*

**Fast-scan (NTSC) fundamentals.** (NTSC = National Television System Committee) A frame is **525 horizontal lines**, built by **interlacing** —
one field carries the **odd-numbered lines**, the next carries the **even-numbered** ones.
**Vestigial sideband** is the reason analog TV fits into its allocated bandwidth: it's **AM in which
one complete sideband and a portion of the other are transmitted** (AM = amplitude modulation), and in fast-scan TV specifically
it **reduces bandwidth while increasing the fidelity of the low-frequency (coarse-detail) video
components**. Digital amateur TV (DVB-T) instead uses **QAM and QPSK** (QAM = quadrature amplitude modulation; QPSK = quadrature phase-shift keying) modulation, and a coding rate
of 3/4 means **25% of the transmitted data is forward error correction overhead** — read that one
carefully, since the "3/4" names the useful-data fraction, not the FEC fraction.

**Repurposing gear.** Hams get 70-centimeter fast-scan TV onto ordinary analog TV sets by
**transmitting USB and demodulating the signal with a computer sound card** (USB = upper sideband) — there's no special
70-cm tuner trick involved.

**Slow-scan (SSTV).** Picture brightness rides on **tone frequency**, not amplitude. Each new
picture line is triggered by **specific tone frequencies**, and analog color SSTV sends its **color
lines sequentially** rather than all at once. The **vertical interval signaling (VIS) code** at the
start of a transmission **identifies which SSTV mode is being used**, so receiving software can
decode correctly. SSTV carried over the **Digital Radio Mondiale (DRM)** protocol is received on an
ordinary **SSB** receiver — DRM here is a mode riding inside SSB (single sideband) audio, not a separate radio system.

#### All 12 pool questions for E2B

**E2B01**

In digital television, what does a coding rate of 3/4 mean?

- A. 25% of the data sent is forward error correction data
- B. Data compression reduces data rate by 3/4
- C. 1/4 of the time interval is used as a guard interval
- D. Three, four-bit words are used to transmit each pixel
-
- Answer: A

**E2B02**

How many horizontal lines make up a fast-scan (NTSC) television frame?

- A. 30
- B. 60
- C. 525
- D. 1080
-
- Answer: C

**E2B03**

How is an interlaced scanning pattern generated in a fast-scan (NTSC) television system?

- A. By scanning two fields simultaneously
- B. By scanning each field from bottom-to-top
- C. By scanning lines from left-to-right in one field and right-to-left in the next
- D. By scanning odd-numbered lines in one field and even-numbered lines in the next
-
- Answer: D

**E2B04**

How is color information sent in analog SSTV?

- A. Color lines are sent sequentially
- B. Color information is sent on a 2.8 kHz subcarrier
- C. Color is sent in a color burst at the end of each line
- D. Color is amplitude modulated on the frequency modulated intensity signal
-
- Answer: A

**E2B05**

Which of the following describes the use of vestigial sideband in analog fast-scan TV transmissions?

- A. The vestigial sideband carries the audio information
- B. The vestigial sideband contains chroma information
- C. Vestigial sideband reduces the bandwidth while increasing the fidelity of low frequency video components
- D. Vestigial sideband provides high frequency emphasis to sharpen the picture
-
- Answer: C

**E2B06**

What is vestigial sideband modulation?

- A. Amplitude modulation in which one complete sideband and a portion of the other are transmitted
- B. A type of modulation in which one sideband is inverted
- C. Narrow-band FM modulation achieved by filtering one sideband from the audio before frequency modulating the carrier
- D. Spread spectrum modulation achieved by applying FM modulation following single sideband amplitude modulation
-
- Answer: A

**E2B07**

Which types of modulation are used for amateur television DVB-T signals?

- A. FM and FSK
- B. QAM and QPSK
- C. AM and OOK
- D. All these choices are correct
-
- Answer: B

**E2B08**

What technique allows commercial analog TV receivers to be used for fast-scan TV operations on the 70-centimeter band?

- A. Transmitting on channels shared with cable TV
- B. Using converted satellite TV dishes
- C. Transmitting on the abandoned TV channel 2
- D. Using USB and demodulating the signal with a computer sound card
-
- Answer: D

**E2B09**

What kind of receiver can be used to receive and decode SSTV using the Digital Radio Mondiale (DRM) protocol?

- A. CDMA
- B. AREDN
- C. AM
- D. SSB
-
- Answer: D

**E2B10**

What aspect of an analog slow-scan television signal encodes the brightness of the picture?

- A. Tone frequency
- B. Tone amplitude
- C. Sync amplitude
- D. Sync frequency
-
- Answer: A

**E2B11**

What is the function of the vertical interval signaling (VIS) code sent as part of an SSTV transmission?

- A. To lock the color burst oscillator in color SSTV images
- B. To identify the SSTV mode being used
- C. To provide vertical synchronization
- D. To identify the call sign of the station transmitting
-
- Answer: B

**E2B12**

What signals SSTV receiving software to begin a new picture line?

- A. Specific tone frequencies
- B. Elapsed time
- C. Specific tone amplitudes
- D. A two-tone signal
-
- Answer: A

---

## E2C — Contest and DX operating; remote operation techniques; log data format; contact confirmation; RF network systems

*One exam question comes from this group. 12 questions in the pool.*

**Remote operation and logs.** A US (United States) station operated by remote control, with the remote transmitter
also located in the US, needs **no additional indicator** — a plain call sign is enough. Amateur log
data is exchanged in **ADIF** (Amateur Data Interchange Format) format; when you submit a finished log to a contest sponsor, that's the
**Cabrillo format** instead — two different standards for two different jobs. Confirmations flow
through **Logbook of The World (LoTW)** for essentially any qualifying contact — special event
contacts, contacts with non-US stations, Worked All States credit — so that question answers **"all
these choices are correct."**

**Contests.** **30 meters is generally excluded from amateur radio contesting.** During a VHF/UHF (very high frequency / ultra high frequency)
contest, activity concentrates in the **weak-signal segment, near the calling frequency** — not at
the top of the band and not 25 kHz above the calling frequency. In a pileup or contest, identify by
sending your **full call sign once or twice** — nothing abbreviated, nothing repeated three times.

**DX operating.** DX (long-distance communication) stations split their transmit and receive frequencies for every reason at
once — avoiding a frequency prohibited to some responding stations, separating callers from the DX
station, and reducing interference — so that question is also **"all these choices are correct."** A
**DX QSL Manager handles the receiving and sending of confirmations** for a DX station, distinct from
someone running a pileup net or relaying propagation information to a DXpedition.

**Mesh networking.** Amateur mesh networks run on **frequencies shared with various unlicensed
wireless data services**, built from **wireless routers running custom firmware** — not repurposed
packet TNCs (terminal node controllers).

**One more term.** The delay between a control operator's action and the resulting change in the
transmitted signal is **latency**, not jitter, hang time, or anti-VOX.

#### All 12 pool questions for E2C

**E2C01**

What indicator is required to be used by US-licensed operators when operating a station via remote control and the remote transmitter is located in the US?

- A. / followed by the USPS two-letter abbreviation for the state in which the remote station is located
- B. /R# where # is the district of the remote station
- C. / followed by the ARRL Section of the remote station
- D. No additional indicator is required
-
- Answer: D

**E2C02**

Which of the following file formats is used for exchanging amateur radio log data?

- A. NEC
- B. ARLD
- C. ADIF
- D. OCF
-
- Answer: C

**E2C03**

From which of the following bands is amateur radio contesting generally excluded?

- A. 30 meters
- B. 6 meters
- C. 70 centimeters
- D. 33 centimeters
-
- Answer: A

**E2C04**

Which of the following frequencies can be used for amateur radio mesh networks?

- A. HF frequencies where digital communications are permitted
- B. Frequencies shared with various unlicensed wireless data services
- C. Cable TV channels 41-43
- D. The 60-meter band channel centered on 5373 kHz
-
- Answer: B

**E2C05**

What is the function of a DX QSL Manager?

- A. Allocate frequencies for DXpeditions
- B. Handle the receiving and sending of confirmations for a DX station
- C. Run a net to allow many stations to contact a rare DX station
- D. Communicate to a DXpedition about propagation, band openings, pileup conditions, etc.
-
- Answer: B

**E2C06**

During a VHF/UHF contest, in which band segment would you expect to find the highest level of SSB or CW activity?

- A. At the top of each band, usually in a segment reserved for contests
- B. In the middle of each band, usually on the national calling frequency
- C. In the weak signal segment of the band, with most of the activity near the calling frequency
- D. In the middle of the band, usually 25 kHz above the national calling frequency
-
- Answer: C

**E2C07**

What is the Cabrillo format?

- A. A standard for submission of electronic contest logs
- B. A method of exchanging information during a contest QSO
- C. The most common set of contest rules
- D. A digital protocol specifically designed for rapid contest exchanges
-
- Answer: A

**E2C08**

Which of the following contacts may be confirmed through the Logbook of The World (LoTW)?

- A. Special event contacts between stations in the US
- B. Contacts between a US station and a non-US station
- C. Contacts for Worked All States credit
- D. All these choices are correct
-
- Answer: D

**E2C09**

What type of equipment is commonly used to implement an amateur radio mesh network?

- A. A 2-meter VHF transceiver with a 1,200-baud modem
- B. A computer running EchoLink to provide interface from the radio to the internet
- C. A wireless router running custom firmware
- D. A 440 MHz transceiver with a 9,600-baud modem
-
- Answer: C

**E2C10**

Why do DX stations often transmit and receive on different frequencies?

- A. Because the DX station may be transmitting on a frequency that is prohibited to some responding stations
- B. To separate the calling stations from the DX station
- C. To improve operating efficiency by reducing interference
- D. All these choices are correct
-
- Answer: D

**E2C11**

How should you generally identify your station when attempting to contact a DX station during a contest or in a pileup?

- A. Send your full call sign once or twice
- B. Send only the last two letters of your call sign until you make contact
- C. Send your full call sign and grid square
- D. Send the call sign of the DX station three times, the words “this is,” then your call sign three times
-
- Answer: A

**E2C12**

What indicates the delay between a control operator action and the corresponding change in the transmitted signal?

- A. Jitter
- B. Hang time
- C. Latency
- D. Anti-VOX
-
- Answer: C

---

## E2D — Operating methods: digital modes and procedures for VHF and UHF; APRS; EME procedures; meteor scatter procedures

*One exam question comes from this group. 11 questions in the pool.*

**Meteor scatter and EME are both about timing.** **MSK144** is the mode built for meteor scatter
communications. EME (moonbounce) instead uses **Q65**, and the classic method for establishing an
EME contact is **time-synchronous transmissions that alternate between stations** — you transmit in
your assigned slot, the other station transmits in theirs. **JT65**, the mode both of these descend
from, is prized for **decoding signals with a very low signal-to-noise ratio**, using **multitone
AFSK** (AFSK = audio frequency-shift keying) modulation. In a VHF (very high frequency) contest run on **FT8 or FT4**, the exchange substitutes a **grid square**
for the usual signal-to-noise report.

**APRS.** APRS (Automatic Packet Reporting System) beacon data rides on **AX.25** packet, carried in an **Unnumbered Information**
frame — the frame type built for connectionless broadcast data. Stations relay each other's packets
through **packet digipeaters**. A path of **WIDE3-1 means three digipeater hops were requested, with
one hop remaining** — the number counts down as each digipeater passes the packet along. APRS is
also the technology used for **real-time tracking of balloons** carrying amateur radio transmitters.

#### All 11 pool questions for E2D

**E2D01**

Which of the following digital modes is designed for meteor scatter communications?

- A. WSPR
- B. MSK144
- C. Hellschreiber
- D. APRS
-
- Answer: B

**E2D02**

What information replaces signal-to-noise ratio when using the FT8 or FT4 modes in a VHF contest?

- A. RST report
- B. State abbreviation
- C. Serial number
- D. Grid square
-
- Answer: D

**E2D03**

Which of the following digital modes is designed for EME communications?

- A. MSK144
- B. PACTOR III
- C. WSPR
- D. Q65
-
- Answer: D

**E2D04**

What technology is used for real-time tracking of balloons carrying amateur radio transmitters?

- A. FT8
- B. Bandwidth compressed LORAN
- C. APRS
- D. PACTOR III
-
- Answer: C

**E2D05**

What is the characteristic of the JT65 mode?

- A. Uses only a 65 Hz bandwidth
- B. Decodes signals with a very low signal-to-noise ratio
- C. Symbol rate is 65 baud
- D. Permits fast-scan TV transmissions over narrow bandwidth
-
- Answer: B

**E2D06**

Which of the following is a method for establishing EME contacts?

- A. Time-synchronous transmissions alternating between stations
- B. Storing and forwarding digital messages
- C. Judging optimum transmission times by monitoring beacons reflected from the moon
- D. High-speed CW identification to avoid fading
-
- Answer: A

**E2D07**

What digital protocol is used by APRS?

- A. PACTOR
- B. QAM
- C. AX.25
- D. AMTOR
-
- Answer: C

**E2D08**

What type of packet frame is used to transmit APRS beacon data?

- A. Acknowledgement
- B. Burst
- C. Unnumbered Information
- D. Connect
-
- Answer: C

**E2D09**

What type of modulation is used by JT65?

- A. Multitone AFSK
- B. PSK
- C. RTTY
- D. QAM
-
- Answer: A

**E2D10**

What does the packet path WIDE3-1 designate?

- A. Three stations are allowed on frequency, one transmitting at a time
- B. Three subcarriers are permitted, subcarrier one is being used
- C. Three digipeater hops are requested with one remaining
- D. Three internet gateway stations may receive one transmission
-
- Answer: C

**E2D11**

How do APRS stations relay data?

- A. By packet ACK/NAK relay
- B. By C4FM repeaters
- C. By DMR repeaters
- D. By packet digipeaters
-
- Answer: D

---

## E2E — Operating methods: digital modes and procedures for HF

*One exam question comes from this group. 13 questions in the pool.*

**FSK basics.** Below 30 MHz, data emissions generally use **FSK** — frequency shift keying, not
DTMF-modulated FM (frequency modulation), pulse modulation, or spread spectrum. There are two flavors: **direct FSK
modulates the transmitter's VFO itself** (VFO = variable-frequency oscillator), while audio FSK shifts a tone fed into the mic input;
direct FSK is the one the exam names. **WSJT-X modes synchronize transmit/receive timing through
synchronization of computer clocks**, which is why an accurate clock matters for FT8/FT4/WSPR (Weak Signal Propagation Reporter)/JT65
operation.

**The FTx family.** The "4" in **FT4** refers to **four-tone continuous-phase frequency shift
keying**. **FST4** adds **four-tone Gaussian frequency shift keying, variable transmit/receive
periods, and seven different tone spacings** — all three at once, so that question is **"all these
choices are correct."** An **FT8 transmission cycle is 15 seconds** long. **Q65** differs from its
ancestor **JT65** in that **multiple receive cycles are averaged** to pull weaker signals out of the
noise. Of **WSPR, RTTY, PSK31, and MFSK16** (RTTY = radioteletype), only **WSPR does not support keyboard-to-keyboard
operation** — it is a one-way, beacon-style propagation-reporting mode.

**Bandwidth and throughput.** Of the modes compared on the exam, **FT8 has the narrowest
bandwidth**, while **PACTOR IV has the highest data throughput** under clear communication
conditions. **PACTOR** is also the HF (high frequency) digital mode used to **transfer binary files**. **PSK31** is
the mode built on **variable-length character coding**.

**ALE.** Automatic Link Establishment stations **constantly scan a list of frequencies, activating
the radio when the designated call sign is received** — a very different mechanism from listening on
one fixed calling frequency.

#### All 13 pool questions for E2E

**E2E01**

Which of the following types of modulation is used for data emissions below 30 MHz?

- A. DTMF tones modulating an FM signal
- B. FSK
- C. Pulse modulation
- D. Spread spectrum
-
- Answer: B

**E2E02**

Which of the following synchronizes WSJT-X digital mode transmit/receive timing?

- A. Alignment of frequency shifts
- B. Synchronization of computer clocks
- C. Sync-field transmission
- D. Sync-pulse timing
-
- Answer: B

**E2E03**

To what does the "4" in FT4 refer?

- A. Multiples of 4 bits of user information
- B. Four-tone continuous-phase frequency shift keying
- C. Four transmit/receive cycles per minute
- D. All these choices are correct
-
- Answer: B

**E2E04**

Which of the following is characteristic of the FST4 mode?

- A. Four-tone Gaussian frequency shift keying
- B. Variable transmit/receive periods
- C. Seven different tone spacings
- D. All these choices are correct
-
- Answer: D

**E2E05**

Which of these digital modes does not support keyboard-to-keyboard operation?

- A. WSPR
- B. RTTY
- C. PSK31
- D. MFSK16
-
- Answer: A

**E2E06**

What is the length of an FT8 transmission cycle?

- A. It varies with the amount of data
- B. 8 seconds
- C. 15 seconds
- D. 30 seconds
-
- Answer: C

**E2E07**

How does Q65 differ from JT65?

- A. Keyboard-to keyboard operation is supported
- B. Quadrature modulation is used
- C. Multiple receive cycles are averaged
- D. All these choices are correct
-
- Answer: C

**E2E08**

Which of the following HF digital modes can be used to transfer binary files?

- A. PSK31
- B. PACTOR
- C. RTTY
- D. AMTOR
-
- Answer: B

**E2E09**

Which of the following HF digital modes uses variable-length character coding?

- A. RTTY
- B. PACTOR
- C. MT63
- D. PSK31
-
- Answer: D

**E2E10**

Which of these digital modes has the narrowest bandwidth?

- A. MFSK16
- B. 170 Hz shift, 45-baud RTTY
- C. FT8
- D. PACTOR IV
-
- Answer: C

**E2E11**

What is the difference between direct FSK and audio FSK?

- A. Direct FSK modulates the transmitter VFO
- B. Direct FSK occupies less bandwidth
- C. Direct FSK can transmit higher baud rates
- D. All these choices are correct
-
- Answer: A

**E2E12**

How do ALE stations establish contact?

- A. ALE constantly scans a list of frequencies, activating the radio when the designated call sign is received
- B. ALE radios monitor an internet site for the frequency they are being paged on
- C. ALE radios send a constant tone code to establish a frequency for future use
- D. ALE radios activate when they hear their signal echoed by back scatter
-
- Answer: A

**E2E13**

Which of these digital modes has the highest data throughput under clear communication conditions?

- A. MFSK16
- B. 170 Hz shift, 45 baud RTTY
- C. FT8
- D. PACTOR IV
-
- Answer: D
