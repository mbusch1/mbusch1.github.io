---
permalink: /research/
title: "Research"
author_profile: true
---

Galaxies form stars out of molecular gas, so measuring how much molecular gas a galaxy has is
a precondition for understanding how it grows. That measurement is harder than it sounds. Most
of our census of molecular gas comes from carbon monoxide, but CO is fragile: in diffuse,
weakly shielded gas it is photodissociated away while the hydrogen molecules survive. The
result is **"CO-dark" molecular gas** — real molecular material that simply does not show up in
the surveys we use to find it.

My work is largely about finding that gas, weighing it, and figuring out what it means for star
formation. The main tool is the ground-state 18 cm hyperfine lines of the hydroxyl radical
(OH), which stays visible where CO does not.

CO-dark molecular gas in the Milky Way
======

<figure>
  <img src="/images/OuterGalaxyOHDisk.jpg" alt="Spectra toward the outer Galaxy comparing HI 21 cm, OH 18 cm from the GBT and a 20 m telescope, and CO 3 mm. OH emission appears across the Local Arm, inter-arm gas, Perseus Arm, and outer Galaxy, while CO is detected only in the Local Arm.">
  <figcaption>HI 21 cm, OH 18 cm (GBT and 20 m), and CO 3 mm spectra along one outer-Galaxy
  sightline. OH is detected in the Local Arm, the inter-arm gas, the Perseus Arm, and out to
  R ~ 10–12 kpc. CO shows up only in the Local Arm.
  From <a href="/publications/2021-busch-thick-disk">Busch et al. 2021</a>.</figcaption>
</figure>

My thesis work used the Green Bank Telescope to survey 18 cm OH emission in the outer Galaxy
and the Perseus Arm, where the CO-dark fraction should be largest. Two results came out of it.
First, OH emission is widespread in regions with no detectable CO, and the gas it traces is
diffuse and cold rather than clumped into recognizable clouds
([Busch et al. 2019](/publications/2019-busch-perseus-arm)). Second, this material is not
confined to the thin molecular disk — there is a **thick disk of dark molecular gas** extending
well off the Galactic plane, which conventional CO-based inventories miss entirely
([Busch et al. 2021](/publications/2021-busch-thick-disk)).

<figure class="align-right" style="max-width: 320px;">
  <img src="/images/Models.png" alt="Model grid of CO(1-0) integrated intensity versus OH column density for a range of extinctions and densities, with observed sightlines overplotted.">
  <figcaption>CO(1–0) integrated intensity against OH column density, with model tracks for
  different total extinction A<sub>V</sub> and density n<sub>H</sub>. Sightlines with plenty
  of OH but little or no CO are where the CO-dark gas lies.
  From <a href="/publications/2019-busch-perseus-arm">Busch et al. 2019</a>.</figcaption>
</figure>

Taken together, these say that the molecular reservoir of the Galaxy is both larger and more
extended than the CO maps imply.

CryoPAF on Murriyang
======


Surveys of faint, extended emission are limited by how much sky you can see at once. A
single-pixel receiver looks at one point on the sky; a **phased array feed** forms many beams
simultaneously, turning the telescope into a proper survey instrument for exactly the diffuse
signals I care about.

I am currently working with **CryoPAF**, the cryogenically-cooled phased array feed on
**Murriyang**, the CSIRO Parkes 64 m telescope. A cooled PAF is the combination that matters
here: the wide field of view makes large-area mapping tractable, and the cryogenic front end
keeps the system temperature low enough that genuinely faint diffuse HI and OH stay within
reach. The goal is to map the diffuse molecular interstellar medium over far more sky than
pointed observations have allowed.

The first step is a 100-hour Murriyang program (P1385) mapping OH in a high-latitude cloud — a
region where the CO-dark fraction should be high and the emission faint enough that the survey
speed of a cooled PAF is what makes the measurement possible at all.

<figure>
  <img src="/images/P1385_1667_flag_cube_channels.gif" alt="Animated channel maps of OH 1667 MHz emission across a high-latitude cloud from the P1385 CryoPAF program, with the mean spectrum below marking each channel's velocity." style="max-width: 560px; display: block; margin: 0 auto;">
  <figcaption>Channel maps of OH 1667 MHz emission from the P1385 CryoPAF data toward the
  &pi; cloud, a high-latitude cloud at b ≈ −70° about 300 pc away on the edge of the Local
  Bubble. The panel underneath shows the mean spectrum, with the current channel's velocity
  marked. CO emission is found only in the southeastern part of the cloud, so OH is tracing a
  significant amount of CO-dark gas. Busch et al., in prep.</figcaption>
