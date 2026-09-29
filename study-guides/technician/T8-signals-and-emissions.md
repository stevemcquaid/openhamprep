# T8 — Signals and Emissions

**4 of your 35 exam questions · 4 groups (T8A–T8D) · 47 questions in the pool**

T8 covers how a signal actually gets shaped and sent: the analog modulation modes (AM, FM, SSB,
CW) and how their bandwidths compare, when to choose USB over LSB and SSB over FM, the vocabulary
and operating practices of working through amateur satellites, common operating activities like
direction finding, contesting, and linking repeaters over the internet, and finally the alphabet
soup of non-voice and digital modes.

None of it requires math or first-principles reasoning — it is vocabulary and fact recall. T8D's
digital-mode trivia is the densest single group on the Technician exam, but every group here is
learnable by rote. Four groups, four questions, one from each.

---

## T8A — Basic characteristics of FM and SSB; Bandwidth of various modulation modes: CW, SSB, FM, fast-scan TV; Choice of emission type: selection of USB vs LSB, use of SSB for weak signal work, use of FM for VHF packet and repeaters

*One exam question comes from this group. 12 questions in the pool.*

**SSB is a form of amplitude modulation** — the sidebands come from varying the carrier's
amplitude, then suppressing the carrier and one sideband. That is also why **SSB has narrower
bandwidth than FM**: FM trades bandwidth for noise immunity, SSB doesn't spend any bandwidth on a
carrier or a redundant sideband.

**Bandwidth, narrowest to widest — memorize this order, since several questions just ask you to
rank or pick from it:** **CW is about 150 Hz**, **SSB voice is about 3 kHz**, **FM voice on VHF
repeaters runs 10–15 kHz**, and **AM fast-scan TV is about 6 MHz**. CW is easily the narrowest
signal type tested here; fast-scan TV is easily the widest.

**Mode selection is a short list of pairings to memorize:** **FM or PM is used for VHF packet
radio** and also **for VHF/UHF voice repeaters** — same modulation, two different uses. **SSB is
the choice for long-distance, weak-signal contacts on VHF and UHF** because of its narrow
bandwidth and concentrated power. **Upper sideband (USB)** is the sideband convention for 10-meter
HF, VHF, and UHF SSB communications — lower sideband is reserved for 40, 80, and 160 meters, which
isn't tested in this group but explains why USB is the answer here.

**FM's one real disadvantage next to SSB:** because FM is a full-quieting, capture-effect mode,
**only one FM signal can be received at a time** — a stronger signal captures the receiver and
blocks out weaker ones, unlike SSB where multiple signals can often be heard mixed together.

#### All 12 pool questions for T8A

**T8A01**

Which of the following is a form of amplitude modulation?

- A. Spread spectrum
- B. Packet radio
- **C. Single sideband**  ←
- D. Phase shift keying (PSK)

**T8A02**

What type of modulation is commonly used for VHF packet radio transmissions?

- **A. FM or PM**  ←
- B. SSB
- C. AM
- D. PSK

**T8A03**

Which type of voice mode is often used for long-distance (weak signal) contacts on the VHF and UHF bands?

- A. FM
- B. DRM
- **C. SSB**  ←
- D. PM

**T8A04**

Which type of modulation is commonly used for VHF and UHF voice repeaters?

- A. AM
- B. SSB
- C. PSK
- **D. FM or PM**  ←

**T8A05**

Which of the following signal types has the narrowest bandwidth?

- A. FM voice
- B. SSB voice
- **C. CW**  ←
- D. Slow-scan TV

**T8A06**

Which sideband is normally used for 10-meter HF, VHF, and UHF single-sideband communications?

- **A. Upper sideband**  ←
- B. Lower sideband
- C. Suppressed sideband
- D. Inverted sideband

**T8A07**

What is one characteristic of single sideband (SSB) compared to FM?

