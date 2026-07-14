# Bidirectional LoRa Telemetry Demonstrator

## Overview

This repository presents a bidirectional LoRa telemetry demonstrator developed for an aerospace communication application.

The project focuses on reliable communication between an embedded payload node and a ground-station node. The prototype was implemented and validated using two microcontroller-based communication units.

Because the system is associated with an active competition project, operational source code and implementation-specific details are intentionally not publicly disclosed.

## Project Objectives

- Establish a bidirectional wireless telemetry link.
- Exchange numbered data and acknowledgement messages.
- Verify communication continuity during runtime.
- Evaluate communication recovery and link-reconfiguration concepts.
- Develop a modular foundation for future telemetry integration.
- Validate the system on physical embedded hardware.

## Implemented Capabilities

The prototype successfully demonstrated:

- Bidirectional communication between payload and ground-station nodes
- Periodic transmission and acknowledgement of numbered messages
- Runtime monitoring through serial diagnostic output
- Controlled communication-link reconfiguration
- Communication-continuity verification following reconfiguration
- Error handling for unsuccessful communication attempts
- Hardware-level testing using two independent embedded nodes

The prototype also demonstrated controlled switching between predefined communication channels while preserving end-to-end link continuity.

Implementation-specific message formats, timing parameters, communication settings and recovery procedures are not included in this public repository.

Implementation-specific message formats, timing parameters, communication settings and recovery procedures are not included in this public repository.

## My Contributions

- Designed the embedded communication-software structure.
- Developed the payload-node and ground-station applications.
- Implemented bidirectional message exchange and acknowledgement handling.
- Developed communication-recovery and continuity-verification logic.
- Configured and integrated the embedded communication hardware.
- Conducted subsystem and end-to-end hardware tests.
- Documented the experimental process and validated system behavior.

## Technology Stack

- **Programming:** C/C++
- **Microcontroller:** Teensy 4.1
- **Communication:** LoRa
- **Transceiver:** EBYTE E22 series
- **Interface:** UART
- **Framework:** Arduino
- **Development Areas:** Embedded Systems, Telemetry, C&DH and Ground-Station Communications

## Validation

The prototype was tested using two physical embedded nodes representing the payload and ground-station sides.

The following functions were experimentally verified:

- Continuous bidirectional message exchange
- Correct acknowledgement of numbered messages
- Successful runtime communication reconfiguration
- Continued communication following reconfiguration
- Recovery from unsuccessful communication attempts

Detailed test parameters and operational results are withheld while the related competition project remains active.

## Current Status

The communication demonstrator is functional and continues to be developed as part of an active aerospace competition project.

Additional reliability, monitoring and automation capabilities are currently under development.

## Contact

For further information about the project, its validation process or my technical contributions, please feel free to contact me. Competition-sensitive implementation details will remain confidential while the project is active.

- **Email:** [yigitalpgulsen26@gmail.com](mailto:yigitalpgulsen26@gmail.com)

## Source-Code Availability

The source code, operational communication parameters, message structures and implementation details are not publicly available while the related competition project remains active.

A sanitized technical release may be published after the competition period.

## Repository Scope

This repository serves as a public technical overview of the project and documents the engineering responsibilities, technologies and validated capabilities without disclosing competition-sensitive implementation details.
