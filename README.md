# PYNQ-RTL-SDR

This project aims to develop a FPGA accelerated real time Software-Defined Radio (SDR) receiver using PYNQ-Z2 board and RTL-SDR dongle. I/Q samples are acquired through [pyrtlsdr](https://github.com/roger-/pyrtlsdr) and passed to programmable logic (PL) where custom IPs created in "System Generator for DSP" downsample, filter and demodulate the data. Currently main focus of the project is to implement a modular and efficient FM receiver where support for additional demodulation schemes could be added later.

## ToDo
- [x] ~~Pass I/Q samples to PL~~
- [x] ~~Implement mono FM receiver~~
- [ ] Play audio samples from PL
- [ ] Implement stereo FM receiver
- [ ] Add support for partial reconfiguration