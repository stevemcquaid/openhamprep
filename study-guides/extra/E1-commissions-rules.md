# E1 — Commission's Rules

**6 of your 50 exam questions · 6 groups (E1A–E1F) · 68 questions in the pool**

Extra's rules subelement assumes you already know General's material and pushes into the edge
cases: carrier-frequency arithmetic on SSB, the narrow 630- and 2200-meter bands, automatic and
remote control minutiae, VE program mechanics at the level VEs actually experience them, and the
space- and Earth-station rules that exist because Extra class licensees are the ones flying
satellites and high-altitude balloons.

These six groups carry unusually heavy weight — E1C and E1D alone run 12 questions apiece, more
than any group in the General pool. Much of it is still pure memorization (power limits, band
edges, timeframes), but a real slice requires reasoning through where a signal's sidebands actually
fall relative to a band edge — work through those carefully rather than just memorizing numbers.

---

## E1A — Frequency privileges; signal frequency range; automatic message forwarding; stations aboard ships or aircraft; power restriction on 630- and 2200-meter bands

*One exam question comes from this group. 11 questions in the pool.*

**Carrier frequency vs. sidebands.** USB energy sits *above* the carrier frequency; LSB energy sits
*below* it. A displayed carrier frequency is legal only if the entire occupied bandwidth stays
inside the band edges — so the lowest legal LSB carrier is one full signal-width (roughly 3 kHz)
*above* the lower band edge, and the highest legal USB carrier is one full signal-width *below* the
upper edge. Get the sideband direction backwards and you'll pick the wrong edge every time.

**630 and 2200 meters run on EIRP, not PEP.** 2200 meters caps at **1 watt EIRP**; 630 meters caps
at **5 watts EIRP** (except in parts of Alaska). Both are measured as *equivalent isotropic radiated
power*, not the PEP-output-from-transmitter standard used elsewhere in Part 97.

**60-meter channelized CW** must be transmitted at the **center frequency** of the channel — not the
edge, and not "wherever the sidebands happen to fit."

**Shipboard/aircraft stations.** Physical control requires **any FCC-issued amateur license** (or
reciprocal alien authorization) — no special marine or aviation endorsement exists. Before the
station can operate at all, the ship's master or the aircraft's pilot in command must approve it.

**Message forwarding accountability.** If a forwarding system inadvertently relays a
rule-violating message, the **control operator of the originating station** is primarily
accountable — not the bulletin-board operator, and not everyone downstream.

#### All 11 pool questions for E1A

**E1A01** &nbsp;·&nbsp; `[97.305, 97.307(b)]`

Why is it not legal to transmit a 3 kHz bandwidth USB signal with a carrier frequency of 14.348 MHz?

- A. USB is not used on 20-meter phone
- B. The lower 1 kHz of the signal is outside the 20-meter band
- C. 14.348 MHz is outside the 20-meter band
- **D. The upper 1 kHz of the signal is outside the 20-meter band**  ←

**E1A02** &nbsp;·&nbsp; `[97.301, 97.305]`

When using a transceiver that displays the carrier frequency of phone signals, which of the following displayed frequencies represents the lowest frequency at which a properly adjusted LSB emission will be totally within the band?

- A. The exact lower band edge
- B. 300 Hz above the lower band edge
- C. 1 kHz above the lower band edge
- **D. 3 kHz above the lower band edge**  ←

**E1A03** &nbsp;·&nbsp; `[97.305, 97.307(b)]`

What is the highest legal carrier frequency on the 20-meter band for transmitting a 2.8 kHz wide USB data signal?

- A. 14.0708 MHz
- B. 14.1002 MHz
- **C. 14.1472 MHz**  ←
- D. 14.3490 MHz

**E1A04** &nbsp;·&nbsp; `[97.301, 97.305]`

May an Extra class operator answer the CQ of a station on 3.601 MHz LSB phone?

- A. Yes, the entire signal will be inside the SSB allocation for Extra class operators
- B. Yes, the displayed frequency is within the 75-meter phone band segment
- **C. No, the sideband components will extend beyond the edge of the phone band segment**  ←
- D. No, US stations are not permitted to use phone emissions below 3.610 MHz

**E1A05** &nbsp;·&nbsp; `[97.5]`

Who must be in physical control of the station apparatus of an amateur station aboard any vessel or craft that is documented or registered in the United States?

- A. Only a person with an FCC Marine Radio license grant
- B. Only a person named in an amateur station license grant
- **C. Any person holding an FCC issued amateur license or who is authorized for alien reciprocal operation**  ←
- D. Any person named in an amateur station license grant or a person holding an unrestricted Radiotelephone Operator Permit

