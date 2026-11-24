# ForkCandles

### Four Candles meets The Stars at Night

**Four candles. Two wires. One night sky.**

An experimental electronics, hardware and firmware project dedicated to developing unobtrusive, neurodivergent friendly and migraine conscious Christmas lights and ambient lighting inspired by the natural night sky.

Continuous DC illumination, genuine analogue dimming, flicker free steady state operation and subtle, intentional lighting effects are fundamental design objectives.

The project explores three complementary approaches, from the liberation and repurposing of inexpensive electronic tealight controllers to bespoke autonomous LED controllers and advanced, individually addressable analogue lighting systems.

## The Motivation

When did Christmas lights become so bloody annoying?

The ubiquitous eight function controller has become almost unavoidable. Excessive brightness, repetitive flashing, synchronised banks of LEDs and predictable animation sequences that bear little resemblance to anything found in nature.

To make matters worse, the bastardisation of conventional LED lighting strings through AC drive, alternating polarity and multiplexed illumination means that even the supposedly static setting can be anything but static.

A bloody flicker fest disguised as continuous illumination.

Apparently, anyone whose visual system exceeds the specification of a cheap Christmas light controller is simply expected to tolerate it.

Unfortunately, human visual perception does not conveniently stop at 25, 30, 50 or even 100 Hz. Research has demonstrated that temporal light artefacts can remain perceptible above 500 Hz under certain conditions, with some sensitive individuals detecting phantom array artefacts at frequencies reaching several kilohertz.

Research also indicates increased sensitivity to temporal light modulation among people who experience migraine.

For neurodivergent individuals, migraine sufferers and anyone sensitive to excessive brightness, unwanted flicker or visual overstimulation, conventional Christmas lights can be uncomfortable, distracting and exhausting rather than relaxing.

ForkCandles aims to address this through sensory conscious engineering rather than another bloody lighting mode.

## The Vision

Imagine looking at a clear night sky.

Hundreds of softly illuminated points of warm white light. Occasionally, an individual star twinkles, gently fades, momentarily disappears or briefly increases in brightness. Perhaps a rare shooting star catches your attention.

No obvious rhythm. No synchronisation. No repetitive animation sequence.

Atmospheric, organic and unobtrusive illumination.

Genuine analogue DC dimming should allow the lighting to be reduced to a barely perceptible glow without introducing unwanted PWM flicker.

Any variation in light output should be intentional, not an undesirable consequence of the electrical drive circuitry.

**Inactivity is not a limitation of the design. It is a fundamental feature.**

## Projects

### [ForkCandles: The Tealight Liberation Front](./ForkCandles/)

Reverse engineering, modification and repurposing of inexpensive electronic candle controllers for integration into custom, analogue DC dimmable Christmas light strings.

- Electronic tealight controller identification
- Hardware liberation and transplantation
- Continuous DC background illumination
- Analogue master brightness control
- Extremely low brightness operation
- Identical LED emitters throughout the string
- Independent random lighting effects
- Supply voltage and oscillator characterisation
- Waveform analysis and firmware investigation
- Minimal additional hardware and manufacturing cost

The objective is to exploit existing electronic candle technology to recreate natural stellar twinkling whilst retaining smooth DC dimming and eliminating unwanted flicker from the static LEDs.

*Liberating silicon, one tealight at a time.*

### [StarsAtNight](./StarsAtNight/)

Purpose built autonomous inverse twinkle LED controllers using inexpensive, ultra low power microcontrollers with minimal processing and memory requirements.

- Two wire DC operation
- Analogue master brightness control
- Minimal resource OTP or Flash microcontrollers
- MOSFET and bipolar transistor shunt circuits
- Normally illuminated LEDs
- Independent pseudorandom lighting events
- Random dips, extinction and gentle recovery
- Extremely low quiescent current
- No central animation controller
- Potential integration within conventional LED encapsulation

The controller does not generate normal illumination. It occasionally subtracts light from an otherwise continuously illuminated LED.

The majority of the lighting string consists of conventional static LEDs, with approximately 2–5% incorporating autonomous inverse twinkle controllers.

The ultimate objective is a miniature, two pin LED incorporating autonomous lighting intelligence without requiring external control signals.

*The intelligence is distributed. The illumination is passive.*

### [Mastermind](./Mastermind/)

An advanced, expandable lighting system combining static DC illumination with individually addressable analogue lighting modules.

- Continuous DC background illumination
- Analogue master brightness control
- Individually addressable dynamic LEDs
- Distributed intelligent controllers
- Autonomous and coordinated lighting events
- Travelling comet effects
- Intelligent Christmas tree toppers
- Expandable power and communications interface
- Physical brightness and activity controls
- Persistent user settings

The system will allow occasional coordinated effects, including comets travelling upwards through the tree before erupting into a starburst across an intelligent tree topper.

The objective is to introduce more elaborate lighting effects without compromising the unobtrusive nature of the background illumination.

*Hopefully answering the current question rather than the question before last.*

## Project Comparison

