# ForkCandles

### Four Candles meets The Stars at Night

**Four candles. Two wires. One night sky.**

An experimental electronics, hardware and firmware project developing unobtrusive, neurodivergent friendly and migraine conscious Christmas lights and ambient lighting inspired by the natural night sky.

The project explores three approaches, from repurposing inexpensive electronic tealight controllers to bespoke autonomous LED controllers and intelligent addressable lighting systems.

## The Motivation

When did Christmas lights become so bloody annoying?

The ubiquitous eight function controller has become almost unavoidable. Excessive brightness, repetitive flashing, synchronised banks of LEDs and predictable animation sequences that bear little resemblance to anything found in nature.

The bastardisation of LED lighting strings through AC drive, alternating polarity and multiplexing has made matters worse. Even the supposedly static setting can be a bloody flicker fest disguised as continuous illumination.

Apparently, anyone whose visual system exceeds the specification of a cheap Christmas light controller is simply expected to tolerate it.

Human visual perception does not conveniently stop at 25, 30, 50 or even 100 Hz. Research has demonstrated that temporal light artefacts can remain perceptible at frequencies exceeding 500 Hz, with some individuals detecting artefacts at considerably higher frequencies. Research also indicates increased sensitivity among people who experience migraine.

For neurodivergent individuals, migraine sufferers and anyone sensitive to flicker, excessive brightness or visual overstimulation, conventional Christmas lighting can be uncomfortable and exhausting rather than relaxing.

Surely we can do better.

## The Vision

Imagine looking at a clear night sky.

Hundreds of softly illuminated points of warm white light. Occasionally, an individual star twinkles, gently fades, momentarily disappears or briefly increases in brightness. Perhaps a rare shooting star catches your attention.

No obvious rhythm, synchronisation or repetitive animation sequence. Nothing demands your attention.

Genuine analogue DC dimming should allow the lighting to be reduced to a barely perceptible glow without introducing unwanted flicker.

The objective is to create atmospheric, organic and unobtrusive lighting, where any variation in illumination is intentional rather than an undesirable consequence of the electrical drive circuitry.

Inactivity is not a limitation of the design. It is a fundamental feature.

## Projects

### [ForkCandles: The Tealight Liberation Front](./ForkCandles/)

Reverse engineering, modification and repurposing of ubiquitous electronic tealight controllers for integration into custom, analogue DC dimmable lighting strings.

- Salvaged electronic candle controllers
- Hardware transplantation and integration
- Continuous DC background illumination
- Analogue master brightness control
- Identical LED emitters throughout
- Independent random lighting effects
- Minimal additional hardware and cost

An investigation into what can be achieved using existing, inexpensive electronic candle technology.

*Liberating silicon, one tealight at a time.*

### [StarsAtNight](./StarsAtNight/)

Purpose built autonomous inverse twinkle controllers using inexpensive, ultra low power microcontrollers with minimal processing and memory requirements.

- Two wire DC operation
- Analogue master dimming
- Minimal resource OTP or Flash microcontrollers
- MOSFET or bipolar transistor shunt modulation
- Independent pseudorandom lighting events
- Extremely low quiescent current
- No central animation controller
- Potential integration within conventional LED encapsulation

Approximately 95–98% of the LEDs remain continuously illuminated, with the remaining LEDs incorporating autonomous controllers.

Rather than generating the normal illumination, each controller occasionally subtracts light from an otherwise continuously illuminated LED.

### [Mastermind](./Mastermind/)

An advanced lighting system combining continuously illuminated conventional LEDs with individually addressable analogue lighting modules.

- Continuous DC background illumination
- Analogue master dimming
- Distributed intelligent controllers
- Autonomous and coordinated lighting effects
- Travelling comets and shooting stars
- Intelligent Christmas tree toppers
- Expandable power and communications interface
- Physical brightness and activity controls

An occasional comet could travel upwards through the tree before erupting into a starburst across the topper, whilst the remaining LEDs continue their undisturbed illumination.

*Hopefully answering the current question rather than the question before last.*

## Design Principles

All three projects share the same fundamental objectives:

- Neurodivergent friendly and migraine conscious design
- Unobtrusive, natural lighting effects
- Continuous DC background illumination
- Genuine analogue dimming
- Flicker free steady state operation
- Extremely low minimum brightness
- Only intentional variations in light output
- No unnecessary PWM or multiplexing
- No repetitive or synchronised flashing
- Minimal component count and power consumption
- No mandatory applications or cloud services
- Absolutely no bloody eight function controllers

## Project Comparison

| Feature | ForkCandles | StarsAtNight | Mastermind |
|---|---|---|---|
| Continuous DC background | Yes | Yes | Yes |
| Analogue dimming | Yes | Yes | Yes |
| Autonomous effects | Yes | Yes | Yes |
| Salvaged candle controllers | Yes | No | No |
| Bespoke MCU firmware | Optional | Yes | Yes |
| Two wire operation | Target | Target | TBD |
| Individual addressing | No | No | Yes |
| Coordinated effects | No | No | Yes |
| Intelligent tree topper | No | No | Yes |

## Development Status

Early experimental research and development.

Individual project directories contain circuit concepts, hardware investigations, firmware proposals and development notes.

All proposed designs are subject to prototyping, electrical characterisation and optical measurements, particularly regarding unwanted temporal light modulation, low brightness performance and controller operation throughout the analogue dimming range.

Flicker free operation and sensory comfort are design objectives rather than validated product claims.

## Further Reading

- [Humans perceive flicker artifacts at 500 Hz](https://pmc.ncbi.nlm.nih.gov/articles/PMC4314649/)
- [Visibility and annoyance of the phantom array effect varies with age and history of migraine](https://journals.sagepub.com/doi/10.1177/14771535241288783)
- [US Department of Energy: Flicker Research](https://www.energy.gov/cmei/ssl/flicker-research)

## Licence

Copyright © 2026 Dale Robins.

All rights reserved during the initial research and development phase. Licensing arrangements will be determined as the project matures.

---

**Nature does not run an eight function lighting controller.**

*It's goodnight from me, and it's goodnight from him.*
