# G9 — Antennas and Feed Lines

**4 of your 35 exam questions · 4 groups (G9A–G9D) · 46 questions in the pool**

The second-heaviest subelement after the 5-question ones, and the most practically useful material
in the entire pool. Three formulas plus a catalogue of antenna behavior.

---

## G9A — Feed lines: characteristic impedance, attenuation, SWR, feed point matching

*One exam question comes from this group. 11 questions in the pool.*

**Characteristic impedance** is set by **the spacing between conductor centers and the conductor
radius** — geometry only. Not length, not frequency: a feed line's impedance is the same whether it
is 3 feet or 300 feet long. **Window line is 450 ohms.**

**Loss.** Coax attenuation **increases with frequency**, and feed line loss is expressed in
**decibels per 100 feet**. **High SWR increases loss in a lossy line** — note the qualifier; the
extra loss comes from reflected power making extra trips through a line that was already lossy.

**The counterintuitive one:** higher line loss **reduces** the SWR you measure at the input, because
loss attenuates the reflected wave on its way back to your meter. A long lossy run makes a bad
antenna look deceptively good.

**SWR = larger impedance / smaller impedance**, always bigger over smaller. So 50 ohms into 200 ohms
is **4:1**, and 50 ohms into 10 ohms is **5:1**.

**Reflections** are caused by **a difference between feed line impedance and antenna feed point
impedance**, and the only way to prevent standing waves is to **match** those two. Electrical length
has nothing to do with it.

**The most important practical concept in the pool (G9A08):** a tuner at the *transmitter* end that
presents 1:1 to the radio leaves the feed line SWR **unchanged at 5:1**. The mismatch and its extra
loss are still out there. This is why hams say an antenna tuner does not tune your antenna.

#### All 11 pool questions for G9A

**G9A01**

Which of the following factors determine the characteristic impedance of a parallel conductor feed line?

- **A. The distance between the centers of the conductors and the radius of the conductors**  ←
- B. The distance between the centers of the conductors and the length of the line
- C. The radius of the conductors and the frequency of the signal
- D. The frequency of the signal and the length of the line

**G9A02**

What is the relationship between high standing wave ratio (SWR) and transmission line loss?

- A. There is no relationship between transmission line loss and SWR
- **B. High SWR increases loss in a lossy transmission line**  ←
- C. High SWR makes it difficult to measure transmission line loss
- D. High SWR reduces the relative effect of transmission line loss

**G9A03**

What is the nominal characteristic impedance of “window line” transmission line?

- A. 50 ohms
- B. 75 ohms
- C. 100 ohms
- **D. 450 ohms**  ←

**G9A04**

What causes reflected power at an antenna’s feed point?

- A. Operating an antenna at its resonant frequency
- B. Using more transmitter power than the antenna can handle
- **C. A difference between feed line impedance and antenna feed point impedance**  ←
- D. Feeding the antenna with unbalanced feed line

**G9A05**

How does the attenuation of coaxial cable change with increasing frequency?

- A. Attenuation is independent of frequency
- **B. Attenuation increases**  ←
- C. Attenuation decreases
- D. Attenuation follows Marconi’s Law of Attenuation

**G9A06**

In what units is RF feed line loss usually expressed?

- A. Ohms per 1,000 feet
- B. Decibels per 1,000 feet
- C. Ohms per 100 feet
- **D. Decibels per 100 feet**  ←

**G9A07**

What must be done to prevent standing waves on a feed line connected to an antenna?

- A. The antenna feed point must be at DC ground potential
- B. The feed line must be an odd number of electrical quarter wavelengths long
- C. The feed line must be an even number of physical half wavelengths long
- **D. The antenna feed point impedance must be matched to the characteristic impedance of the feed line**  ←

**G9A08**

If the SWR on an antenna feed line is 5:1, and a matching network at the transmitter end of the feed line is adjusted to present a 1:1 SWR to the transmitter, what is the resulting SWR on the feed line?

