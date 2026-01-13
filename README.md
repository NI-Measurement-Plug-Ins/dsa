# DSA

NI-Measurement-Plug-Ins/dsa is a collection of open source projects made
available on GitHub. It includes a permissive open source license, a developer
certificate of origin, and a pull request template. This provides everything
necessary to have a properly licensed open source project.

## Projects
### Acquisition
- Dynamic Signal Acquisition (Prereleased)
- Averaged Transfer Functions (Proposed)
- Analog Tachometer Processing (Implemented)

### Generation
- Single Tone (Released)
- Pure Tone (Released)
- Broadband (Acknowledged)
- Multitone (Acknowledged)

### Stimulus-Response
- Single Tone - Gain and Distortion (Released)
- Pure Tone - Gain and Distortion (Released)
- Frequency Sweep - Gain, Phase, Distortion (Released)
- Broadband - Averaged Frequency Response and Coherence (Implemented)

## Using this Repository

1. Clone or download this repository.
2. Copy its contents into your project (including the hidden .github directory). 

## Hardware Setup

Supported DSA hardware platforms:
- PXI and PXIe
- USB
- cDAQ
- FieldDAQ

Supported hardware for Pure Tone plugins (NI Dynamic Signal Acquisition devices with Pure Tone support):
- PXIe-4467
- PXIe-4468

Tested hardware:
- PXIe-4468 (with and without channel expansion)
- PXIe-4464 (with and without channel expansion)
- PXI-4461 (with and without channel expansion)
- USB-4431
- cDAQ
   - NI 9260 (analog output)
   - NI 9234 (analog input)
   - NI 9232 (analog input)

## Software Installation

(*This section is if you only want to use the pre-compiled plug-ins. If you want to open the source code, go to [software development](docs/sw-dev.md).*)  
Install from NI Package Manager:

- NI DAQmx (2024 Q1 or greater)
- InstrumentStudio (2024 Q3 or greater)

Download the latest NI package from the releases section of this repo or add the feed to NI Package Manager to get updates from this repo and other in this community. To use the NI Package Manager feeds, refer to this: [Subscribing to package feeds](https://github.com/NI-MeasurementLink-Plug-Ins/package-manager-feeds)

## Getting Started

When you are ready to start using the software, check out [this](docs/help.md).

## Contributing

Use the instructions in [software development](docs/sw-dev.md) for setting up a development environment and overview of the code.