- A. SSB signals are easier to tune in correctly
- B. SSB signals are less susceptible to interference
- **C. SSB signals have narrower bandwidth**  ←
- D. SSB signals are less susceptible to high SWR

**T8A08**

What is the approximate bandwidth of a typical single sideband (SSB) voice signal?

- A. 1 kHz
- **B. 3 kHz**  ←
- C. 6 kHz
- D. 15 kHz

**T8A09**

What is the approximate bandwidth of an FM voice signal on VHF repeaters?

- A. Less than 500 Hz
- B. About 150 kHz
- **C. Between 10 and 15 kHz**  ←
- D. Between 50 and 125 kHz

**T8A10**

What is the approximate bandwidth of AM fast-scan TV transmissions?

- A. More than 10 MHz
- **B. About 6 MHz**  ←
- C. About 3 MHz
- D. About 1 MHz

**T8A11**

What is the approximate bandwidth required to transmit a CW signal?

- A. 2.4 kHz
- **B. 150 Hz**  ←
- C. 1000 Hz
- D. 15 kHz

**T8A12**

Which of the following is a disadvantage of FM compared with single sideband?

- A. Voice quality is poorer
- **B. Only one signal can be received at a time**  ←
- C. FM signals are harder to tune
- D. FM signals are more susceptible to high SWR

---

## T8B — Amateur satellite operation: Doppler shift, basic orbits, operating protocols, modulation mode selection, transmitter power considerations, telemetry, satellite tracking programs, beacons, uplink and downlink mode definitions, spin fading, definition of "LEO", setting uplink power

*One exam question comes from this group. 12 questions in the pool.*

**A satellite beacon is a transmission that carries status information** — specifically **the
health and status of the satellite**. Don't be fooled by an "all these choices are correct"
distractor on the telemetry-content question; only health/status is correct there, even though a
different question about tracking-program *outputs* and another about satellite *transmission
modes* really do answer "all these choices are correct."

**Uplink power discipline:** too much effective radiated power on the uplink doesn't overload the
satellite or its computer — it **blocks access by other users** sharing the same transponder. The
correct way to judge your own uplink power into a linear transponder is that **your downlink
signal strength should be about the same as the beacon's**.

**Satellite tracking programs** take **Keplerian elements** as input and, in return, provide
real-time position maps, pass timing (start/max/end with azimuth and elevation), and the
Doppler-shifted apparent frequency — **all of these are correct** as outputs.

**Doppler shift** is the **observed change in signal frequency caused by relative motion between
the satellite and the earth station** — the satellite is moving fast enough relative to you that
you actually have to retune during a pass. **Spin fading** is a different phenomenon: it's caused
by **rotation of the satellite and its antennas**, not by Doppler shift or solar interference.

**Mode letters describe uplink/downlink bands.** In **U/V mode, the uplink is on 70 centimeters
and the downlink is on 2 meters** — U for uplink-UHF, V for downlink-VHF.

**LEO means Low Earth Orbit**, and the distinguishing number is a **period of around 100
minutes**. **Anyone may receive telemetry** from an amateur satellite — there's no license or
control-operator restriction on listening.

#### All 12 pool questions for T8B

**T8B01**

What telemetry information is typically transmitted by satellite beacons?

- A. The signal strength of received signals
- B. Time of day accurate to plus or minus 1/10 second
- **C. Health and status of the satellite**  ←
- D. All these choices are correct

**T8B02**

What is the impact of using excessive effective radiated power on a satellite uplink?

- A. Possibility of commanding the satellite to an improper mode
- **B. Blocking access by other users**  ←
- C. Overloading the satellite batteries
- D. Possibility of rebooting the satellite control computer

**T8B03**

Which of the following are provided by satellite tracking programs?

- A. Maps showing the real-time position of the satellite track over Earth
- B. The time, azimuth, and elevation of the start, maximum altitude, and end of a pass
- C. The apparent frequency of the satellite transmission, including effects of Doppler shift
- **D. All these choices are correct**  ←

