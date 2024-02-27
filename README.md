# VIP Aerospace Technologies - Team Laniakea

Team Laniakea is a CubeSat development Vertically Integrated Project (VIP) at the University of Hawaii at Manoa. The purpose of the project is to produce Ke Ao, which will be the first Hawaii student-built satellite to image the Hawaiian islands. 

## GitHub Repository Directory
The following are a list of all repositories within the [vip-aerospace organization](https://github.com/vip-aerospace) that concern Ke Ao.

### General Repositories
- [keao](https://github.com/vip-aerospace/keao) The general Ke Ao repository.
- [laniakea](https://github.com/vip-aerospace/laniakea) The general Team Laniakea repository.

### Flight Software Repositories
As Ke Ao builds upon the Artemis CubeSat kit, there is significant overlap between Artemis code and Ke Ao. As such, the flight software development team is currently refactoring and upstreaming changes to the flight software for the benefit of both Ke Ao and Artemis.
- [artemis-cosmos-rpi-fsw](https://github.com/vip-aerospace/artemis-cosmos-rpi-fsw) The COSMOS flight software that will run on Artemis' Raspberry Pi Zero. This is a fork used to upstream development to Artemis, and the upstream repository (managed by HSFL) is [here](https://github.com/hsfl/artemis-cosmos-rpi-fsw).
- [artemis-cosmos-teensy-fsw](https://github.com/vip-aerospace/artemis-cosmos-teensy-fsw) The micro-COSMOS flight software that will run on Artemis' Teensy 4.1. This is a fork used to upstream development to Artemis, and the upstream repository (managed by HSFL) is [here](https://github.com/hsfl/artemis-cosmos-teensy-fsw).
- [keao-cosmos-teensy-fsw](https://github.com/vip-aerospace/artemis-cosmos-teensy-fsw) The micro-COSMOS flight software that will run on Ke Ao's Teensy 4.1. This is a fork of the upstream Artemis micro-COSMOS flight software, and should only be developed when the Artemis flight software has been completed and upstreamed. This flight software should contain extensions to the Artemis code for Ke Ao's payloads.
- [keao-flight-software](https://github.com/vip-aerospace/keao-flight-software) An archive of the old Raspberry Pi and Teensy flight software in one repository. No longer being updated.
- [teensy-fsw-documentation](https://github.com/vip-aerospace/teensy-fsw-documentation) An archive of the automatically generated Doxygen documentation from keao-flight-software. No longer being updated.
- [keao-teensy-fsw](https://github.com/vip-aerospace/keao-teensy-fsw) An archive of a previous attempt to upstream changes from Ke Ao to Artemis. No longer being updated.

### Ground Station Repositories
- [keao-gs](https://github.com/vip-aerospace/keao-gs) A set of GNURadio flows used to communicate with Ke Ao.

### Unit Testing Repositories
- [astrodev-serial-test](https://github.com/vip-aerospace/astrodev-serial-test) An Arduino sketch used to debug serial communications to/from an [Astrodev Lithium-3 radio](http://www.astrodevllc.com/public_html3/index.html).
- [keao-comms](https://github.com/vip-aerospace/keao-comms) A series of Arduino sketches and Python scripts that test communications with the RFM69 and RFM98 radios. No longer being updated, but archived for reference.

### Mechanical Repositories
- [keao-structure](https://github.com/vip-aerospace/keao-structure) Information about Ke Ao's structural components.
- [keao-thermal](https://github.com/vip-aerospace/keao-thermal) Information about thermal simulation testing.

### Electrical Power System (EPS) Repositories
- [keao-eps-pdu](https://github.com/vip-aerospace/keao-eps-pdu) Information about Ke Ao's Power Distribution Unit (PDU).
- [keao-eps-solar-panels](https://github.com/vip-aerospace/keao-eps-solar-panels) Information about Ke Ao's solar panels.
- [keao-eps-battery](https://github.com/vip-aerospace/keao-eps-battery) Information about Ke Ao's batteries.

### Attitude Control and Determination System (ADCS) Repositories
- [keao-adcs](https://github.com/vip-aerospace/keao-adcs) Information about Ke Ao's ADCS.
- [keao-stk-sim](https://github.com/vip-aerospace/keao-stk-sim) Information about Ke Ao's STK simulations.

### Training Repositories
- [github-workshop](https://github.com/vip-aerospace/github-workshop) A sample GitHub repository for use in Git training.