**E1A06** &nbsp;·&nbsp; `[97.303(h)(1)]`

What is the required transmit frequency of a CW signal for channelized 60 meter operation?

- A. At the lowest frequency of the channel
- **B. At the center frequency of the channel**  ←
- C. At the highest frequency of the channel
- D. On any frequency where the signal’s sidebands are within the channel

**E1A07** &nbsp;·&nbsp; `[97.313(k)]`

What is the maximum power permitted on the 2200-meter band?

- A. 50 watts PEP (peak envelope power)
- B. 100 watts PEP (peak envelope power)
- **C. 1 watt EIRP (equivalent isotropic radiated power)**  ←
- D. 5 watts EIRP (equivalent isotropic radiated power)

**E1A08** &nbsp;·&nbsp; `[97.219]`

If a station in a message forwarding system inadvertently forwards a message that is in violation of FCC rules, who is primarily accountable for the rules violation?

- A. The control operator of the packet bulletin board station
- **B. The control operator of the originating station**  ←
- C. The control operators of all the stations in the system
- D. The control operators of all the stations in the system not authenticating the source from which they accept communications

**E1A09** &nbsp;·&nbsp; `[97.313(l)]`

Except in some parts of Alaska, what is the maximum power permitted on the 630-meter band?

- A. 50 watts PEP (peak envelope power)
- B. 100 watts PEP (peak envelope power)
- C. 1 watt EIRP (equivalent isotropic radiated power)
- **D. 5 watts EIRP (equivalent isotropic radiated power)**  ←

**E1A10** &nbsp;·&nbsp; `[97.11]`

If an amateur station is installed aboard a ship or aircraft, what condition must be met before the station is operated?

- **A. Its operation must be approved by the master of the ship or the pilot in command of the aircraft**  ←
- B. The amateur station operator must agree not to transmit when the main radio of the ship or aircraft is in use
- C. The amateur station must have a power supply that is completely independent of the main ship or aircraft power supply
- D. The amateur station must operate only in specific segments of the amateur service HF and VHF bands

**E1A11** &nbsp;·&nbsp; `[97.5]`

What licensing is required when operating an amateur station aboard a US-registered vessel in international waters?

- A. Any amateur license with an FCC Marine or Aircraft endorsement
- **B. Any FCC-issued amateur license**  ←
- C. Only General class or higher amateur licenses
- D. An unrestricted Radiotelephone Operator Permit

---

## E1B — Station restrictions and special operations: restrictions on station location; general operating restrictions; spurious emissions; antenna structure restrictions; RACES operations

*One exam question comes from this group. 11 questions in the pool.*

**Spurious emissions**, by FCC definition, are emissions **outside the necessary bandwidth** that
can be reduced or eliminated without affecting the transmitted information — not simply any
interfering signal, and not the same thing as an unidentified transmission.

**Bandwidth and distance numbers.** Digital voice and slow-scan TV on the HF bands are limited to
**3 kHz**. An amateur station must protect any **FCC monitoring facility** from harmful interference
within **1 mile** of it.

**Interference obligations run both ways.** A 70-cm repeater that interferes with a radiolocation
system must **cease operation or make changes that mitigate the interference** — there's no
HAAT-reduction or NOTAM-filing shortcut. When an amateur station's signal bothers
*good-engineering-design* broadcast receivers, the FCC's remedy is narrower than shutting the
station down entirely: it may require the amateur to **avoid transmitting during certain hours** on
the offending frequencies.

**The National Radio Quiet Zone** surrounds the **National Radio Astronomy Observatory** — not the
FCC's own monitoring station and not a military test range.

**Antenna structures near public-use airports** may trigger a requirement to **notify the FAA and
register with the FCC under Part 17**.

**PRB-1** governs **state and local zoning** of antenna structures (not HOAs, not FAA height rules)
and requires that amateur communications be **reasonably accommodated**.

**RACES** is open to **any FCC-licensed amateur station certified by the responsible civil defense
organization** for the area served, and such a station may use **all amateur frequencies authorized
to its control operator** — RACES doesn't carve out a separate, narrower set of channels.

#### All 11 pool questions for E1B

**E1B01** &nbsp;·&nbsp; `[97.3]`

Which of the following constitutes a spurious emission?

- A. An amateur station transmission made without the proper call sign identification
- B. A signal transmitted to prevent its detection by any station other than the intended recipient
- C. Any transmitted signal that unintentionally interferes with another licensed radio station and whose levels exceed 40 dB below the fundamental power level
- **D. An emission outside the signal’s necessary bandwidth that can be reduced or eliminated without affecting the information transmitted**  ←

**E1B02** &nbsp;·&nbsp; `[97.307(f)(2)]`

