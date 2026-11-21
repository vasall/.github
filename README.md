# Vasall Toolchain

## Concept
The rapid prototyping of new robot designs requires a proper workflow and tools to support it. For this purpose, the **Vasall Toolchain** is being developed: a single, self-contained environment for designing and configuring new robots and for training both the AI models and the controllers that move them.

To keep things clean and simple, the toolchain consists of three components: an editor (Dyno), a simulation engine (Sandbox) and a runtime (Runtime). They communicate over a custom protocol, which lets the editor manage and monitor the other two.

Once a design has been validated in simulation, its parts can be exported to common formats such as STL for manufacturing, while the runtimes can be seamlessly deployed to a Raspberry Pi connected to the real hardware.

## Components

### General Architecture



### Dyno (Working title)
Dyno is both a CAD editor and a network manager. It allows the design of parts, assembling them into robots and controlling the Sandbox and Runtimes.

Dyno contains the following areas:
<table>
  <tr>
    <td><img src="assets/icons/designer.svg" width="16" height="16" align="center"> <b>Designer</b></td>
    <td>Design parts using script-based CAD</td>
  </tr>
  <tr>
    <td><img src="assets/icons/binder.svg" width="16" height="16" align="center">     <b>Binder</b></td>
    <td>Program the behavior of parts to simulate actuators and sensors</td>
  </tr>
  <tr>
    <td><img src="assets/icons/rigger.svg" width="16" height="16" align="center"> <b>Rigger</b></td>
    <td>Assemble the parts into a robot by configuring connections and joints</td>
  </tr>
  <tr>
    <td><img src="assets/icons/scene_builder.svg" width="16" height="16" align="center"> <b>Scene Builder</b></td>
    <td>Setup the testing environment</td>
  </tr>
  <tr>
    <td><img src="assets/icons/programmer.svg" width="16" height="16" align="center"> <b>Programmer</b></td>
    <td>Configure and programm Runtimes</td>
  </tr>
  <tr>
    <td><img src="assets/icons/simulator.svg" width="16" height="16" align="center"> <b>Simulator</b></td>
    <td>Configure and manage the Simulation</td>
  </tr>
</table>

### Sandbox

### Runtime

### Writ

### Herold

## Workflow