**T8B04**

What mode of transmission is commonly used by amateur radio satellites?

- A. SSB
- B. FM
- C. CW/data
- **D. All these choices are correct**  ←

**T8B05**

What is a satellite beacon?

- A. The primary transmit antenna on the satellite
- B. An indicator light that shows where to point your antenna
- C. A reflective surface on the satellite
- **D. A transmission from a satellite that contains status information**  ←

**T8B06**

Which of the following are inputs to a satellite tracking program?

- A. The satellite transmitted power
- **B. The Keplerian elements**  ←
- C. The last observed time of zero Doppler shift
- D. All these choices are correct

**T8B07**

What is Doppler shift in reference to satellite communications?

- A. A change in the satellite orbit
- B. A mode where the satellite receives signals on one band and transmits on another
- **C. An observed change in signal frequency caused by relative motion between the satellite and Earth station**  ←
- D. A special digital communications mode for some satellites

**T8B08**

What does it mean if a satellite is operating in U/V mode?

- A. The satellite uplink is in the 15-meter band and the downlink is in the 10-meter band
- **B. The satellite uplink is in the 70-centimeter band and the downlink is in the 2-meter band**  ←
- C. The satellite operates using ultraviolet frequencies
- D. The satellite frequencies are usually variable

**T8B09**

What causes spin fading of satellite signals?

- A. Circular polarized noise interference radiated from the sun
- **B. Rotation of the satellite and its antennas**  ←
- C. Doppler shift of the received signal
- D. Interfering signals within the satellite uplink band

**T8B10**

What does the term LEO mean in reference to communication satellites?

- A. Low Energy Orbit, which conserves battery power
- B. Low Elevation Orbit, which appears close to the horizon from the earth station
- C. Low Equilibrium Orbit, which has a slightly unstable period
- **D. Low Earth Orbit, which has a period of around 100 minutes**  ←

**T8B11**

Who is permitted to receive telemetry from an amateur radio satellite?

- **A. Anyone**  ←
- B. Only the satellite control operator
- C. Only the control operator or a licensed radio amateur who has received the encryption key from the control operator
- D. Only a licensed radio amateur who has received the encryption key from AMSAT

**T8B12**

Which of the following is a way to determine whether your satellite uplink power into a linear transponder satellite is neither too low nor too high?

- A. Check your signal strength report in the telemetry data
- B. Listen for distortion on your downlink signal
- **C. Your signal strength on the downlink should be about the same as the beacon**  ←
- D. Compare your signal to others on the downlink using an internet SDR receiver

---

## T8C — Operating activities: radio direction finding, contests, linking over the internet, exchanging grid locators

*One exam question comes from this group. 11 questions in the pool.*

**Radio direction finding** is the method used to **locate sources of noise interference or
jamming**, and for a hidden transmitter hunt the useful gear is **a directional antenna** — not an
SWR meter or wattmeter.

**Contesting** is the activity defined as **contacting as many stations as possible during a
specified period**. Good contest etiquette is to **send only the minimum information needed for
proper identification and the contest exchange** — brevity keeps the pileup moving.

**A grid locator is a letter-number designator assigned to a geographic location** (e.g., FM19) —
not to an azimuth/elevation heading and not a piece of test equipment.

**Internet linking has three names to keep straight, all tested individually:**

| Term | What it is |
|---|---|
| **VoIP** | A method of delivering voice communications **over the internet using digital techniques** |
| **IRLP** | A technique to **connect amateur radio systems, such as repeaters, via the internet**; accessed over the air using **DTMF signals** |
| **EchoLink** | The protocol that lets a station **transmit through a repeater without using a radio to initiate the transmission**; requires you to **register your call sign and provide proof of license** before use |

A station that connects other amateur stations to the internet is called a **gateway** — not a
repeater, digipeater, or beacon.

#### All 11 pool questions for T8C

**T8C01**

Which of the following methods is used to locate sources of noise interference or jamming?

