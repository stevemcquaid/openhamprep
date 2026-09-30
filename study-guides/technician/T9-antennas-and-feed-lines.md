# T9 — Antennas and Feed Lines

**2 of your 35 exam questions · 2 groups (T9A–T9B) · 23 questions in the pool**

This subelement covers the practical side of getting RF from your radio into the air: basic
antenna types and behavior (polarization, gain, loading, beam antennas, common VHF/UHF whips),
plus feed lines, connectors, and the basics of SWR and antenna tuners. It's almost entirely
plain-language, real-world knowledge — no math beyond intuition about "shorter antenna, higher
resonant frequency."

Along with T0 and G0, this is one of the smallest subelements in its pool — just two groups and
23 questions feeding two exam questions. It's worth mastering completely, since it's cheap to
learn fully. General's G9 revisits nearly all the same vocabulary (polarization, gain, feed
lines, SWR) but goes much deeper — dB gain figures, transmission line impedance matching math,
and half- and full-wave line sections. T9 only asks you to know the vocabulary and the practical
facts.

## Table of Contents

- [T9A — Antennas: vertical and horizontal polarization, concept of antenna gain, definition and types of beam antennas, antenna loading, common portable and mobile antennas, relationships between resonant length and frequency, dipole pattern](#t9a--antennas-vertical-and-horizontal-polarization-concept-of-antenna-gain-definition-and-types-of-beam-antennas-antenna-loading-common-portable-and-mobile-antennas-relationships-between-resonant-length-and-frequency-dipole-pattern)
  - [All 11 pool questions for T9A](#all-11-pool-questions-for-t9a)
- [T9B — Feed lines: types, attenuation vs frequency, selecting; SWR concepts; Antenna tuners (couplers); RF Connectors: selecting, weather protection](#t9b--feed-lines-types-attenuation-vs-frequency-selecting-swr-concepts-antenna-tuners-couplers-rf-connectors-selecting-weather-protection)
  - [All 12 pool questions for T9B](#all-12-pool-questions-for-t9b)

---

## T9A — Antennas: vertical and horizontal polarization, concept of antenna gain, definition and types of beam antennas, antenna loading, common portable and mobile antennas, relationships between resonant length and frequency, dipole pattern

*One exam question comes from this group. 11 questions in the pool.*

**Beam antennas** concentrate signal in one direction rather than radiating equally all around —
that's the whole definition, no exotic hardware implied by the name. Of the antenna types
commonly compared on this exam, the **Yagi has the greatest gain**, beating a 5/8-wave vertical,
a J-pole, and (by definition) the isotropic reference antenna itself. **Antenna gain** is defined
as the **increase in signal strength in a specified direction compared to a reference antenna** —
gain doesn't add transmitter power, it redirects the power you already have.

**Polarization** is described by the **orientation of the electric field**, not the magnetic
field and not the antenna's physical shape.

**Antenna loading** electrically lengthens a physically short antenna by **inserting inductors
in the radiating elements** — this is how a stubby mobile whip can still be resonant. Along
similar lines, **shortening** a dipole **increases its resonant frequency** (shorter = higher
frequency; this is the inverse of loading it longer with coils).

**Portable and mobile antennas, VHF/UHF specifics:**
- A handheld's **short flexible "rubber duck" antenna** has **low efficiency** compared to a
  full-size quarter-wave antenna — that's its main disadvantage, not polarization or digital
  compatibility.
- Using a handheld **inside a vehicle without an external antenna** reduces signal strength
  because the **vehicle body shields** the radio — the car acts like a Faraday cage.
- A **19-inch vertical** is common on 2 meters because it's a **resonant quarter-wave** antenna
  at that frequency (not a half-wave, and not chosen for low exposure or high gain).
- A **5/8-wavelength whip** beats a 1/4-wave whip for VHF/UHF mobile use because it has **more
  gain** — it produces a lower-angle radiation pattern that puts more signal toward the horizon,
  not lower SWR or lower impedance.

**Dipole radiation pattern:** a half-wave dipole radiates its strongest signal **broadside to the
antenna** (perpendicular to the wire), and is weakest off the ends.

#### All 11 pool questions for T9A

**T9A01**

What is a beam antenna?

- A. An antenna built from square aluminum beams
- B. An omnidirectional antenna invented by Clarence Beam
- C. An antenna that concentrates signals in one direction
- D. An antenna that focuses the signal into two intense rays
-
- Answer: C

**T9A02**

Which of the following describes a type of antenna loading?

- A. Electrically lengthening by inserting inductors in radiating elements
- B. Inserting a resistor in the radiating portion of the antenna to make it resonant
- C. Installing a spring in the base of a mobile vertical antenna to make it more flexible
- D. Strengthening the radiating elements of a beam antenna to better resist wind damage
-
- Answer: A

**T9A03**

How is the polarization of an antenna described?

- A. By the shape of the driven element
- B. By the orientation of the electric field
- C. By the orientation of the magnetic field
- D. By the direction of radiation
-
- Answer: B

**T9A04**

What is a disadvantage of a handheld radio transceiver's short flexible antenna compared to a full-sized quarter-wave antenna?

- A. It has low efficiency
- B. It transmits only circularly polarized signals
- C. It is more susceptible to receiver desensitization
- D. It only works on analog signals, not digital ones
-
- Answer: A

**T9A05**

Which of the following increases the resonant frequency of a dipole antenna?

- A. Lengthening it
- B. Inserting coils in series with radiating wires
- C. Shortening it
- D. Adding capacitive loading to the ends of the radiating wires
-
- Answer: C

**T9A06**

Which of the following types of antennas offers the greatest gain?

- A. 5/8 wave vertical
- B. Isotropic
- C. J pole
- D. Yagi
-
- Answer: D

**T9A07**

What is a potential drawback of using a handheld VHF transceiver inside a vehicle that lacks an externally mounted antenna?

- A. Signal strength is reduced due to the shielding effect of the vehicle
- B. The bandwidth of the antenna will decrease, increasing SWR
- C. The SWR might decrease, decreasing the signal strength
- D. The handheld will overheat due to reflected power in the vehicle
-
- Answer: A

**T9A08**

Why is a 19-inch-long vertical antenna often used on 2 meters?

- A. It has high gain
- B. It is a resonant half-wave
- C. It is a resonant quarter-wave
- D. It has low RF radiation exposure
-
- Answer: C

**T9A09**

What is an advantage of a 5/8-wavelength whip antenna for VHF or UHF mobile service compared to a 1/4-wave antenna?

- A. It has more gain
- B. It radiates at a higher angle
- C. It has lower SWR
- D. It has lower impedance
-
- Answer: A

**T9A10**

In which direction does a half-wave dipole antenna radiate the strongest signal?

- A. Equally in all directions
- B. Off the ends of the antenna
- C. In the direction of the feed line
- D. Broadside to the antenna
-
- Answer: D

**T9A11**

What is antenna gain?

- A. The additional power that is added to the transmitter power
- B. The additional power that is required in the antenna when transmitting on a higher frequency
- C. The increase in signal strength in a specified direction compared to a reference antenna
- D. The increase in impedance on receive or transmit compared to a reference antenna
-
- Answer: C

---

## T9B — Feed lines: types, attenuation vs frequency, selecting; SWR concepts; Antenna tuners (couplers); RF Connectors: selecting, weather protection

*One exam question comes from this group. 12 questions in the pool.*

**Coaxial cable** is the dominant feed line in amateur radio because it's **easy to use and
requires few special installation considerations** — not because it has the least loss, handles
the most power, or costs the least (other feed line types can beat coax on each of those). The
**most common coax impedance** used in amateur radio is **50 ohms**. As frequency **increases**,
**loss in coax increases** too — attenuation rises with frequency, which is why HF-length coax
runs are more forgiving than VHF/UHF ones.

**Loss sources in coaxial feed line** are cumulative and the exam rewards knowing they *all*
count: **water intrusion into connectors, high SWR, and multiple connectors in the line** are
all sources of loss ("all these choices are correct"). **Erratic, unstable changes in SWR** are
a classic symptom of a **loose connection** in the antenna or feed line — a real physical fault,
not weather or a strong nearby station.

**Comparing feed line loss:** of common types, **air-insulated hardline** has the **lowest
loss**. Between two coax types, **RG-213 has less loss than RG-58** at a given frequency —
RG-213 is simply the physically larger, lower-loss cable.

**Antenna tuners** (couplers) exist to **match the antenna system's impedance to the
transceiver's output impedance** — they don't select antennas automatically or help a receiver
find weak stations.

**SWR** (standing wave ratio) is fundamentally **a measure of how well a load is matched to a
transmission line** — not an amplifier efficiency figure and not a ground-quality indicator.

**Connectors:**
- **PL-259** connectors are **commonly used at HF and VHF frequencies** — not preferred for
  microwave use, and not watertight or bayonet-style on their own.
- **Type N** connectors are the best choice **above 400 MHz**.
- **All of PL-259, BNC, and Type N** need to be **carefully taped for weather protection** when
  used outdoors — none of them are weatherproof out of the box on this exam's logic.

#### All 12 pool questions for T9B

**T9B01**

Which of the following connectors should be carefully taped for weather protection when used outdoors?

- A. PL259
- B. BNC
- C. Type N
- D. All these choices are correct
-
- Answer: D

**T9B02**

What is the most common impedance of coaxial cables used in amateur radio?

- A. 8 ohms
- B. 50 ohms
- C. 600 ohms
- D. 12 ohms
-
- Answer: B

**T9B03**

Why is coaxial cable the most common feed line for amateur radio antenna systems?

- A. It is easy to use and requires few special installation considerations
- B. It has less loss than any other type of feed line
- C. It can handle more power than any other type of feed line
- D. It is less expensive than any other type of feed line
-
- Answer: A

**T9B04**

What is the major function of an antenna tuner (antenna coupler)?

- A. It matches the antenna system impedance to the transceiver's output impedance
- B. It helps a receiver automatically tune in weak stations
- C. It allows an antenna to be used on both transmit and receive
- D. It automatically selects the proper antenna for the frequency band being used
-
- Answer: A

**T9B05**

What happens as the frequency of a signal in coaxial cable is increased?

- A. The characteristic impedance decreases
- B. The loss decreases
- C. The characteristic impedance increases
- D. The loss increases
-
- Answer: D

**T9B06**

Which of the following connector types is most suitable as an RF connector for frequencies above 400 MHz?

- A. PL-259
- B. Type N
- C. RS-213
- D. DB-25
-
- Answer: B

**T9B07**

Which of the following is true of PL-259 type coax connectors?

- A. They are preferred for microwave operation
- B. They are watertight
- C. They are commonly used at HF and VHF frequencies
- D. They are a bayonet-type connector
-
- Answer: C

**T9B08**

Which of the following is a source of loss in coaxial feed line?

- A. Water intrusion into coaxial connectors
- B. High SWR
- C. Multiple connectors in the line
- D. All these choices are correct
-
- Answer: D

**T9B09**

What can cause erratic changes in SWR?

- A. Local thunderstorm
- B. Loose connection in the antenna or feed line
- C. Over-modulation
- D. Overload from a strong local station
-
- Answer: B

**T9B10**

What is the electrical difference between RG-58 and RG-213 coaxial cable?

- A. There is no significant difference between the two types
- B. RG-58 cable has two shields
- C. RG-213 cable has less loss at a given frequency
- D. RG-58 cable can handle higher power levels
-
- Answer: C

**T9B11**

Which of the following types of feed line has the lowest loss?

- A. 50-ohm flexible coax
- B. Multi-conductor unbalanced cable
- C. Air-insulated hardline
- D. 75-ohm flexible coax
-
- Answer: C

**T9B12**

What is standing wave ratio (SWR)?

- A. A measure of how well a load is matched to a transmission line
- B. The ratio of amplifier power output to input
- C. The transmitter efficiency ratio
- D. An indication of the quality of your station's ground connection
-
- Answer: A
