# Getting Started

## Adding a Measurement Panel to InstrumentStudio
Setting up the InstrumentStudio Panels
1. Open InstrumentStudio
1. Click Manual Layout, and select desired measurement service in the large panel. Click OK.
1. The measurement UI will get displayed in the large panel.
1. Additional small panels may be added to the sfp or you may add a new sfp to host another large panel.
1. Configure Measurement:
   - Test Signal
   - DAQmx Channels
   - Measurement Analysis
1. Make Connections:
   - Connect test signals to DUT inputs.
   - Connect test signal to reference data acquisition channel.
   - Connect DUT output to response data acquisition channel.
1. Press **Run**.

The measurements in Frequency and time domain graphs should be visible.

## Adding a Measurment Step to TestStand 

The following workflow provides an example to show how we can automate our measurements using TestStand from Instrument Studio and also shows how monitoring can be done. 

After following above steps to add measurement service into the Instrument Studio:

1. Open TestStand 24.0 or higher version. Open new sequence file or saved sequence file. 
 
2. To transfer the measurement configuration from Instrument Studio to TestStand, click on "COPY button".
   - In InstrumentStudio, select the "Copy Measurement Configuration"
   - In TestStand, from the insertion Palette, select the measurement link step, add it to the sequence file, and click on the paste button. 

3. Save the Sequence file and RUN the sequence. While running the sequence file in TestStand, you can see measurement result graphs and results were updated in the InstrumentStudio as well.