# T3 — Radio Wave Propagation

**3 of your 35 exam questions · 3 groups (T3A–T3C) · 35 questions in the pool**

This subelement covers how radio signals actually get from your antenna to someone else's: fading
and multipath, antenna polarization, the relationship between wavelength and frequency, where VHF,
UHF, and HF sit on the electromagnetic spectrum, and the handful of "beyond line of sight" tricks —
sporadic E, meteor scatter, auroral backscatter, tropospheric ducting, and F-region skip — that let
VHF/UHF and HF signals travel farther than you'd expect.

Compared to General's G3, which builds a full model of the ionosphere (sunspot numbers, K/A
indices, MUF/LUF, critical angle, NVIS), T3 stays much shallower — it names the propagation modes
and their headline facts without asking you to reason through *why* with numbers and formulas. It
is closer to short vocabulary recall than General-level analysis, which makes it a lighter lift per
question than G3 despite covering some of the same ground.

---

## T3A — Radio wave characteristics: how a radio signal travels, fading, multipath, polarization, wavelength vs absorption; Antenna orientation

*One exam question comes from this group. 12 questions in the pool.*

**Multipath is the recurring theme.** Signal strength swinging wildly when you move a VHF antenna a
few feet, "picket fencing" (rapid flutter on mobile signals), and irregular fading of
ionosphere-propagated signals are all **multipath propagation** — signals arriving by more than one
path combining, canceling, or reinforcing each other. On data transmissions, multipath's effect is
to **increase error rates**, not change the required transmission rate.

**Polarization.** For long-distance VHF/UHF CW and SSB contacts, **horizontal** polarization is
normal. Cross-polarizing your antenna relative to the other station's on a line-of-sight VHF/UHF
path **reduces received signal strength** — it doesn't invert sidebands or add an echo. Signals
propagated by the ionosphere come out **elliptically polarized**, which is why either vertically or
horizontally polarized antennas work fine for transmission or reception on those paths — you don't
need matched polarization for ionospheric contacts the way you do for line-of-sight ones.

**Absorption and obstructions.** Vegetation **absorbs** UHF and microwave signals, hurting weak-signal
reception. Precipitation (not wind, pressure, or cold) **decreases range at microwave frequencies**,
while fog or rain has **little effect** on 10-meter and 6-meter signals — attenuation from weather
only really bites at microwave. When buildings block a direct path to a repeater, try to find a path
that **reflects** signals to the repeater rather than changing polarization or increasing SWR. The
**ionosphere** is the region that reflects HF radio waves back to Earth.

#### All 12 pool questions for T3A

**T3A01**

Why do VHF signal strengths sometimes vary greatly when the antenna is moved only a few feet?

- A. The signal path encounters different concentrations of water vapor
- B. VHF ionospheric propagation is very sensitive to path length
- **C. Multipath propagation cancels or reinforces signals**  ←
- D. The Doppler effect causes slight frequency shifts which result in changes in signal strength

**T3A02**

How does vegetation affect UHF and microwave signals?

- A. Causes knife-edge diffraction, distorting voice peaks
- **B. Absorbs signals, leading to poor reception of weak signals**  ←
- C. Amplifies signals, improving reception of weak signals
- D. Has no effect

**T3A03**

What antenna polarization is normally used for long-distance CW and SSB contacts on the VHF and UHF bands?

- A. Right-hand circular
- B. Left-hand circular
- **C. Horizontal**  ←
- D. Vertical

**T3A04**

What is the effect of antenna cross-polarization over a line-of-sight VHF or UHF path?

- A. Modulation sidebands might become inverted
- **B. Received signal strength is reduced**  ←
- C. Signals have an echo effect
- D. Nothing significant will happen

**T3A05**

When using a directional antenna, how might your station be able to communicate with a distant repeater if buildings or obstructions are blocking the direct line of sight path?

- A. Change from vertical to horizontal polarization
- **B. Try to find a path that reflects signals to the repeater**  ←
- C. Try the long path
- D. Increase the antenna SWR

**T3A06**

What is the meaning of the term "picket fencing"?

- A. Alternating transmissions during a net operation
- **B. Rapid flutter on mobile signals due to multipath propagation**  ←
- C. A type of ground system used with vertical antennas
- D. Interference from cable TV in the form of carriers at fixed intervals across the band

**T3A07**

What weather condition might decrease range at microwave frequencies?

- A. High winds
- B. Low barometric pressure
- **C. Precipitation**  ←
- D. Colder temperatures

**T3A08**

What is a likely cause of irregular fading of signals propagated by the ionosphere?

- A. Frequency shift due to Faraday rotation
- B. Interference from thunderstorms
- C. Intermodulation distortion
- **D. Random combining of signals arriving via different paths**  ←

**T3A09**

Which of the following results from the fact that signals propagated by the ionosphere are elliptically polarized?