Which of the following is an acceptable bandwidth for digital voice or slow-scan TV transmissions made on the HF amateur bands?

- **A. 3 kHz**  ←
- B. 10 kHz
- C. 15 kHz
- D. 20 kHz

**E1B03** &nbsp;·&nbsp; `[97.13]`

Within what distance must an amateur station protect an FCC monitoring facility from harmful interference?

- **A. 1 mile**  ←
- B. 3 miles
- C. 10 miles
- D. 30 miles

**E1B04** &nbsp;·&nbsp; `[97.303(b)]`

What must the control operator of a repeater operating in the 70-centimeter band do if a radiolocation system experiences interference from that repeater?

- A. Reduce the repeater antenna HAAT (Height Above Average Terrain)
- B. File an FAA NOTAM (Notice to Air Missions) with the repeater system's ERP, call sign, and six-character grid locator
- **C. Cease operation or make changes to the repeater that mitigate the interference**  ←
- D. All these choices are correct

**E1B05** &nbsp;·&nbsp; `[97.3]`

What is the National Radio Quiet Zone?

- A. An area surrounding the FCC monitoring station in Laurel, Maryland
- B. An area in New Mexico surrounding the White Sands Test Area
- **C. An area surrounding the National Radio Astronomy Observatory**  ←
- D. An area in Florida surrounding Cape Canaveral

**E1B06** &nbsp;·&nbsp; `[97.15]`

Which of the following additional rules apply if you are erecting an amateur station antenna structure at a site at or near a public use airport?

- **A. You may have to notify the Federal Aviation Administration and register it with the FCC as required by Part 17 of the FCC rules**  ←
- B. You may have to enter the height above ground in meters, and the latitude and longitude in degrees, minutes, and seconds on the FAA website
- C. You must file an Environmental Impact Statement with the EPA before construction begins
- D. You must obtain a construction permit from the airport zoning authority per Part 119 of the FAA regulations

**E1B07** &nbsp;·&nbsp; `[97.15]`

To what type of regulations does PRB-1 apply?

- A. Homeowners associations
- B. FAA tower height limits
- **C. State and local zoning**  ←
- D. Use of wireless devices in vehicles

**E1B08** &nbsp;·&nbsp; `[97.121]`

What limitations may the FCC place on an amateur station if its signal causes interference to domestic broadcast reception, assuming that the receivers involved are of good engineering design?

- A. The amateur station must cease operation
- B. The amateur station must cease operation on all frequencies below 30 MHz
- C. The amateur station must cease operation on all frequencies above 30 MHz
- **D. The amateur station must avoid transmitting during certain hours on frequencies that cause the interference**  ←

**E1B09** &nbsp;·&nbsp; `[97.407]`

Which amateur stations may be operated under RACES rules?

- A. Only those club stations licensed to Amateur Extra class operators
- B. Any FCC-licensed amateur station except a Technician class
- **C. Any FCC-licensed amateur station certified by the responsible civil defense organization for the area served**  ←
- D. Only stations meeting the FCC Part 97 technical standards for operation during an emergency

**E1B10** &nbsp;·&nbsp; `[97.407]`

What frequencies are authorized to an amateur station operating under RACES rules?

- **A. All amateur service frequencies authorized to the control operator**  ←
- B. Specific segments in the amateur service MF, HF, VHF, and UHF bands
- C. Specific local government channels
- D. All these choices are correct

**E1B11** &nbsp;·&nbsp; `[97.15]`

What does PRB-1 require of state and local regulations affecting amateur radio antenna size and structures?

- A. No limitations may be placed on antenna size or placement
- **B. Reasonable accommodations of amateur radio must be made**  ←
- C. Such structures must be permitted when use for emergency communications can be demonstrated
- D. Such structures must be permitted if certified by a registered professional engineer

---

## E1C — Automatic and remote control; band-specific regulations; operating in and communicating with foreign countries; spurious emission standards; HF modulation index limit; band-specific rules

*One exam question comes from this group. 12 questions in the pool.*

**60-meter data bandwidth** tops out at **2.8 kHz** — the same figure as the 60-meter USB voice
limit, which makes it easy to remember as "one number for the whole band."

**Foreign communications content.** Messages to amateur stations in foreign countries must be
limited to matters **incidental to the purpose of the amateur service and remarks of a personal
nature** — there's no blanket English-language requirement and no NGO-only carve-out for
third-party traffic.

**630/2200-meter notification.** Before operating on either band, you must notify the **Utilities
Technology Council (UTC)** of your call sign and station coordinates. You may then operate after
**30 days**, provided you haven't been told your station sits within **1 kilometer** of a Power
Line Carrier (PLC) system using those frequencies — no separate approval or test-signal step is
required.

