# T0 — Safety

**3 of your 35 exam questions · 3 groups (T0A–T0C) · 36 questions in the pool**

The Technician exam's safety subelement is the biggest of the three license classes' safety
sections — General's G0 has 2 groups and 25 questions, Extra's E0 has just 1 group and 12 — but it
still carries only 3 of your 35 questions here. It covers three distinct areas: electrical hazards
around the shack (batteries, fuses, grounding, lightning), physical hazards around a tower (climbing,
guying, ground systems, power-line clearance), and RF exposure hazards (radiation type, duty cycle,
who's responsible for compliance). None of it requires math or Part 97 citations — it's straight
fact recall, and unlike most of the exam it's genuinely worth knowing cold rather than just for test
day, since some of these facts will keep you alive.

---

## T0A — Power circuits and hazards: hazardous voltages, fuses and circuit breakers, grounding, electrical code compliance; Lightning protection; Battery safety

*One exam question comes from this group. 12 questions in the pool.*

**Batteries.** An unprotected 12-volt storage battery's real hazard is **shorting the terminals**,
which can cause burns, fire, or an explosion — not electrical shock from touching both terminals
(12 V is too low for that) and not poison gas from nearby RF. **Rapidly charging or discharging** an
unprotected battery risks **overheating or out-gassing**. Electrical current flowing through the body
is dangerous for several overlapping reasons at once — it can heat tissue, disrupt cells' electrical
functions, and cause involuntary muscle contractions — so when the pool asks what hazard current
flowing through the body poses, the answer is **all these choices are correct**.

**Household wiring.** In a US three-wire 120 V AC cable, **black insulation means hot**. A **fuse's
job is to remove power in case of an overload** — and that's why you should never replace a 5-ampere
fuse with a 20-ampere one: the **excessive current a bigger fuse would allow through could cause a
fire**, since the fuse is protecting the wiring, not just the load. Fuses and circuit breakers go
**in series with the hot conductor only** — never the neutral.

**Shock and residual hazards.** Good shock-guarding practice bundles three habits together: **three-wire
cords and plugs, a common safety ground for all AC-powered station equipment, and discharging
high-voltage capacitors before working inside gear** — the pool's answer is **all these choices are
correct**. Capacitors matter because a power supply remains hazardous **immediately after you turn it
off** — the **charge stored in the filter capacitors** doesn't disappear just because the switch is
off.

**Lightning and grounding.** A lightning arrester on a coax feed line belongs **on a grounded panel
near where the feed line enters the building** — not at the transceiver, not at the antenna feed
point, and not at the AC service panel. Multiple external ground rods must be **bonded together with
heavy wire or conductive strap**; isolated grounds create dangerous potential differences during a
strike. When measuring high voltages, make sure the **voltmeter and its leads are rated for the
voltages being measured**.

#### All 12 pool questions for T0A

**T0A01**

Which of the following is a safety hazard of a 12-volt storage battery that lacks internal protection circuitry?

- A. Touching both terminals with your hands can cause electrical shock
- **B. Shorting the terminals can cause burns, fire, or an explosion**  ←
- C. RF emissions from a nearby transmitter can cause the electrolyte to emit poison gas
- D. All these choices are correct

**T0A02**

What health hazard is posed by electrical current flowing through the body?

- A. It may cause injury by heating body tissue
- B. It may disrupt the electrical functions of cells
- C. It may cause involuntary muscle contractions
- **D. All these choices are correct**  ←

**T0A03**

In the United States, what circuit does black wire insulation indicate in a three-wire 120 V AC cable?

- A. Neutral
- **B. Hot**  ←
- C. Equipment ground
- D. Negative

**T0A04**

What is the purpose of a fuse in an electrical circuit?

- A. To prevent power supply ripple from damaging a component
- **B. To remove power in case of an overload**  ←
- C. To limit current and prevent shocks
- D. All these choices are correct

**T0A05**

Why should a 5-ampere fuse never be replaced with a 20-ampere fuse?

- A. The larger fuse would be likely to blow because it is rated for higher current
- B. The power supply ripple would greatly increase
- **C. Excessive current could cause a fire**  ←
- D. Voltage drop in the higher current fuse could result in excessively low voltage to the device

**T0A06**

What is a good way to guard against electrical shock at your station?

- A. Use three-wire cords and plugs for all AC powered equipment
- B. Connect all AC powered station equipment to a common safety ground
- C. Ensure all capacitors used for high-voltage DC are fully discharged before working inside equipment
- **D. All these choices are correct**  ←

**T0A07**

Where should a lightning arrester be installed in a coaxial feed line?

- A. At the output connector of a transceiver
- B. At the antenna feed point
- C. At the AC power service panel
- **D. On a grounded panel near where feed lines enter the building**  ←

**T0A08**

Where should a fuse or circuit breaker be installed in a 120V AC power circuit?

- **A. In series with the hot conductor only**  ←
- B. In series with the hot and neutral conductors
- C. In parallel with the hot conductor only
- D. In parallel with the hot and neutral conductors

**T0A09**

What should be done to all external ground rods or earth connections?

- A. Waterproof them with silicone caulk or electrical tape
- B. Keep them as far apart as possible
- **C. Bond them together with heavy wire or conductive strap**  ←
- D. Tune them for resonance on the lowest frequency of operation

**T0A10**

What hazard exists when rapidly charging or discharging an unprotected battery?

- **A. Overheating or out-gassing**  ←
- B. Excess output ripple
- C. Electric shock
- D. Overvoltage

**T0A11**

What hazard exists in a power supply immediately after turning it off?

- A. Circulating currents in the dc filter
- B. Leakage flux in the power transformer
- C. Voltage transients from kickback diodes
- **D. Charge stored in filter capacitors**  ←

**T0A12**

Which of the following precautions should be taken when measuring high voltages with a voltmeter?

- A. Ensure that the voltmeter has very low impedance
- **B. Ensure that the voltmeter and its leads are rated for use at the voltages being measured**  ←
- C. Ensure that the circuit is grounded through the voltmeter
- D. Ensure that the voltmeter is set to the correct frequency

---

## T0B — Antenna safety: tower safety and grounding, installing antennas, antenna supports

*One exam question comes from this group. 11 questions in the pool.*

**Lightning ground wiring on a tower** should have **short, direct connections** — the pool
specifically rejects right-angle bends and drip loops as "good practice" distractors; **sharp bends
must be avoided** in grounding conductors generally, because a sharp bend adds impedance a lightning
strike's current has to fight through.

**Climbing rules.** Climbing an antenna tower requires **sufficient training, appropriate tie-off at
all times, and an approved climbing harness** — the pool's answer is **all these choices are
correct**. It is **never** safe to climb a tower without a helper or observer, regardless of height or
whether electrical or mechanical work is involved. While putting up a tower, **stay clear of overhead
electrical wires**. A **crank-up tower** specifically **must not be climbed unless it is retracted, or
mechanical safety locking devices have been installed** — the extending sections are the hazard.

**Guying and grounding.** A **safety wire through a turnbuckle** exists to **prevent the turnbuckle
from loosening due to vibration** — it's not a backup connection or a lightning path. Proper tower
grounding uses **separate eight-foot ground rods for each tower leg, bonded to the tower and to each
other** — a single short rod near the base, a choke, or a cold-water-pipe connection are all wrong.

**Antenna placement around power lines.** The minimum safe clearance from a power line is **enough
distance that if the antenna falls, no part of it can come within 10 feet of the power wires** — not
a fraction of a wavelength, not a height-based formula. For the same reason, **avoid attaching an
antenna to a utility pole**: the antenna could contact high-voltage power lines.

**Whose rules govern grounding.** Amateur radio tower and antenna grounding requirements come from
**local electrical codes** — not FCC Part 97, not FAA tower-lighting rules, and not UL recommended
practices.

#### All 11 pool questions for T0B

**T0B01**

Which of the following is good practice when installing ground wires on a tower for lightning protection?

- A. Put a drip loop in the ground connection to prevent water damage to the ground system
- B. Make sure all ground wire bends are right angles
- **C. Ensure that connections are short and direct**  ←
- D. All these choices are correct

**T0B02**

What is required when climbing an antenna tower?

- A. Have sufficient training on safe tower climbing techniques
- B. Use appropriate tie-off to the tower at all times
- C. Always wear an approved climbing harness
- **D. All these choices are correct**  ←

**T0B03**

Under what circumstances is it safe to climb a tower without a helper or observer?

- A. When no electrical work is being performed
- B. When no mechanical work is being performed
- C. When the work being done is not more than 20 feet above the ground
- **D. Never**  ←

**T0B04**

Which of the following is an important safety precaution to observe when putting up an antenna tower?

- A. Wear a ground strap connected to your wrist at all times
- B. Insulate the base of the tower to avoid lightning strikes
- **C. Look for and stay clear of any overhead electrical wires**  ←
- D. All these choices are correct

**T0B05**

What is the purpose of a safety wire through a turnbuckle used to tension guy lines?

- A. Secure the guy line if the turnbuckle breaks
- **B. Prevent loosening of the turnbuckle from vibration**  ←
- C. Provide a ground path for lightning strikes
- D. Provide an ability to measure for proper tensioning

**T0B06**

What is the minimum safe distance from a power line to allow when installing an antenna?

- A. Add the height of the antenna to the height of the power line and multiply by a factor of 1.5
- B. The height of the power line above ground
- C. 1/2 wavelength at the operating frequency
- **D. Enough so that if the antenna falls, no part of it can come within 10 feet of the power wires**  ←

**T0B07**

Which of the following is an important safety rule to remember when using a crank-up tower?

- A. This type of tower must never be painted
- B. This type of tower must never be grounded
- **C. This type of tower must not be climbed unless it is retracted, or mechanical safety locking devices have been installed**  ←
- D. All these choices are correct

**T0B08**

Which is a proper grounding method for a tower?

- A. A single four-foot ground rod, driven into the ground no more than 12 inches from the base
- B. A ferrite-core RF choke connected between the tower and ground
- C. A connection between the tower base and a cold-water pipe
- **D. Separate eight-foot ground rods for each tower leg, bonded to the tower and each other**  ←

**T0B09**

Why should you avoid attaching an antenna to a utility pole?

- A. The antenna will not work properly because of induced voltages
- B. The antenna may unbalance the power transformer, causing power fluctuations
- **C. The antenna could contact high-voltage power lines**  ←
- D. All these choices are correct

**T0B10**

Which of the following is true when installing grounding conductors used for lightning protection?

- A. Use only non-insulated wire
- B. Wires must be carefully routed with precise right-angle bends
- **C. Sharp bends must be avoided**  ←
- D. Common grounds must be avoided

**T0B11**

Which of the following establishes grounding requirements for an amateur radio tower or antenna?

- A. FCC Part 97 rules
- **B. Local electrical codes**  ←
- C. FAA tower lighting regulations
- D. UL recommended practices

---

## T0C — RF hazards: radiation exposure, proximity to antennas, recognized safe power levels, radiation types, duty cycle

*One exam question comes from this group. 13 questions in the pool.*

**Radio signals are non-ionizing radiation** — they lack the energy of gamma, alpha, or other ionizing
radiation, which is precisely why RF exposure hazards differ from radioactivity hazards: **RF
radiation does not have sufficient energy to cause chemical changes in cells and damage DNA**. Of the
bands in the pool, **50 MHz has the lowest maximum permissible exposure** for RF safety, reflecting
how efficiently the body absorbs energy in that range.

**Duty cycle.** Dropping duty cycle from 100 percent to 50 percent lets the **allowable power density
increase by a factor of 2** — less time transmitting means you can run more power for the same
average exposure. Duty cycle matters because it **affects the average exposure to radiation**, and its
formal definition here is **the percentage of time that a transmitter is transmitting**.

**What drives exposure.** RF exposure near an amateur antenna depends on **frequency and power level
of the RF field, distance from the antenna to the person, and the antenna's radiation pattern** — all
these choices are correct. Exposure limits vary with frequency for one core reason: **the human body
absorbs more RF energy at some frequencies than at others**.

**Checking and maintaining compliance.** You may determine compliance by **calculation based on FCC
OET Bulletin 65, by computer modeling, or by measurement with calibrated equipment** — all these
choices are correct. Once compliant, stay that way by **re-evaluating the station whenever an item in
the transmitter or antenna system changes** — not by notifying the FCC and not by chasing low SWR.

**Direct hazards and responsibility.** Touching an antenna during transmission creates a risk of **RF
burn to the skin** — not electrocution or ionizing exposure. You can reduce RF exposure by
**relocating antennas** farther from occupied areas. And ultimate responsibility for keeping anyone
near the station under the FCC's RF exposure limits rests with **the station licensee** — not the
FCC, not bystanders, and not the local zoning board.

#### All 13 pool questions for T0C

**T0C01**

What type of radiation are radio signals?

- A. Gamma radiation
- B. Ionizing radiation
- C. Alpha radiation
- **D. Non-ionizing radiation**  ←

**T0C02**

Which of the following bands has the lowest maximum permissible exposure for RF safety?

- A. 3.5 MHz
- **B. 50 MHz**  ←
- C. 440 MHz
- D. 1296 MHz

**T0C03**

How does the allowable power density for RF safety change if duty cycle changes from 100 percent to 50 percent?

- A. It increases by a factor of 3
- B. It decreases by 50 percent
- **C. It increases by a factor of 2**  ←
- D. There is no adjustment allowed for lower duty cycle

**T0C04**

What factors affect the RF exposure of people near an amateur station antenna?

- A. Frequency and power level of the RF field
- B. Distance from the antenna to a person
- C. Radiation pattern of the antenna
- **D. All these choices are correct**  ←

**T0C05**

Why do exposure limits vary with frequency?

- A. Lower frequency RF fields have more energy than higher frequency fields
- B. Lower frequency RF fields do not penetrate the human body
- C. Higher frequency RF fields are transient in nature
- **D. The human body absorbs more RF energy at some frequencies than at others**  ←

**T0C06**

Which of the following is an acceptable method to determine whether your station complies with FCC RF exposure regulations?

- A. By calculation based on FCC OET Bulletin 65
- B. By calculation based on computer modeling
- C. By measurement of field strength using calibrated equipment
- **D. All these choices are correct**  ←

**T0C07**

What hazard is created by touching an antenna during a transmission?

- A. Electrocution
- **B. RF burn to skin**  ←
- C. Exposure to ionizing radiation
- D. All these choices are correct

**T0C08**

Which of the following actions can reduce exposure to RF radiation?

- **A. Relocate antennas**  ←
- B. Relocate the transmitter
- C. Increase the duty cycle
- D. All these choices are correct

**T0C09**

How can you make sure your station stays in compliance with RF safety regulations?

- A. By informing the FCC of any changes made in your station
- **B. By re-evaluating the station whenever an item in the transmitter or antenna system is changed**  ←
- C. By making sure your antennas have low SWR
- D. By using only Underwriter Laboratories approved transmitting equipment

**T0C10**

Why is duty cycle one of the factors used to determine safe RF radiation exposure levels?

- **A. It affects the average exposure to radiation**  ←
- B. It affects the peak exposure to radiation
- C. It takes into account the antenna feed line loss
- D. It takes into account the thermal effects of the final amplifier

**T0C11**

What is the definition of duty cycle during the averaging time for RF exposure?

- A. The difference between the lowest and highest power output of a transmitter
- B. The difference between the PEP and the average power output of a transmitter
- **C. The percentage of time that a transmitter is transmitting**  ←
- D. The percentage of time that a transmitter is not transmitting

**T0C12**

How does RF radiation differ from ionizing radiation (radioactivity)?

- **A. RF radiation does not have sufficient energy to cause chemical changes in cells and damage DNA**  ←
- B. RF radiation can only be detected with an RF dosimeter
- C. RF radiation is limited in range to a few feet
- D. RF radiation is perfectly safe

**T0C13**

Who is responsible for ensuring that no person is exposed to RF energy above the FCC exposure limits?

- A. The FCC
- **B. The station licensee**  ←
- C. Anyone who is near an antenna
- D. The local zoning board
