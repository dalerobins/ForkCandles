# ForkCandles

### Four Candles meets The Stars at Night

*“It's like bloody Blackpool Illuminations in here!”*

A familiar British household expression and, arguably, a perfectly valid engineering criticism of modern Christmas lighting.

Excessive brightness, unwanted flicker, the ubiquitous eight function controller and enough electromagnetic interference to upset Radio Four. Surely we can do better.

**Four candles. Two wires. One night sky.**

ForkCandles is an experimental electronics, hardware and firmware project developing unobtrusive, neurodivergent friendly and migraine conscious Christmas lights and ambient lighting inspired by the natural night sky. Genuine analogue dimming, minimal unwanted temporal light modulation and low RF emissions are fundamental engineering objectives.

## The Motivation

When did Christmas lights become so bloody annoying?

Repetitive flashing, synchronised banks of LEDs and predictable animation sequences bear little resemblance to anything found in nature. The bastardisation of conventional LED strings through AC drive, alternating polarity and multiplexing means that even the supposedly static setting can be a flicker fest disguised as continuous illumination.

And if that wasn't irritating enough, there's the EMC and RFI nightmare. Long lengths of unshielded wiring, rapid switching and inadequately filtered supplies can turn an innocent Christmas tree into a source of conducted and radiated interference. Apparently, irritating the visible spectrum wasn't enough. We had to have a go at the RF spectrum too.

Human visual perception does not conveniently stop at 25, 30, 50 or even 100 Hz. Research has demonstrated perceptible temporal light artefacts above 500 Hz under certain conditions, and indicates increased sensitivity to some artefacts among people who experience migraine. Actual modulation frequencies depend on the controller and must be measured.

For neurodivergent individuals, migraine sufferers and anyone sensitive to unwanted flicker, excessive brightness or visual overstimulation, conventional lighting can be uncomfortable rather than relaxing.

## The Vision

Imagine looking at a clear night sky: hundreds of softly illuminated points of warm white light. Occasionally an individual star twinkles, gently fades, disappears or briefly brightens. Perhaps a rare shooting star catches your attention.

No obvious rhythm, synchronisation or repeating sequence. Genuine analogue DC dimming should allow a barely perceptible glow without additional PWM. Any variation in light output should be intentional, rather than an artefact of the drive circuitry.

Quiet in both the optical and RF spectrum. Inactivity is not a limitation of the design. It is a fundamental feature.

## Projects

### [ForkCandles: The Tealight Liberation Front](./ForkCandles/)

Repurpose cheap electronic tealight controllers in custom analogue DC dimmable strings. Retain identical emitters, continuous DC background illumination and sparse independent effects. Investigate donor circuitry, oscillator behaviour and low voltage operation.

*Liberating silicon, one tealight at a time.*

### [StarsAtNight](./StarsAtNight/)

Purpose built autonomous inverse twinkle modules using tiny, ultra low power OTP or Flash MCUs. Approximately 95–98% of LEDs remain static; the remaining nodes occasionally subtract light using a transistor or MOSFET. Two wire DC operation, analogue dimming and eventual integration into an LED encapsulation are targets.

### [CrossedLines](./CrossedLines/)

Replacement controllers for existing isolated low voltage, two wire antiparallel strings. High frequency symmetrical polarity reversal, analogue current regulation, controlled switching edges and EMC optimisation. The existing topology precludes continuous DC illumination of both banks; reduced perceptible flicker is the target, not zero modulation.

Sometimes the lights aren't the problem. It's the bloody controller.

### [Mastermind](./Mastermind/)

Hybrid static DC and individually addressable analogue lighting. Distributed controllers, rare travelling comets, an expandable topper interface and physical brightness and activity controls. A comet could travel up the tree and erupt into a starburst whilst the background remains undisturbed.

*Hopefully answering the current question rather than the question before last.*

### Shared extension: [MakeItMatter](./MakeItMatter/)

Optional local Matter connectivity for CrossedLines and Mastermind using ESP32-C6 or ESP32-H2. Thread is the preferred network; C6 also permits WiFi. Hardware timing and physical controls remain independent of network activity. No mandatory app or cloud service.

## Project Comparison

| Design target | ForkCandles | StarsAtNight | CrossedLines | Mastermind |
|---|---|---|---|---|
| Continuous DC background | Yes | Yes | No | Yes |
| Analogue dimming | Yes | Yes | Yes | Yes |
| Low RF emissions | Yes | Yes | Yes | Yes |
| Salvaged candle controllers | Yes | No | No | No |
| Autonomous effects | Yes | Yes | No | Yes |
| Retrofit bipolar strings | No | No | Yes | No |
| Individual addressing | No | No | No | Yes |
| Coordinated comets/topper | No | No | No | Yes |
| Optional Matter | No | No | Yes | Yes |

## Design Principles

- Sensory conscious, unobtrusive lighting with extremely low minimum brightness.
- Continuous DC background wherever topology permits; no unnecessary PWM or multiplexing.
- Independent brightness and effect controls where supported; static operation is a target.
- Identical warm white emitters, low component count and low power consumption.
- Controlled switching, filtered DC supplies and low conducted and radiated emissions.
- Physical controls, persistent settings where applicable and no mandatory cloud connectivity.
- Absolutely no bloody eight function controllers.

## Development Status

Early experimental research and development. All circuit concepts and proposed features require prototyping and validation. Measure optical modulation, low brightness performance, current, thermal behaviour and conducted and radiated emissions throughout the dimming range, including radio activity where applicable. See [shared measurement methods](./docs/Measurement-Methods.md).

Flicker free steady state operation where feasible, sensory comfort and low RF emissions are design objectives, not validated product claims. Individual sensory responses vary.

## Further Reading

- [Humans perceive flicker artifacts at 500 Hz](https://pmc.ncbi.nlm.nih.gov/articles/PMC4314649/)
- [Visibility and annoyance of the phantom array effect varies with age and history of migraine](https://journals.sagepub.com/doi/10.1177/14771535241288783)
- [US Department of Energy: Flicker Research](https://www.energy.gov/cmei/ssl/flicker-research)

## Licence

Copyright © 2026 Dale Robins. All rights reserved during initial research and development. Third party materials remain subject to their respective licences.

---

**Nature does not run an eight function lighting controller.**

*It's goodnight from me, and it's goodnight from him.*