**IARP vs. CEPT.** An **IARP** is a permit letting US amateurs operate in certain countries **of the
Americas**. **CEPT** is the separate European reciprocal arrangement — to operate under it you need
a copy of **FCC Public Notice DA 16-1048**, not an embassy sign-off or a "/CEPT" call sign suffix.

**Automatic control and third parties.** A station under automatic control may transmit
**third-party communications only when sending RTTY or data emissions** — SSB and CW are excluded
from that exception.

**Remote control failsafe.** If a remotely controlled station's control link fails, its
transmissions may continue for no more than **3 minutes** before they must stop.

**Two more numbers to fix in memory:** the highest permitted **modulation index** for angle
modulation below 29.0 MHz is **1.0**, and the maximum mean power for a spurious emission below
30 MHz is **-43 dB** relative to the fundamental.

#### All 12 pool questions for E1C

**E1C01** &nbsp;·&nbsp; `[97.303]`

What is the maximum bandwidth for a data emission on 60 meters?

- A. 60 Hz
- B. 170 Hz
- C. 1.5 kHz
- **D. 2.8 kHz**  ←

**E1C02** &nbsp;·&nbsp; `[97.117]`

Which of the following apply to communications transmitted to amateur stations in foreign countries?

- A. Third party traffic must be limited to that intended for the exclusive use of government and non-Government Organization (NGOs) involved in emergency relief activities
- B. All transmissions must be in English
- **C. Communications must be limited to those incidental to the purpose of the amateur service and remarks of a personal nature**  ←
- D. All these choices are correct

**E1C03** &nbsp;·&nbsp; `[97.303(g)]`

How long must an operator wait after filing a notification with the Utilities Technology Council (UTC) before operating on the 2200-meter or 630-meter band?

- A. Operators must not operate until approval is received
- **B. Operators may operate after 30 days, providing they have not been told that their station is within 1 kilometer of PLC systems using those frequencies**  ←
- C. Operators may not operate until a test signal has been transmitted in coordination with the local power company
- D. Operations may commence immediately, and may continue unless interference is reported by the UTC

**E1C04**

What is an IARP?

- **A. A permit that allows US amateurs to operate in certain countries of the Americas**  ←
- B. The internal amateur radio practices policy of the FCC
- C. An indication of increased antenna reflected power
- D. A forecast of intermittent aurora radio propagation

**E1C05** &nbsp;·&nbsp; `[97.221(c)(1), 97.115(c)]`

Under what situation may a station transmit third party communications while being automatically controlled?

- A. Never
- **B. Only when transmitting RTTY or data emissions**  ←
- C. Only when transmitting SSB or CW
- D. On any mode approved by the National Telecommunication and Information Administration

**E1C06**

Which of the following is required in order to operate in accordance with CEPT rules in foreign countries where permitted?

- A. You must identify in the official language of the country in which you are operating
- B. The US embassy must approve of your operation
- **C. You must have a copy of FCC Public Notice DA 16-1048**  ←
- D. You must append "/CEPT" to your call sign

**E1C07** &nbsp;·&nbsp; `[97.303(g)]`

What notifications must be given before transmitting on the 630- or 2200-meter bands?

- A. A special endorsement must be requested from the FCC
- B. An environmental impact statement must be filed with the Department of the Interior
- C. Operators must inform the FAA of their intent to operate, giving their call sign and distance to the nearest runway
- **D. Operators must inform the Utilities Technology Council (UTC) of their call sign and coordinates of the station**  ←

**E1C08** &nbsp;·&nbsp; `[97.213]`

What is the maximum permissible duration of a remotely controlled station’s transmissions if its control link malfunctions?

- A. 30 seconds
- **B. 3 minutes**  ←
- C. 5 minutes
- D. 10 minutes

**E1C09** &nbsp;·&nbsp; `[97.307]`

What is the highest modulation index permitted at the highest modulation frequency for angle modulation below 29.0 MHz?

- A. 0.5
- **B. 1.0**  ←
- C. 2.0
- D. 3.0

**E1C10** &nbsp;·&nbsp; `[97.307]`

What is the maximum mean power level for a spurious emission below 30 MHz with respect to the fundamental emission?

- **A. - 43 dB**  ←
- B. - 53 dB
- C. - 63 dB
- D. - 73 dB

**E1C11** &nbsp;·&nbsp; `[97.5]`

Which of the following operating arrangements allows an FCC-licensed US citizen to operate in many European countries, and amateurs from many European countries to operate in the US?

- **A. CEPT**  ←
- B. IARP
- C. ITU reciprocal license
- D. All these choices are correct