- A. 1:1
- **B. 5:1**  ←
- C. Between 1:1 and 5:1 depending on the characteristic impedance of the line
- D. Between 1:1 and 5:1 depending on the reflected power at the transmitter

**G9A09**

What standing wave ratio results from connecting a 50-ohm feed line to a 200-ohm resistive load?

- **A. 4:1**  ←
- B. 1:4
- C. 2:1
- D. 1:2

**G9A10**

What standing wave ratio results from connecting a 50-ohm feed line to a 10-ohm resistive load?

- A. 2:1
- B. 1:2
- C. 1:5
- **D. 5:1**  ←

**G9A11**

What is the effect of transmission line loss on SWR measured at the input to the line?

- **A. Higher loss reduces SWR measured at the input to the line**  ←
- B. Higher loss increases SWR measured at the input to the line
- C. Higher loss increases the accuracy of SWR measured at the input to the line
- D. Transmission line loss does not affect the SWR measurement

---

## G9B — Basic dipole and monopole antennas

*One exam question comes from this group. 12 questions in the pool.*

**The length formulas — memorize 468, and halve it for a quarter wave:**

```
1/2 wave dipole (feet)   = 468 / frequency in MHz
1/4 wave monopole (feet) = 234 / frequency in MHz
```

That gives **33 feet** at 14.250 MHz, **132 feet** at 3.550 MHz, and **8 feet** for a quarter-wave at
28.5 MHz.

**Patterns.** A free-space dipole radiates in a **figure-eight at right angles to the antenna** — off
its sides, with nulls off its ends. A **quarter-wave ground-plane vertical is omnidirectional in
azimuth**.

**Height matters below half a wavelength.** Under 1/2 wavelength high, a dipole's azimuthal pattern
is **almost omnidirectional** — the clean figure-eight only develops when you get it up. And as the
antenna is lowered toward 1/10 wavelength, feed point impedance **steadily decreases**.

**Along the element**, moving the feed point from center toward the ends makes impedance **steadily
increase**. The center is a current maximum (low impedance, 50-70 ohms) and the ends are voltage
maxima — which is also why an end-fed half-wave has a very high feed point impedance (G9D02).

**Verticals.** Ground-mounted radials go **on the surface or a few inches below**. On an **elevated**
ground plane, **sloping the radials downward** brings the feed point from about 35 ohms toward 50.
Horizontal polarization on HF gives **lower ground losses**.

**A random wire fed directly** means **station equipment may carry significant RF current** — without
a counterpoise, your chassis and power cables become the other half of the antenna. That is the
classic source of RF burns and hot microphones.

#### All 12 pool questions for G9B

**G9B01**

What is a characteristic of a random-wire HF antenna connected directly to the transmitter?

- A. It must be longer than 1 wavelength
- **B. Station equipment may carry significant RF current**  ←
- C. It produces only vertically polarized radiation
- D. It is more effective on the lower HF bands than on the higher bands

**G9B02**

Which of the following is a common way to adjust the feed point impedance of an elevated quarter-wave ground-plane vertical antenna to be approximately 50 ohms?

- A. Slope the radials upward
- **B. Slope the radials downward**  ←
- C. Lengthen the radials beyond one wavelength
- D. Coil the radials

**G9B03**

Which of the following best describes the radiation pattern of a quarter-wave ground-plane vertical antenna?

- A. Bi-directional in azimuth
- B. Isotropic
- C. Hemispherical
- **D. Omnidirectional in azimuth**  ←

**G9B04**

What is the radiation pattern of a dipole antenna in free space in a plane containing the conductor?

- **A. It is a figure-eight at right angles to the antenna**  ←
- B. It is a figure-eight off both ends of the antenna
- C. It is a circle (equal radiation in all directions)
- D. It has a pair of lobes on one side of the antenna and a single lobe on the other side

**G9B05**

How does antenna height affect the azimuthal radiation pattern of a horizontal dipole HF antenna at elevation angles higher than about 45 degrees?