- A. Echolocation
- B. Doppler radar
- **C. Radio direction finding**  ←
- D. Phase locking

**T8C02**

Which of these items would be useful for a hidden transmitter hunt?

- A. Calibrated SWR meter
- **B. A directional antenna**  ←
- C. A directional wattmeter
- D. All these choices are correct

**T8C03**

What operating activity involves contacting as many stations as possible during a specified period?

- A. Simulated emergency exercises
- B. Net operations
- C. Hidden transmitter hunts
- **D. Contesting**  ←

**T8C04**

Which of the following is good practice when contacting another station in a contest?

- A. Signing only the last two letters of your call if there are many other stations calling
- B. Contacting the station twice to be sure that you are in his log
- **C. Sending only the minimum information needed for proper identification and the contest exchange**  ←
- D. Adding "Please copy" before your exchange

**T8C05**

What is a grid locator?

- **A. A letter-number designator assigned to a geographic location**  ←
- B. A letter-number designator assigned to an azimuth and elevation
- C. An instrument for locating faults in power amplifiers
- D. An instrument for radio direction finding

**T8C06**

How is over the air access to Internet Radio Linking Project (IRLP) nodes accomplished?

- A. By obtaining a password that is sent via voice to the node
- **B. By using Dual-Tone Multi-Frequency (DTMF) signals**  ←
- C. By entering the proper internet password
- D. By using Continuous Tone-Coded Squelch System (CTCSS) tone codes

**T8C07**

What is Voice Over Internet Protocol (VoIP)?

- A. A set of rules specifying how to identify your station when linked over the internet to another station
- B. A technique employed to "spot" DX stations via the internet
- C. A technique for measuring the modulation quality of a transmitter using remote sites monitored via the internet
- **D. A method of delivering voice communications over the internet using digital techniques**  ←

**T8C08**

What is the Internet Radio Linking Project (IRLP)?

- **A. A technique to connect amateur radio systems, such as repeaters, via the internet**  ←
- B. A system for providing access to websites via amateur radio
- C. A system for informing amateurs in real time of the frequency of active DX stations
- D. A technique for measuring signal strength of an amateur transmitter via the internet

**T8C09**

Which of the following protocols enables an amateur station to transmit through a repeater without using a radio to initiate the transmission?

- A. IRLP
- B. D-STAR
- C. DMR
- **D. EchoLink**  ←

**T8C10**

What is required before using the EchoLink system?

- A. Complete the required EchoLink training
- B. Purchase a license to use the EchoLink software
- **C. Register your call sign and provide proof of license**  ←
- D. At least a General Class license

**T8C11**

What is an amateur radio station that connects other amateur stations to the internet?

- **A. A gateway**  ←
- B. A repeater
- C. A digipeater
- D. A beacon

---

## T8D — Non-voice and digital communications: image signals and definition of NTSC, CW, packet radio, PSK, APRS, error detection and correction, amateur radio networking, DMR, WSJT modes, Broadband-Hamnet

*One exam question comes from this group. 12 questions in the pool.*

**The broadest "all these choices are correct" group in T8** — three separate questions here
(digital modes in general, what APRS carries, and what WSJT-X supports) resolve to "all of the
above," so when you see that option paired with a list of plausible-sounding items in T8D, it is
often the right answer.

**Definitions to lock in:** **CW is another name for a Morse code transmission**. **PSK stands for
Phase Shift Keying**. **NTSC is an analog fast-scan color TV signal**. **FT8 is a digital mode
capable of low signal-to-noise operation** — that low-SNR capability is FT8's whole selling point
and the fact the exam tests.

**APRS** carries **GPS position data, text messages, and weather data** (all correct), and its
signature *application* is **providing real-time tactical digital communications together with a
map showing station locations** — not a PACTOR packet counter or a repeater sign-in list.

**DMR** is described as **a technique for time-multiplexing two digital voice signals on a single
12.5 kHz repeater channel** — two conversations sharing one channel by taking turns in time.