**E1C12** &nbsp;·&nbsp; `[97.305(c)]`

In what portion of the 630-meter band are phone emissions permitted?

- A. None
- B. Only the top 3 kHz
- C. Only the bottom 3 kHz
- **D. The entire band**  ←

---

## E1D — Amateur Space and Earth stations; telemetry and telecommand rules; identification of balloon transmissions; one-way communications

*One exam question comes from this group. 12 questions in the pool.*

**Telemetry vs. telecommand — opposite directions.** Telemetry is a **one-way transmission of
measurements** from the thing being measured. Telecommand is the reverse: a transmission that
**initiates, modifies, or terminates functions of a device** at a distance. A **space telecommand
station** is specifically one that sends telecommand signals to a **space station**.

**Encryption exception.** Amateur rules generally forbid obscuring the meaning of communications,
but **telecommand signals from a space telecommand station** are explicitly allowed to be
encrypted — terrestrial repeater telecommand, auxiliary relay links, and mesh backbone nodes get no
such exception.

**Balloon telemetry identification** requires only a **call sign** — not power output, not a grid
locator, and Part 97 doesn't ask for both.

**Posting requirement for telecommand stations** operating on or within 50 kilometers of the
Earth’s surface: a label with the **name, address, and telephone number of the station licensee**.

**Power cap for model craft by telecommand:** **1 watt**.

**Space station band allocations are specific, not "wherever."** HF: **40, 20, 15, and 10 meters**.
VHF: **2 meters only**. UHF: **70 centimeters and 13 centimeters**. Memorize these as a short list
rather than assuming satellite operation is permitted broadly across the bands.

**Eligibility is privilege-based, not credential-based.** Any amateur station **designated by the
space station licensee** may serve as its telecommand station, and any amateur station may operate
as an **Earth station**, subject to the ordinary privileges of the control operator's license
class — no AMSAT course, no minimum license class, and no ITU designation required.

**One-way transmissions** are permitted specifically from a **space station, beacon station, or
telecommand station** — not from repeaters or message-forwarding stations.

#### All 12 pool questions for E1D

**E1D01** &nbsp;·&nbsp; `[97.3]`

What is the definition of telemetry?

- **A. One-way transmission of measurements at a distance from the measuring instrument**  ←
- B. Two-way transmissions in excess of 1000 feet
- C. Two-way transmissions of data
- D. One-way transmission that initiates, modifies, or terminates the functions of a device at a distance

**E1D02** &nbsp;·&nbsp; `[97.211(b)]`

Which of the following may transmit encrypted messages?

- A. Telecommand signals to terrestrial repeaters
- **B. Telecommand signals from a space telecommand station**  ←
- C. Auxiliary relay links carrying repeater audio
- D. Mesh network backbone nodes

**E1D03** &nbsp;·&nbsp; `[97.3(a)(45)]`

What is a space telecommand station?

- A. An amateur station located on the surface of the Earth for communication with other Earth stations by means of Earth satellites
- **B. An amateur station that transmits communications to initiate, modify, or terminate functions of a space station**  ←
- C. An amateur station located in a satellite or a balloon more than 50 kilometers above the surface of the Earth
- D. An amateur station that receives telemetry from a satellite or balloon more than 50 kilometers above the surface of the Earth

**E1D04** &nbsp;·&nbsp; `[97.119(a)]`

Which of the following is required in the identification transmissions from a balloon-borne telemetry station?

- **A. Call sign**  ←
- B. The output power of the balloon transmitter
- C. The station's six-character Maidenhead grid locator
- D. All these choices are correct

**E1D05** &nbsp;·&nbsp; `[97.213(d)]`

What must be posted at the location of a station being operated by telecommand on or within 50 kilometers of the Earth’s surface?

- A. A photocopy of the station license
- B. A label with the name, address, and telephone number of the station licensee
- C. A label with the name, address, and telephone number of the control operator
- **D. All these choices are correct**  ←

**E1D06** &nbsp;·&nbsp; `[97.215(c)]`

What is the maximum permitted transmitter output power when operating a model craft by telecommand?

- **A. 1 watt**  ←
- B. 2 watts
- C. 5 watts
- D. 100 watts

**E1D07** &nbsp;·&nbsp; `[97.207]`

Which of the following HF amateur bands include allocations for space stations?

- **A. 40 meters, 20 meters, 15 meters, and 10 meters**  ←
- B. 30 meters, 17 meters, and 10 meters
- C. Only 10 meters
- D. Satellite operation is permitted on all HF bands

**E1D08** &nbsp;·&nbsp; `[97.207]`

Which VHF amateur bands have frequencies authorized for space stations?