- A. If the antenna is too high, the pattern becomes unpredictable
- B. Antenna height has no effect on the pattern
- **C. If the antenna is less than 1/2 wavelength high, the azimuthal pattern is almost omnidirectional**  ←
- D. If the antenna is less than 1/2 wavelength high, radiation off the ends of the wire is eliminated

**G9B06**

Where should the radial wires of a ground-mounted vertical antenna system be placed?

- A. As high as possible above the ground
- B. Parallel to the antenna element
- **C. On the surface or buried a few inches below the ground**  ←
- D. At the center of the antenna

**G9B07**

How does the feed point impedance of a horizontal 1/2 wave dipole antenna change as the antenna height is reduced to 1/10 wavelength above ground?

- A. It steadily increases
- **B. It steadily decreases**  ←
- C. It peaks at about 1/8 wavelength above ground
- D. It is unaffected by the height above ground

**G9B08**

How does the feed point impedance of a 1/2 wave dipole change as the feed point is moved from the center toward the ends?

- **A. It steadily increases**  ←
- B. It steadily decreases
- C. It peaks at about 1/8 wavelength from the end
- D. It is unaffected by the location of the feed point

**G9B09**

Which of the following is an advantage of using a horizontally polarized as compared to a vertically polarized HF antenna?

- **A. Lower ground losses**  ←
- B. Lower feed point impedance
- C. Shorter radials
- D. Lower radiation resistance

**G9B10**

What is the approximate length for a 1/2 wave dipole antenna cut for 14.250 MHz?

- A. 8 feet
- B. 16 feet
- C. 24 feet
- **D. 33 feet**  ←

**G9B11**

What is the approximate length for a 1/2 wave dipole antenna cut for 3.550 MHz?

- A. 42 feet
- B. 84 feet
- **C. 132 feet**  ←
- D. 263 feet

**G9B12**

What is the approximate length for a 1/4 wave monopole antenna cut for 28.5 MHz?

- **A. 8 feet**  ←
- B. 11 feet
- C. 16 feet
- D. 21 feet

---

## G9C — Directional antennas

*One exam question comes from this group. 11 questions in the pool.*

**Yagi element lengths: the reflector is longest, the driven element is about 1/2 wavelength, and
the director is shortest.** The pattern fires toward the director end.

**Performance.** More boom length and more directors means **gain increases**. **Larger-diameter
elements increase bandwidth** — fat elements are broadband, thin elements are sharp. What can be
adjusted to optimize gain, front-to-back, or SWR bandwidth? **All these choices are correct.**

**Definitions.** **Front-to-back ratio** is power in the **main lobe compared to the opposite
direction**. The **main lobe** is the **direction of maximum radiated field strength**.

**Gain comparisons.** **dBi is 2.15 dB higher than dBd** for the same antenna, because 2.15 dB is a
dipole's gain over an isotropic radiator — dBi is referenced to the weaker standard, which is why
manufacturers prefer it. Stacking two identical Yagis a half wavelength apart doubles the power in
the main lobe, so gain is **about 3 dB higher**.

**Matching.** A **beta or hairpin match** is a **shorted transmission line stub at the feed point**.
A **gamma match's** characteristic advantage is that it **does not require the driven element to be
insulated from the boom**, which makes construction much simpler.

#### All 11 pool questions for G9C

**G9C01**

Which of the following would increase the bandwidth of a Yagi antenna?

- **A. Larger-diameter elements**  ←
- B. Closer element spacing
- C. Loading coils in series with the element
- D. Tapered-diameter elements

**G9C02**

What is the approximate length of the driven element of a Yagi antenna?

- A. 1/4 wavelength
- **B. 1/2 wavelength**  ←
- C. 3/4 wavelength
- D. 1 wavelength

**G9C03**

How do the lengths of a three-element Yagi reflector and director compare to that of the driven element?

- **A. The reflector is longer, and the director is shorter**  ←
- B. The reflector is shorter, and the director is longer
- C. They are all the same length
- D. Relative length depends on the frequency of operation

