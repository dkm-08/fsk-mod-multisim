# FSK Modulation Circuit Implementation in Multisim

## Overview
This repository contains a Frequency Shift Keying (FSK) modulation circuit implemented in NI Multisim. The circuit demonstrates binary FSK modulation using operational amplifiers, transistors, and basic electronic components.

## Circuit Components

### Active Components
- Operational Amplifier: 741
- Transistors:
  - Q1: BC548BP (NPN)
  - Q2: BC558AP (PNP)

### Passive Components
- Resistors:
  - R1 through R8: 1kΩ each

### Power Supply
- VCC: +12.0V
- VEE: -12.0V

### Signal Sources
- Function Generator 1: Data Signal input
- Function Generator 2: Carrier frequency for logic 1 (Carrier_1)
- Function Generator 3: Carrier frequency for logic 0 (Carrier_0)

### Measurement
- Four Channel Oscilloscope for signal analysis and monitoring

## Circuit Operation
The circuit implements FSK modulation by switching between two carrier frequencies based on the binary input data:
1. When the data signal is logic 1, Carrier_1 frequency is selected
2. When the data signal is logic 0, Carrier_0 frequency is selected

The modulated output signal (Modulated_Out) can be observed using the oscilloscope.

## Testing and Measurement
The circuit includes a four-channel oscilloscope (XSC1) with the following connections:
- Channel A: For monitoring input signals
- Channel B: For monitoring carrier signals
- Channel C: For monitoring modulated output
- Channel D: For additional signal analysis

## Notes
- Ensure proper power supply connections (±12V) before simulation
- Adjust function generator frequencies according to desired FSK parameters
- Monitor the modulated output using the oscilloscope for signal verification

## Circuit Validation
To validate the circuit operation:
1. Connect the data signal to Function Generator 1
2. Set appropriate frequencies for Carrier_1 and Carrier_0
3. Monitor the output waveform on the oscilloscope
4. Verify frequency shifting corresponds to input data changes

## Requirements
- NI Multisim software
- Basic understanding of FSK modulation principles
- Knowledge of electronic circuit simulation

## Safety Considerations
- Observe proper voltage ratings for all components
- Ensure correct polarity of power supplies
- Follow standard simulation safety practices