- A. 6 meters and 2 meters
- B. 6 meters, 2 meters, and 1.25 meters
- C. 2 meters and 1.25 meters
- **D. 2 meters**  ←

**E1D09** &nbsp;·&nbsp; `[97.207]`

Which UHF amateur bands have frequencies authorized for space stations?

- A. 70 centimeters only
- **B. 70 centimeters and 13 centimeters**  ←
- C. 70 centimeters and 33 centimeters
- D. 33 centimeters and 13 centimeters

**E1D10** &nbsp;·&nbsp; `[97.211]`

Which amateur stations are eligible to be telecommand stations of space stations, subject to the privileges of the class of operator license held by the control operator of the station?

- A. Any amateur station approved by AMSAT
- **B. Any amateur station so designated by the space station licensee**  ←
- C. Any amateur station so designated by the ITU
- D. All these choices are correct

**E1D11** &nbsp;·&nbsp; `[97.209]`

Which amateur stations are eligible to operate as Earth stations?

- A. Any amateur licensee who has successfully completed the AMSAT space communications course
- B. Only those of General, Advanced or Amateur Extra class operators
- C. Only those of Amateur Extra class operators
- **D. Any amateur station, subject to the privileges of the class of operator license held by the control operator**  ←

**E1D12** &nbsp;·&nbsp; `[97.207(e), 97.203(g)]`

Which of the following amateur stations may transmit one-way communications?

- **A. A space station, beacon station, or telecommand station**  ←
- B. A local repeater or linked repeater station
- C. A message forwarding station or automatically controlled digital station
- D. All these choices are correct

---

## E1E — Volunteer examiner program: definitions; qualifications; preparation and administration of exams; reimbursement; accreditation; question pools; documentation requirements

*One exam question comes from this group. 11 questions in the pool.*

**Reimbursement** covers only the **out-of-pocket costs of preparing, processing, administering,
and coordinating an exam session** — not teaching a prep course and not providing prep materials.

**Who does what.** **VECs** maintain the question pools for all US amateur exams (not the FCC, and
not the ARRL directly). A **VEC** itself is an organization that has an **agreement with the FCC**
to coordinate, prepare, and administer exams — being a VE is a separate role from being a VEC.
Accreditation as a **VE** requires a **VEC to confirm** the applicant meets FCC requirements; there's
no automatic accreditation on upgrade and no FCC-administered VE exam.

**Paperwork flow.** If an examinee **fails**, the VE team **returns the application document to the
examinee** — it isn't sent to the FCC and it isn't destroyed. If the examinee **passes** every
element needed for the grant, **three VEs must certify** that the candidate is qualified and that the
administering requirements were met; the VEs then **submit the application to the coordinating VEC**,
following that VEC's own instructions — neither the FCC nor the applicant is the direct recipient of
that document.

**Conduct and eligibility during a session.** **Each administering VE** — not a single "session
manager" — is responsible for proper conduct and supervision. A candidate who won't follow
instructions gets their **exam terminated immediately** (not just warned, and it doesn't shut down
the whole session). A VE **cannot examine relatives**, specifically those listed in the FCC's own
rules.

**Fraud is punished on two license grants at once**: a VE who fraudulently administers or certifies
an exam risks **revocation of the station license grant and suspension of the operator license
grant** together.

#### All 11 pool questions for E1E

**E1E01** &nbsp;·&nbsp; `[97.527]`

For which types of out-of-pocket expenses do the Part 97 rules state that VEs and VECs may be reimbursed?

- **A. Preparing, processing, administering, and coordinating an examination for an amateur radio operator license**  ←
- B. Teaching an amateur operator license examination preparation course
- C. No expenses are authorized for reimbursement
- D. Providing amateur operator license examination preparation training materials

**E1E02** &nbsp;·&nbsp; `[97.523]`

Who is tasked by Part 97 with maintaining the pools of questions for all US amateur license examinations?

- A. The VEs
- B. The FCC
- **C. The VECs**  ←
- D. The ARRL

**E1E03** &nbsp;·&nbsp; `[97.521]`

What is a Volunteer Examiner Coordinator?

- A. A person who has volunteered to administer amateur operator license examinations
- B. An organization paid by the volunteer examiner team to publicize and schedule examinations
- **C. An organization that has entered into an agreement with the FCC to coordinate, prepare, and administer amateur operator license examinations**  ←
- D. The person who has entered into an agreement with the FCC to be the VE session manager

**E1E04** &nbsp;·&nbsp; `[97.509, 97.525]`

What is required to be accredited as a Volunteer Examiner?