**G9C04**

How does antenna gain in dBi compare to gain stated in dBd for the same antenna?

- A. Gain in dBi is 2.15 dB lower
- **B. Gain in dBi is 2.15 dB higher**  ←
- C. Gain in dBd is 1.25 dBd lower
- D. Gain in dBd is 1.25 dBd higher

**G9C05**

What is the primary effect of increasing boom length and adding directors to a Yagi antenna?

- **A. Gain increases**  ←
- B. Beamwidth increases
- C. Front-to-back ratio decreases
- D. Resonant frequency is lower

**G9C07**

What does “front-to-back ratio” mean in reference to a Yagi antenna?

- A. The number of directors versus the number of reflectors
- B. The relative position of the driven element with respect to the reflectors and directors
- **C. The power radiated in the major lobe compared to that in the opposite direction**  ←
- D. The ratio of forward gain to dipole gain

**G9C08**

What is meant by the “main lobe” of a directive antenna?

- A. The magnitude of the maximum vertical angle of radiation
- B. The point of maximum current in a radiating antenna element
- C. The maximum voltage standing wave point on a radiating element
- **D. The direction of maximum radiated field strength from the antenna**  ←

**G9C09**

In free space, how does the gain of two three-element, horizontally polarized Yagi antennas spaced vertically 1/2 wavelength apart typically compare to the gain of a single three-element Yagi?

- A. Approximately 1.5 dB higher
- **B. Approximately 3 dB higher**  ←
- C. Approximately 6 dB higher
- D. Approximately 9 dB higher

**G9C10**

Which of the following can be adjusted to optimize forward gain, front-to-back ratio, or SWR bandwidth of a Yagi antenna?

- A. The physical length of the boom
- B. The number of elements on the boom
- C. The spacing of each element along the boom
- **D. All these choices are correct**  ←

**G9C11**

What is a beta or hairpin match?

- **A. A shorted transmission line stub placed at the feed point of a Yagi antenna to provide impedance matching**  ←
- B. A 1/4 wavelength section of 75-ohm coax in series with the feed point of a Yagi to provide impedance matching
- C. A series capacitor selected to cancel the inductive reactance of a folded dipole antenna
- D. A section of 300-ohm twin-lead transmission line used to match a folded dipole antenna

**G9C12**

Which of the following is a characteristic of using a gamma match with a Yagi antenna?

- **A. It does not require the driven element to be insulated from the boom**  ←
- B. It does not require any inductors or capacitors
- C. It is useful for matching multiband antennas
- D. All these choices are correct

---

## G9D — Specialized antenna types and applications

*One exam question comes from this group. 12 questions in the pool.*

**Wire antennas.** The **NVIS antenna** for daytime short skip on 40 m is a **horizontal dipole
between 1/10 and 1/4 wavelength above ground** — low and horizontal. An **end-fed half-wave** has a
**very high** feed point impedance. A dipole with a **single central support** is an **inverted V**. A
**multi-wavelength horizontal loop** is **virtually omnidirectional with a lower peak vertical
radiation angle than a dipole**. A **Beverage** is for **directional receiving on the low HF bands** —
it is a long, low, lossy wire that radiates poorly but rejects noise beautifully, and on 160 and 80
meters that trade is worth it.

**Small loops.** An electrically small loop has **nulls broadside to the loop**, with maximum
response in the plane of the loop. Those deep nulls are why they are used for direction finding and
for nulling local noise.

**Multiband.** **Traps enable multiband operation**, and the disadvantage of multiband antennas is
**poor harmonic rejection** — an antenna resonant on both 20 and 15 m will happily radiate your 20 m
second harmonic.

**Log-periodic:** **element length and spacing vary logarithmically along the boom**, and the
advantage is **wide bandwidth**.

**Odds and ends.** Vertically stacking horizontally polarized Yagis **narrows the main lobe in
elevation** — stacking in one plane sharpens the pattern in that plane. A **"screwdriver" mobile
antenna varies its base loading inductance** with a motor, which is how you change bands without
stopping the car. A **"halo"** radiates **omnidirectionally in the plane of the halo**.

