# Vasall Toolchain

**Design, simulate, train and deploy robots, all in one toolchain.**

The Vasall Toolchain brings the whole robot prototyping workflow into one
self-contained environment. Design parts and assemble robots in
**Steward**, train their controllers and AI models in **Tourney**, then
deploy the same **Knight** runtimes to a Raspberry Pi on the real robot.
Finished parts can be exported as STL for manufacturing.

> 🚧 The Vasall Toolchain is in early development and not yet ready for use.

## Components

| Component | Description |
|---|---|
| [Steward](https://github.com/vasall/steward) | Script-based CAD editor for designing robots and managing their simulation and deployment |
| [Tourney](https://github.com/vasall/tourney) | Physics simulation engine for testing robot designs and training their controllers |
| [Knight](https://github.com/vasall/knight) | Runtime for robot controllers and AI models, in simulation and on real hardware |
| [Herold](https://github.com/vasall/herold) | Communication protocol for synchronizing robot configurations and states across the toolchain |
| [Writ](https://github.com/vasall/writ) | A compilable robot description language |