- A. Each General, Advanced and Amateur Extra class operator is automatically accredited as a VE when the license is granted
- B. The amateur operator applying must pass a VE examination administered by the FCC Enforcement Bureau
- C. The prospective VE must obtain accreditation from the FCC
- **D. A VEC must confirm that the VE applicant meets FCC requirements to serve as an examiner**  ←

**E1E05** &nbsp;·&nbsp; `[97.509(j)]`

What must the VE team do with the application form if the examinee does not pass the exam?

- A. Maintain the application form with the VEC’s records
- **B. Return the application document to the examinee**  ←
- C. Send the application form to the FCC and inform the FCC of the grade
- D. Destroy the application form

**E1E06** &nbsp;·&nbsp; `[97.509]`

Who is responsible for the proper conduct and necessary supervision during an amateur operator license examination session?

- A. The VEC coordinating the session
- B. The designated monitoring VE
- **C. Each administering VE**  ←
- D. Only the VE session manager

**E1E07** &nbsp;·&nbsp; `[97.509, 97.511]`

What should a VE do if a candidate fails to comply with the examiner’s instructions during an amateur operator license examination?

- A. Warn the candidate that continued failure to comply will result in termination of the examination
- **B. Immediately terminate the candidate’s examination**  ←
- C. Allow the candidate to complete the examination, but invalidate the results
- D. Immediately terminate everyone’s examination and close the session

**E1E08** &nbsp;·&nbsp; `[97.509]`

To which of the following examinees may a VE not administer an examination?

- A. Employees of the VE
- B. Friends of the VE
- **C. Relatives of the VE as listed in the FCC rules**  ←
- D. All these choices are correct

**E1E09** &nbsp;·&nbsp; `[97.509]`

What may be the penalty for a VE who fraudulently administers or certifies an examination?

- **A. Revocation of the VE’s amateur station license grant and the suspension of the VE’s amateur operator license grant**  ←
- B. A fine of up to $1,000 per occurrence
- C. A sentence of up to one year in prison
- D. All these choices are correct

**E1E10** &nbsp;·&nbsp; `[97.509(m)]`

What must the administering VEs do after the administration of a successful examination for an amateur operator license?

- A. They must collect and send the documents directly to the FCC
- B. They must collect and submit the documents to the coordinating VEC for grading
- **C. They must submit the application document to the coordinating VEC according to the coordinating VEC instructions**  ←
- D. They must return the documents to the applicant for submission to the FCC according to the FCC instructions

**E1E11** &nbsp;·&nbsp; `[97.509(i)]`

What must the VE team do if an examinee scores a passing grade on all examination elements needed for an upgrade or new license?

- A. Photocopy all examination documents and forward them to the FCC for processing
- **B. Three VEs must certify that the examinee is qualified for the license grant and that they have complied with the administering VE requirements**  ←
- C. Issue the examinee the new or upgrade license
- D. All these choices are correct

---

## E1F — Miscellaneous rules: external RF power amplifiers; prohibited communications; spread spectrum; auxiliary stations; Canadian amateurs operating in the US; special temporary authority

*One exam question comes from this group. 11 questions in the pool.*

**Spread spectrum** is permitted only **above 222 MHz** — nowhere on HF or the lower VHF bands.

**Canadian reciprocal privileges** in the US track the operator's **own Canadian license terms and
conditions**, capped at whatever **US Amateur Extra class privileges** allow — it's not a flat
General-class or full-Extra grant regardless of the Canadian license held.

**Selling an uncertificated external RF amplifier** (capable of operating below 144 MHz) is legal
specifically when it was **constructed or modified by an amateur radio operator for use at an
amateur station** — kit-built, low-gain, or foreign-certificated units don't get the same exception.

**"Line A"** runs roughly parallel to, and **south of, the US–Canada border**. North of Line A in the
contiguous 48 states, amateurs may **not transmit in 420–430 MHz** — a slice of the 70-cm band
carved out to avoid interfering with Canadian and radar allocations.

**Special Temporary Authority (STA)** exists to permit things like **experimental amateur
communications** — it isn't the mechanism for special event call signs, reduced VE-team sizes, or
early use of upgraded privileges.

**The pecuniary-interest test for business messages.** A message to a business is allowed
specifically when **neither the amateur nor their employer has a pecuniary interest** in it — there's
no dollar-threshold exception. More broadly, communications transmitted **for hire or material
compensation** are prohibited except where Part 97 otherwise allows it, and messages **encoded to
obscure their meaning** cannot be sent over an amateur mesh network.

**Auxiliary stations** may be controlled by **Technician, General, Advanced, or Amateur Extra**
operators — Novice is the one class excluded.