#### All 12 pool questions for G9D

**G9D01**

Which of the following antenna types will be most effective as a near vertical incidence skywave (NVIS) antenna for short-skip communications on 40 meters during the day?

- **A. A horizontal dipole placed between 1/10 and 1/4 wavelength above the ground**  ←
- B. A vertical antenna placed between 1/4 and 1/2 wavelength above the ground
- C. A horizontal dipole placed at approximately 1/2 wavelength above the ground
- D. A vertical dipole placed at approximately 1/2 wavelength above the ground

**G9D02**

What is the feed point impedance of an end-fed half-wave antenna?

- A. Very low
- B. Approximately 50 ohms
- C. Approximately 300 ohms
- **D. Very high**  ←

**G9D03**

In which direction is the maximum radiation from a VHF/UHF “halo” antenna?

- A. Broadside to the plane of the halo
- B. Opposite the feed point
- **C. Omnidirectional in the plane of the halo**  ←
- D. On the same side as the feed point

**G9D04**

What is the primary function of antenna traps?

- **A. To enable multiband operation**  ←
- B. To notch spurious frequencies
- C. To provide balanced feed point impedance
- D. To prevent out-of-band operation

**G9D05**

What is an advantage of vertically stacking horizontally polarized Yagi antennas?

- A. It allows quick selection of vertical or horizontal polarization
- B. It allows simultaneous vertical and horizontal polarization
- C. It narrows the main lobe in azimuth
- **D. It narrows the main lobe in elevation**  ←

**G9D06**

Which of the following is an advantage of a log-periodic antenna?

- **A. Wide bandwidth**  ←
- B. Higher gain per element than a Yagi antenna
- C. Harmonic suppression
- D. Polarization diversity

**G9D07**

Which of the following describes a log-periodic antenna?

- **A. Element length and spacing vary logarithmically along the boom**  ←
- B. Impedance varies periodically as a function of frequency
- C. Gain varies logarithmically as a function of frequency
- D. SWR varies periodically as a function of boom length

**G9D08**

How does a “screwdriver” mobile antenna adjust its feed point impedance?

- A. By varying its body capacitance
- **B. By varying the base loading inductance**  ←
- C. By extending and retracting the whip
- D. By deploying a capacitance hat

**G9D09**

What is the primary use of a Beverage antenna?

- **A. Directional receiving for MF and low HF bands**  ←
- B. Directional transmitting for low HF bands
- C. Portable direction finding at higher HF frequencies
- D. Portable direction finding at lower HF frequencies

**G9D10**

In which direction or directions does an electrically small loop (less than 1/10 wavelength in circumference) have nulls in its radiation pattern?

- A. In the plane of the loop
- **B. Broadside to the loop**  ←
- C. Broadside and in the plane of the loop
- D. Electrically small loops are omnidirectional

**G9D11**

Which of the following is a disadvantage of multiband antennas?

- A. They present low impedance on all design frequencies
- B. They must be used with an antenna tuner
- C. They must be fed with open wire line
- **D. They have poor harmonic rejection**  ←

**G9D12**

What is the common name of a dipole with a single central support?

- **A. Inverted V**  ←
- B. Inverted L
- C. Sloper
- D. Lazy H

---

## Bottom line for G9

Characteristic impedance comes from **geometry alone**; window line is **450 ohms**. **Line loss
lowers measured SWR.** **SWR is larger over smaller.** A tuner at the shack **does not change feed
line SWR**. **468 / MHz** for a dipole, **234 / MHz** for a quarter wave. A dipole is a **figure-eight
broadside**; below half a wavelength it goes nearly **omnidirectional**. Yagi: **reflector longest,
director shortest**; **dBi = dBd + 2.15**; stacking adds **3 dB**. **Traps** give multiband at the
cost of **harmonic rejection**. Small loops null **broadside**.
