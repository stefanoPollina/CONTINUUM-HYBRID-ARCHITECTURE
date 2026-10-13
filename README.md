# CONTINUUM

## Parallel Hybrid Architecture

**An experimental browser-based, multi-engine synthesis environment.**

Continuum Parallel Hybrid Architecture is a standalone synthesiser prototype exploring eight synthesis engine families, eight banks and **64 configurable engine slots** in a unified, modular-inspired performance environment.

The project is part of the wider Continuum family of creative audio environments, while remaining independently usable as a browser-based instrument.

> **Status:** Experimental beta. Features and behaviour may change between builds. Test with sensible audio levels.

## Architecture

The interface organises the instrument into **eight synthesis banks**, each containing **eight engine slots**. It combines individual engine controls with shared modulation, routing, sequencing and master output facilities.

### Synthesis families

1. **Acid / 303-inspired** — resonant subtractive bass and sequence sounds.
2. **Hybrid subtractive** — oscillator, filter and envelope tone shaping.
3. **FM matrix** — frequency-modulation timbres.
4. **Macro wavefold** — harmonic shaping and wavefolding.
5. **Spectral wavetable** — wavetable-inspired timbral exploration.
6. **Physical resonator** — resonant acoustic-inspired tones.
7. **Additive harmonics** — layered harmonic partials.
8. **Cross modulation** — interacting oscillators and modulation paths.

These are experimental Web Audio implementations inspired by synthesis techniques, not ports of proprietary instruments.

## Current prototype features

- Eight banks with eight engine slots each
- Live synthesis parameter controls and DSP editors
- Bank-level sound shaping and routing controls
- Global modulation and master output processing
- On-screen performance keyboard
- Step-based performance sequencing
- Visual monitoring and engine activity displays
- JSON patch import and export
- Self-contained HTML, CSS and JavaScript using the Web Audio API
- Responsive layout intended for desktop and mobile browsers

Some features may be experimental or browser-dependent in individual builds.

## Getting started

1. Download the latest HTML build from this repository.
2. Open it in a modern browser supporting the Web Audio API.
3. Activate audio using the interface control. Browsers generally require a user gesture before audio can start.
4. Enable an engine slot, choose its synthesis type and adjust the controls.
5. Play the on-screen keyboard or use the performance sequencer.
6. Explore routing, modulation, effects and patch export.

No dedicated DAW is required for basic standalone use.

## Development direction

Continuum is an evolving creative research and performance project. Possible future work includes deeper DSP, more flexible modulation, expanded sequencing, MIDI controller integration, improved patch management and additional performance interfaces. These are development intentions, **not promises of current functionality**.

## Relationship to Continuum Mosaic

**Continuum Mosaic** is the wider modular development and integration framework. **Parallel Hybrid Architecture** is an independently developed synthesis instrument within that creative family.

## Creative direction and development

**Concept, architecture and creative direction:** Stefano Pollina.

Developed through iterative human–AI collaboration, with ongoing experimentation in synthesis, interface design and live musical interaction.

## Licence

**Licence decision pending.** The repository owner is evaluating an open-source licence that supports public experimentation and possible future commercial editions. Until a `LICENSE` file is published, do not assume that public availability grants permission to modify or redistribute the code.

Copyright © 2026 Stefano Pollina. All rights reserved unless and until a licence states otherwise.

---

*Continuum Parallel Hybrid Architecture — an evolving exploration of synthesis, interaction and parallel sound design.*