| Feature | ForkCandles | StarsAtNight | Mastermind |
|---|---|---|---|
| Continuous DC background | Yes | Yes | Yes |
| Analogue dimming | Yes | Yes | Yes |
| Low brightness operation | Yes | Yes | Yes |
| Autonomous twinkling | Yes | Yes | Yes |
| Salvaged candle electronics | Yes | No | No |
| Custom MCU firmware | Optional | Yes | Yes |
| Two wire operation | Target | Target | TBD |
| Individual addressing | No | No | Yes |
| Coordinated comet effects | No | No | Yes |
| Intelligent tree topper | No | No | Yes |

These represent proposed design objectives rather than validated product specifications.

## Core Design Philosophy

- Neurodivergent friendly
- Migraine conscious
- Sensory conscious engineering
- Unobtrusive ambient illumination
- Natural night sky inspired effects
- Continuous DC background illumination
- Genuine analogue brightness control
- Flicker free steady state illumination
- Only intentional variations in light output
- Extremely low minimum brightness
- Identical warm white LED emitters
- No unnecessary PWM
- No alternating polarity multiplexing
- No repetitive or synchronised flashing
- Minimal component count and power consumption
- No mandatory applications or cloud services
- Absolutely no bloody eight function controllers

Lighting should enhance an environment, not demand attention.

## The Starry Night Effect

The majority of LEDs remain continuously illuminated. A small percentage occasionally exhibit independent lighting events.

| Effect | Behaviour |
|---|---|
| Dip | Momentary reduction in brightness |
| Fade | Gentle disappearance and recovery |
| Twinkle | Subtle variation in luminous intensity |
| Sparkle | Brief increase in brightness |
| Flicker | Short, irregular brightness fluctuations |
| Comet | Rapid increase followed by a gradual decay |
| Shooting Star | Coordinated travelling illumination |
| Starburst | Occasional coordinated tree topper effect |

Effect availability depends on the hardware implementation.

These are independent lighting events, not eight bloody functions.

Event frequency, duration, depth and intensity should be independently variable, with long periods of undisturbed illumination forming an essential part of the experience.

A completely static mode should also be available.

## Development Status

**Experimental / Early Research and Development**

The circuits, architectures and firmware concepts contained within this repository are preliminary and subject to modification, prototyping and electrical characterisation.

Particular attention will be given to:

- [ ] Reverse engineering electronic tealight controllers
- [ ] Identifying suitable donor Christmas light strings
- [ ] Characterising existing lighting drive circuits
- [ ] Measuring unwanted temporal light modulation
- [ ] Developing analogue DC dimming circuitry
- [ ] Investigating ultra low power OTP microcontrollers
- [ ] Developing autonomous inverse twinkle firmware
- [ ] Optimising random event distributions
- [ ] Evaluating controller operation at reduced supply voltages
- [ ] Matching static and dynamic LED brightness
- [ ] Constructing prototype lighting strings
- [ ] Developing individually addressable analogue controllers
- [ ] Developing intelligent tree toppers
- [ ] Investigating custom encapsulated LED manufacturing

Flicker free operation is a design objective to be verified through electrical and optical measurements. Individual sensory responses may vary.

## Scientific and Technical References

### Temporal Light Modulation and Visual Perception

- [Humans perceive flicker artifacts at 500 Hz (2015)](https://pmc.ncbi.nlm.nih.gov/articles/PMC4314649/)
- [Phantom array and stroboscopic effect visibility under combinations of TLM parameters (2023)](https://journals.sagepub.com/doi/full/10.1177/14771535231169904)
- [Visibility and annoyance of the phantom array effect varies with age and history of migraine (2024)](https://journals.sagepub.com/doi/10.1177/14771535241288783)
- [Impacts of home lighting on human health](https://journals.sagepub.com/doi/full/10.1177/14771535211021064)
- [US Department of Energy: Flicker Research](https://www.energy.gov/cmei/ssl/flicker-research)

### Electronic Candle Technology

- [Hacking a Candle Flicker LED](https://cpldcpu.com/2013/12/08/hacking-a-candleflicker-led/)
- [CandleLEDhack: Source code and waveform analysis](https://github.com/cpldcpu/CandleLEDhack)
- [Revisiting Candle Flicker LEDs with Integrated Timers](https://cpldcpu.com/2024/01/14/revisiting-candle-flicker-leds-now-with-integrated-timer/)

### Christmas Light Controllers

- [Reverse engineering a two wire LED Christmas light controller](https://www.mattmillman.com/projects/simple-2-wire-led-christmas-light-controller/)

### Semiconductor Research

- [Padauk Microcontrollers](https://www.padauk.com.tw/)
- [Bliss Electronic](https://www.bliss.com.tw/en/digital.htm)

## Frequently Unasked Questions

**Does it have eight lighting functions?**

No.

**Does it require an app?**

No.

**Does it repeatedly flash entire banks of LEDs?**

Absolutely bloody not.

**Can it be dimmed without introducing unwanted flicker?**

That's rather the point.

**Four candles?**

Depends how many we need to dismantle.

## Licence

Copyright © 2026 Dale Robins.

All rights reserved during the initial research and development phase. Licensing arrangements will be determined as the project matures. Referenced third party material remains subject to its respective licensing terms.

---

**Nature does not run an eight function lighting controller.**

The humour is intentional. So is the twinkling. The unwanted flicker is not.

**Less flashing. More magic.**

*It's goodnight from me, and it's goodnight from him.*

**Nature does not run an eight function lighting controller.**

*Less flashing. More magic.*

*It's good night from me, and it's good night from him.*