- A. Digital modes are unusable
- **B. Either vertically or horizontally polarized antennas may be used for transmission or reception**  ←
- C. FM voice is unusable
- D. Both the transmitting and receiving antennas must be of the same polarization

**T3A10**

What effect does multi-path propagation have on data transmissions?

- A. Transmission rates must be increased by a factor equal to the number of separate paths observed
- B. Transmission rates must be decreased by a factor equal to the number of separate paths observed
- C. No significant changes will occur if the signals are transmitted using FM
- **D. Error rates are likely to increase**  ←

**T3A11**

Which region of the atmosphere can reflect HF radio waves?

- A. The stratosphere
- B. The troposphere
- **C. The ionosphere**  ←
- D. The electrosphere

**T3A12**

What effect does fog or rain have on 10-meter and 6-meter band signals?

- A. Absorption
- **B. Little effect**  ←
- C. Deflection
- D. Increased range

---

## T3B — Electromagnetic wave properties: wavelength vs frequency, nature and velocity of electromagnetic waves, relationship of wavelength and frequency; Electromagnetic spectrum definitions: UHF, VHF, HF

*One exam question comes from this group. 12 questions in the pool.*

**The wave itself.** A radio wave has two components, its **electric and magnetic fields**, which
sit **at right angles** to each other. Polarization is defined by the orientation of the **electric**
field specifically — not the magnetic field, and not a ratio between the two.

**Velocity.** A radio wave travels through free space at the **speed of light**, roughly
**300,000,000 meters per second**, and every radio frequency — microwave, UHF, VHF, alike — travels
at that same velocity in free space. Frequency doesn't change the speed, only the wavelength.

**Wavelength and frequency move opposite each other:** wavelength gets **shorter** as frequency
increases. The conversion formula is **wavelength in meters = 300 ÷ frequency in MHz**. This is also
why amateur bands are named by their approximate wavelength in meters *in addition to* their
frequency range and traditional letter/number designators — all of those are valid ways to identify
a band.

**Three memorized frequency ranges, low to high:**

| Range | Frequencies |
|---|---|
| **HF** | **3 to 30 MHz** |
| **VHF** | **30 to 300 MHz** |
| **UHF** | **300 to 3000 MHz** |

Each band's ceiling is the next band's floor — HF tops out at 30, VHF starts at 30 and tops out at
300, UHF starts at 300.

#### All 12 pool questions for T3B

**T3B01**

What is the relationship between the electric and magnetic fields of an electromagnetic wave?

- A. They travel at different speeds
- B. They are in parallel
- C. They revolve in opposite directions
- **D. They are at right angles**  ←

**T3B02**

What property of a radio wave defines its polarization?

- **A. The orientation of the electric field**  ←
- B. The orientation of the magnetic field
- C. The ratio of the energy in the magnetic field to the energy in the electric field
- D. The ratio of the velocity to the wavelength

**T3B03**

What are the two components of a radio wave?

- A. Impedance and reactance
- B. Voltage and current
- **C. Electric and magnetic fields**  ←
- D. Ionizing and non-ionizing radiation

**T3B04**

What is the velocity of a radio wave traveling through free space?

- **A. Speed of light**  ←
- B. Speed of sound
- C. 0.86 times the speed of light
- D. 1.86 times the speed of sound

**T3B05**

What is the relationship between wavelength and frequency?

- A. Wavelength gets longer as frequency increases
- **B. Wavelength gets shorter as frequency increases**  ←
- C. Wavelength is constant at all frequencies
- D. Wavelength and frequency increase as path length increases

**T3B06**

What is the formula for converting frequency to approximate wavelength in meters?

- A. Wavelength in meters equals frequency in hertz multiplied by 300
- B. Wavelength in meters equals frequency in hertz divided by 300
- C. Wavelength in meters equals frequency in megahertz divided by 300
- **D. Wavelength in meters equals 300 divided by frequency in megahertz**  ←

**T3B07**

In addition to frequency, which of the following is used to identify amateur radio bands?

- **A. The approximate wavelength in meters**  ←
- B. Traditional letter/number designators
- C. Channel numbers
- D. All these choices are correct

**T3B08**

What frequency range is referred to as VHF?

- A. 30 kHz to 300 kHz
- **B. 30 MHz to 300 MHz**  ←
- C. 300 kHz to 3000 kHz
- D. 300 MHz to 3000 MHz

**T3B09**

What frequency range is referred to as UHF?

- A. 30 to 300 kHz
- B. 30 to 300 MHz
- C. 300 to 3000 kHz
- **D. 300 to 3000 MHz**  ←

**T3B10**

What frequency range is referred to as HF?

- A. 300 to 3000 MHz
- B. 30 to 300 MHz
- **C. 3 to 30 MHz**  ←
- D. 300 to 3000 kHz

**T3B11**

What is the approximate velocity of a radio wave in free space?