**Packet radio transmissions include a checksum for error detection, a header with the
destination call sign, and automatic repeat request — all these choices are correct.** That last
piece, ARQ, gets its own question: **ARQ is an error-correction method in which the receiving
station detects errors and sends a request for retransmission**.

**WSJT-X's digital-mode software suite supports Earth-Moon-Earth, weak-signal propagation
beacons, and meteor scatter — all these choices are correct.**

**An amateur radio mesh network is a data network built on commercial Wi-Fi equipment running
modified firmware** — this is the Broadband-Hamnet / AREDN concept, not a satellite network and
not an internet linking protocol.

#### All 12 pool questions for T8D

**T8D01**

Which of the following is a digital communications mode?

- A. Packet radio
- B. IEEE 802.11
- C. FT8
- **D. All these choices are correct**  ←

**T8D02**

What is FT8?

- A. A wideband FM voice mode
- **B. A digital mode capable of low signal-to-noise operation**  ←
- C. An eight-channel multiplex mode for FM repeaters
- D. A digital slow-scan TV mode with forward error correction and automatic color compensation

**T8D03**

What kind of data can be transmitted by APRS?

- A. GPS position data
- B. Text messages
- C. Weather data
- **D. All these choices are correct**  ←

**T8D04**

What is meant by the term "NTSC?"

- A. A digital transmission standard for encrypting data
- B. A special mode for satellite uplink
- **C. An analog fast-scan color TV signal**  ←
- D. A frame compression scheme for TV signals

**T8D05**

Which of the following is an application of APRS?

- **A. Providing real-time tactical digital communications in conjunction with a map showing the locations of stations**  ←
- B. Automatically showing the number of packets transmitted via PACTOR during a specific time interval
- C. Providing voice over internet connection between repeaters
- D. Providing information on the number of stations signed into a repeater

**T8D06**

What does the abbreviation "PSK" mean?

- A. Pulse Shift Keying
- **B. Phase Shift Keying**  ←
- C. Packet Sampled Keying
- D. Power Sampled Keying

**T8D07**

Which of the following describes DMR?

- **A. A technique for time-multiplexing two digital voice signals on a single 12.5 kHz repeater channel**  ←
- B. An automatic position tracking mode for FM mobiles communicating through repeaters
- C. An automatic computer logging technique for hands-off logging when communicating while operating a vehicle
- D. A digital technique for transmitting on two repeater inputs simultaneously for automatic error correction

**T8D08**

Which of the following is included in packet radio transmissions?

- A. A checksum that permits error detection
- B. A header that contains the call sign of the station to which the information is being sent
- C. Automatic repeat request in case of error
- **D. All these choices are correct**  ←

**T8D09**

What is CW?

- A. A type of electromagnetic propagation
- B. A digital mode used primarily on 2-meter FM
- C. Error correction for digital transmission using code words
- **D. Another name for a Morse code transmission**  ←

**T8D10**

Which of the following operating activities is supported by digital mode software in the WSJT-X software suite?

- A. Earth-Moon-Earth
- B. Weak signal propagation beacons
- C. Meteor scatter
- **D. All these choices are correct**  ←

**T8D11**

What is the role of ARQ in a transmission system?

- A. A special transmission format limited to video signals
- B. A system used to encrypt command signals to an amateur radio satellite
- **C. An error correction method in which the receiving station detects errors and sends a request for retransmission**  ←
- D. A method of compressing data using autonomous reiterative Q codes prior to final encoding

**T8D12**

Which of the following best describes an amateur radio mesh network?

- **A. An amateur-radio data network using commercial Wi-Fi equipment with modified firmware**  ←
- B. A wide-bandwidth digital voice mode employing DMR protocols
- C. An amateur-radio satellite communications network using modified commercial satellite TV hardware
- D. An internet linking protocol allowing communication through repeaters around the world
