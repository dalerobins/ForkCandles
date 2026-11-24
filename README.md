# ForkCandles

### Four Candles meets The Stars at Night

**Four candles. Two wires. One night sky.**

An experimental electronics, hardware and firmware project exploring the reverse engineering, modification and repurposing of ubiquitous electronic LED candles to create custom Christmas lights inspired by the natural night sky.

## The Motivation

Conventional LED Christmas lights are often excessively bright, suffer from undesirable flicker and rely on repetitive, intrusive lighting effects.

ForkCandles aims to create something different: subtle, atmospheric lighting that recreates the natural appearance of stars in the night sky.

Occasional twinkles, gentle dips, random fluctuations and rare comet effects against a predominantly static background of warm white light.

Continuous DC illumination and smooth analogue dimming are fundamental design objectives across all three projects, allowing comfortable operation at extremely low brightness levels.

## Projects

### [ForkCandles: The Tealight Liberation Front](./ForkCandles/)

Reverse engineering, modification and repurposing of inexpensive electronic candle controllers for integration into custom, analogue DC dimmable Christmas light strings.

- Electronic tealight controller identification
- Hardware liberation and transplantation
- Continuous DC background illumination
- Analogue master brightness control
- Low brightness operation
- Identical LED emitters throughout the lighting string
- Independent random twinkle and flicker effects
- Supply voltage and oscillator characterisation
- Waveform analysis and firmware investigation
- Minimal additional hardware and manufacturing cost

The objective is to exploit existing electronic candle technology to recreate natural stellar twinkling whilst retaining smooth DC dimming and eliminating unnecessary flicker from the static LEDs.

*Liberating silicon, one tealight at a time.*

### [StarsAtNight](./StarsAtNight/)

Purpose built autonomous inverse twinkle LED controllers using inexpensive, ultra low power microcontrollers with minimal processing and memory requirements.

- Two wire DC operation
- Analogue master brightness control
- Minimal resource OTP or Flash microcontrollers
- MOSFET and transistor shunt circuits
- Normally illuminated LEDs
- Independent pseudorandom lighting events
- Random dips, extinction and gentle recovery
- Extremely low quiescent current
- No central animation controller
- Potential integration within conventional LED encapsulation

The controller does not generate normal illumination. It occasionally subtracts light from an otherwise continuously illuminated LED.

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

*Hopefully answering the current question, rather than the question before last.*

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

## Design Principles

- Continuous DC illumination
- Genuine analogue dimming
- Excellent performance at extremely low brightness
- Minimal unwanted temporal light modulation
- No unnecessary PWM
- No polarity reversal or multiplexing
- Identical warm white LED emitters
- Minimal power consumption
- Minimal component count
- Independent, natural lighting effects
- Long periods of undisturbed illumination
- No mandatory applications or cloud services
- Absolutely no bloody eight function controllers

## The Starry Night Effect

Unlike conventional Christmas lighting effects, inactivity is the dominant behaviour.

The majority of LEDs remain continuously illuminated. A small percentage occasionally exhibit independent lighting events:

- Momentary dips
- Gentle fades
- Brief extinction
- Irregular twinkles
- Subtle brightness fluctuations
- Rare comet effects

The objective is to reproduce the appearance of a natural night sky rather than a perceptible animation sequence.

## Development Status

Early research and experimental development.

The circuits, architectures and firmware concepts contained within this repository are preliminary and subject to modification, prototyping and electrical characterisation.

Particular attention will be given to DC dimming characteristics, controller operation at reduced supply voltages, optical consistency, quiescent current and unwanted temporal light modulation.

## Research and Inspiration

- [Hacking a Candle Flicker LED](https://cpldcpu.com/2013/12/08/hacking-a-candleflicker-led/)
- [CandleLEDhack](https://github.com/cpldcpu/CandleLEDhack)
- [Revisiting Candle Flicker LEDs](https://cpldcpu.com/2024/01/14/revisiting-candle-flicker-leds-now-with-integrated-timer/)
- The Two Ronnies
- The natural night sky
- The humble electronic tealight

## Licence

Copyright © 2026 Dale Robins.

All rights reserved during the initial research and development phase. Licensing arrangements will be determined as the project matures.

---

**Nature does not run an eight function lighting controller.**

*Less flashing. More magic.*

*It's good night from me, and it's good night from him.*
