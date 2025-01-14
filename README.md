# DSA

NI-Measurement-Plug-Ins/dsa is a collection of open source projects made
available on GitHub. It includes a permissive open source license, a developer
certificate of origin, and a pull request template. This provides everything
necessary to have a properly licensed open source project.

## Projects
- Pure Tone Generation (Active)
- Dynamic Signal Acquisition (Acknowledged)
- Frequency Response (Acknowledged)

## Using this Repository

1. Clone or download this repository.
2. Copy its contents into your project (including the hidden .github directory). 

## Hardware Setup

![Hardware setup](docs/images/hw-setup.png)
Instrumentation:

- NI Dynamic Signal Acquisition device with Pure Tone support (PXIe-4467 | PXIe-4468)

Tested hardware setup:

- PXIe-4468

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