- A. 150,000,000 meters per second
- **B. 300,000,000 meters per second**  ←
- C. 300,000,000 miles per hour
- D. 150,000,000 miles per hour

**T3B12**

Which of these frequencies travels at the highest velocity in free space?

- A. Microwaves
- B. UHF
- C. VHF
- **D. All radio frequencies travel at the same velocity**  ←

---

## T3C — Propagation modes: sporadic E, meteor scatter, auroral propagation, tropospheric ducting; F region skip; Line of sight and radio horizon

*One exam question comes from this group. 11 questions in the pool.*

**Line of sight and the radio horizon.** Simplex UHF signals are rarely heard beyond their radio
horizon because UHF signals **usually are not propagated by the ionosphere** — they need a clear
path. Even so, the **radio horizon extends farther than the visual horizon** for VHF/UHF signals,
because **the atmosphere refracts radio waves slightly**, bending them a bit beyond straight-line
sight. Compared with VHF and higher, HF's defining characteristic is that **long-distance
ionospheric propagation is far more common** on HF.

**Beyond-the-horizon modes, matched to their signatures:**

| Mode | Signature |
|---|---|
| **Auroral backscatter** | Distorted, **raspy** sound |
| **Sporadic E** | Occasional strong signals on **10, 6, and 2 meters** from beyond the horizon |
| **Knife-edge diffraction** | Lets signals travel around/over obstructions |
| **Tropospheric ducting** | Regular over-the-horizon VHF/UHF out to roughly **300 miles**, caused by **temperature inversions** |
| **Meteor scatter** | Best suited to **6 meters** |

**F-region skip on 10 meters** is best **from dawn to shortly after sunset, during periods of high
sunspot activity** — daytime, not night, and only when sunspot numbers are up. During the peak of
the sunspot cycle, the bands that benefit from F-region long-distance propagation are **6 and 10
meters**.

#### All 11 pool questions for T3C

**T3C01**

Why are simplex UHF signals rarely heard beyond their radio horizon?

- A. They are too weak to go very far
- B. FCC regulations prohibit them from going more than 50 miles
- **C. UHF signals are usually not propagated by the ionosphere**  ←
- D. UHF signals are absorbed by the ionospheric D region

**T3C02**

What is a characteristic of HF communication compared with communications on VHF and higher frequencies?

- A. HF antennas are generally smaller
- B. HF accommodates wider bandwidth signals
- **C. Long-distance ionospheric propagation is far more common on HF**  ←
- D. There is less atmospheric interference (static) on HF

**T3C03**

What is one characteristic of VHF signals received via auroral backscatter?

- A. They are often received from 10,000 miles or more
- **B. They are distorted, with a characteristic raspy sound**  ←
- C. They occur only during winter nighttime hours
- D. They are generally strongest when your antenna is aimed west

**T3C04**

Which of the following types of propagation is most commonly associated with occasional strong signals on the 10-, 6-, and 2-meter bands from beyond the radio horizon?

- A. Backscatter
- **B. Sporadic E**  ←
- C. D region absorption
- D. Gray-line propagation

**T3C05**

Which of the following effects may allow radio signals to travel beyond obstructions between the transmitting and receiving stations?

- **A. Knife-edge diffraction**  ←
- B. Faraday rotation
- C. Quantum tunneling
- D. Doppler shift

**T3C06**

What type of propagation is responsible for allowing over-the-horizon VHF and UHF communications to ranges of approximately 300 miles on a regular basis?

- **A. Tropospheric ducting**  ←
- B. D region refraction
- C. F2 region refraction
- D. Faraday rotation

**T3C07**

What band is best suited for communicating via meteor scatter?

- A. 33 centimeters
- **B. 6 meters**  ←
- C. 2 meters
- D. 70 centimeters

**T3C08**

What causes tropospheric ducting?

- A. Discharges of lightning during electrical storms
- B. Sunspots and solar flares
- C. Updrafts from hurricanes and tornadoes
- **D. Temperature inversions in the atmosphere**  ←

**T3C09**

What is generally the best time for long-distance 10-meter band propagation via the F region?

- **A. From dawn to shortly after sunset during periods of high sunspot activity**  ←
- B. From shortly after sunset to dawn during periods of high sunspot activity
- C. From dawn to shortly after sunset during periods of low sunspot activity
- D. From shortly after sunset to dawn during periods of low sunspot activity

**T3C10**

Which of the following bands may provide long-distance communications via the ionosphere's F region during the peak of the sunspot cycle?

- **A. 6 and 10 meters**  ←
- B. 23 centimeters
- C. 70 centimeters and 1.25 meters
- D. All these choices are correct

**T3C11**

Why is the radio horizon for VHF and UHF signals more distant than the visual horizon?

- A. Radio signals move somewhat faster than the speed of light
- B. Radio waves are not blocked by dust particles
- **C. The atmosphere refracts radio waves slightly**  ←
- D. Radio waves are blocked by dust particles