**Amplifier certification standard.** To be FCC-certificated, an external RF amplifier must meet the
FCC's **spurious emission standards** when operated at the **lesser of 1500 watts or its full output
power**.

#### All 11 pool questions for E1F

**E1F01** &nbsp;·&nbsp; `[97.305]`

On what frequencies are spread spectrum transmissions permitted?

- A. Only on amateur frequencies above 50 MHz
- **B. Only on amateur frequencies above 222 MHz**  ←
- C. Only on amateur frequencies above 420 MHz
- D. Only on amateur frequencies above 144 MHz

**E1F02** &nbsp;·&nbsp; `[97.107]`

What privileges are authorized in the US to persons holding an amateur service license granted by the government of Canada?

- A. None, they must obtain a US license
- B. Full privileges of the General class license on the 80-, 40-, 20-, 15-, and 10-meter bands
- **C. The operating terms and conditions of the Canadian amateur service license, not to exceed US Amateur Extra class license privileges**  ←
- D. Full privileges, up to and including those of the Amateur Extra class license, on the 80-, 40-, 20-, 15-, and 10-meter bands

**E1F03** &nbsp;·&nbsp; `[97.315]`

Under what circumstances may a dealer sell an external RF power amplifier capable of operation below 144 MHz if it has not been granted FCC certification?

- A. Gain is less than 23 dB when driven by power of 10 watts or less
- B. The equipment dealer assembled it from a kit
- C. It was manufactured and certificated in a country which has a reciprocal certification agreement with the FCC
- **D. The amplifier is constructed or modified by an amateur radio operator for use at an amateur station**  ←

**E1F04** &nbsp;·&nbsp; `[97.3]`

Which of the following geographic descriptions approximately describes "Line A"?

- **A. A line roughly parallel to and south of the border between the US and Canada**  ←
- B. A line roughly parallel to and west of the US Atlantic coastline
- C. A line roughly parallel to and north of the border between the US and Mexico
- D. A line roughly parallel to and east of the US Pacific coastline

**E1F05** &nbsp;·&nbsp; `[97.303]`

Amateur stations may not transmit in which of the following frequency segments if they are located in the contiguous 48 states and north of Line A?

- A. 440 MHz - 450 MHz
- B. 53 MHz - 54 MHz
- C. 222 MHz - 223 MHz
- **D. 420 MHz - 430 MHz**  ←

**E1F06** &nbsp;·&nbsp; `[1.931]`

Under what circumstances might the FCC issue a Special Temporary Authority (STA) to an amateur station?

- **A. To provide for experimental amateur communications**  ←
- B. To allow use of a special event call sign
- C. To allow a VE group with less than three VEs to administer examinations in a remote, sparsely populated area
- D. To allow a licensee who has passed an upgrade exam to operate with upgraded privileges while waiting for posting on the FCC database

**E1F07** &nbsp;·&nbsp; `[97.113]`

When may an amateur station send a message to a business?

- A. When the pecuniary interest of the amateur or his or her employer is less than $25
- B. When the pecuniary interest of the amateur or his or her employer is less than $50
- C. At no time
- **D. When neither the amateur nor their employer has a pecuniary interest in the communications**  ←

**E1F08** &nbsp;·&nbsp; `[97.113(c)]`

Which of the following types of amateur station communications are prohibited?

- **A. Communications transmitted for hire or material compensation, except as otherwise provided in the rules**  ←
- B. Communications that have political content, except as allowed by the Fairness Doctrine
- C. Communications that have religious content
- D. Communications in a language other than English

**E1F09** &nbsp;·&nbsp; `[FCC Part 97.113(a)(4)]`

Which of the following cannot be transmitted over an amateur radio mesh network?

- A. Third party traffic
- B. Email
- **C. Messages encoded to obscure their meaning**  ←
- D. All these choices are correct

**E1F10** &nbsp;·&nbsp; `[97.201]`

Who may be the control operator of an auxiliary station?

- A. Any licensed amateur operator
- **B. Only Technician, General, Advanced, or Amateur Extra class operators**  ←
- C. Only General, Advanced, or Amateur Extra class operators
- D. Only Amateur Extra class operators

**E1F11** &nbsp;·&nbsp; `[97.317]`

Which of the following best describes one of the standards that must be met by an external RF power amplifier if it is to qualify for a grant of FCC certification?

- A. It must produce full legal output when driven by not more than 5 watts of mean RF input power
- B. It must have received an Underwriters Laboratory certification for electrical safety as well as having met IEEE standard 14.101(B)
- C. It must exhibit a gain of less than 23 dB when driven by 10 watts or less
- **D. It must satisfy the FCC’s spurious emission standards when operated at the lesser of 1500 watts or its full output power**  ←