</figure>

<!-- TODO(Michael): the program and time above come from your CV. Still worth adding: the
     frequency coverage, the number of beams, which high-latitude cloud, and any collaborators
     worth naming. I've left those out rather than guess at numbers. -->

Extragalactic OH and the Local Group
======

<figure class="align-right" style="max-width: 300px;">
  <img src="/images/M31PointingsGBT.jpg" alt="Dust mass surface density map of M31 with two GBT pointing positions marked by circles in the southern part of the disk.">
  <figcaption>Dust mass surface density in M31. The circles mark the two GBT pointings whose
  spectra are shown below. From <a href="/publications/2024-busch-m31-oh">Busch 2024</a>.</figcaption>
</figure>

If OH reveals hidden molecular gas in the Milky Way, it should do the same in other galaxies —
but until recently nobody had detected thermal OH emission outside our own. Using the GBT, I
realized I could carry out a pilot search in nearby galaxies for the same signal I had found in
the Milky Way. I reported the **first extragalactic detection of thermal 18 cm OH emission**,
toward Andromeda (M31), and found it traces an abundant reservoir of CO-faint molecular gas
([Busch 2024](/publications/2024-busch-m31-oh)).

This opens the technique up to the Local Group, where I also work on cold gas in
low-metallicity dwarf galaxies through the **Local Group L-band Survey** (LGLBS) with the VLA
— systems like NGC 6822, IC 10, and WLM, where low metallicity should make the CO-dark
fraction larger still.

<figure style="clear: both;">
  <img src="/images/OHinM31.jpg" alt="GBT spectra at two positions in M31. The left position shows HI, OH 1667, 1665, and 1720 MHz, and CO emission near -550 km/s; the right position shows HI but no clear OH.">
  <figcaption>GBT spectra toward the two M31 positions. Left, 00:39:32 +40:26:09: OH 1667
  and 1665 MHz emission lines up in velocity with HI and CO. Right, 00:40:24 +40:28:11: HI is
  present but OH is not clearly detected. From
  <a href="/publications/2024-busch-m31-oh">Busch 2024</a>.</figcaption>
</figure>

The diffuse ISM in absorption
======

Emission is not the only way to find this gas. Absorption spectroscopy against bright
background continuum sources gives a sharp, sensitive probe of individual diffuse clouds along
a sightline. I contribute to work using **HCO+** absorption to trace CO-dark gas in the diffuse
ISM, and to the **HyGAL** program, which characterizes the Galactic interstellar medium through
hydrides and other small molecules. These absorption measurements provide the physical
conditions — temperature, density, abundance — that the emission surveys need in order to be
converted into masses.

Observing programs
======

Most of this work depends on getting large amounts of time on single-dish and interferometric
telescopes, since diffuse emission is faint and the surveys have to be wide. Since 2019 I have
been awarded **2,803 hours** as PI or co-I across the GBT, the VLA, ALMA, NOEMA, and
Murriyang. A representative sample:

| Program | Facility | Time |
|---|---|---|
| Is the broad 18 cm OH emission "disk" in concordance with Galactic structure? | GBT | 300 h |
| Deep OH absorption in the Outer Galaxy (co-I) | VLA | 350 h |
| Probing the structure of the diffuse molecular ISM — mixed or clumped? | GBT | 216 h |
| A GBT search for the diffuse molecular gas disk in absorption | GBT | 177 h |
| A survey for OH in the northern molecular ring of M31 | GBT | 176 h |
| A GBT survey of M33's molecular gas in OH | GBT | 168 h |
| Turbulent motions, mass content and distribution of dark H<sub>2</sub> in the Outer Galaxy | GBT | 135 h |
| Extending the GBT M31 molecular ring survey in OH | GBT | 132 h |
| A follow-up survey for OH in the Milky Way's nuclear wind | GBT | 121 h |
| Tracing dark molecular gas in the Eos molecular cloud with 18 cm OH | GBT | 100 h |
| CryoPAF mapping of OH in a high-latitude cloud | Murriyang | 100 h |
| An ultra-deep search for OH and CH in the diffuse ISM of the Magellanic system | Murriyang | 100 h |
| Detangling the 3D multi-phase structure of the Perseus cloud with 18 cm OH | GBT | 92.5 h |

Alongside these I contribute to multi-tracer NOEMA and VLA programs on the structure and
chemistry of diffuse molecular gas near the HI-to-H<sub>2</sub> transition.

---

Interested in working on any of this? See the [students page](/students/), or just email me at
[mpbusch@nrao.edu](mailto:mpbusch@nrao.edu).
