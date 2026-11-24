# Vasall Toolchain

**Design, simulate, train and deploy robots, all in one toolchain.**

The Vasall Toolchain brings the whole robot prototyping workflow into one
self-contained environment. Design parts and assemble robots in
**Studio**, train their controllers and AI models in **Sandbox**, then
deploy the same **Runtimes** to a Raspberry Pi on the real robot.
Finished parts can be exported as STL for manufacturing.

> 🚧 The Vasall Toolchain is in early development and not yet ready for use.

## Components

| Component | Description |
|---|---|
| [Studio](https://github.com/vasall/studio) | Script-based CAD editor for designing robots and managing their simulation and deployment |
| [Sandbox](https://github.com/vasall/sandbox) | Physics simulation engine for testing robot designs and training their controllers |
| [Runtime](https://github.com/vasall/runtime) | Runtime for robot controllers and AI models, in simulation and on real hardware |
| [Zeal](https://github.com/vasall/zeal) | Communication protocol for synchronizing robot configurations and states across the toolchain |
| [Writ](https://github.com/vasall/writ) | A compilable robot description language |
