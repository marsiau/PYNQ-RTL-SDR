# IPs used in the project:
* "IQ_To_PL" - AXI Stream compatible IP that splits received I/Q sample stream into two AXI Streams for I and Q data separately.
* "FM_Demod" - FM demodulator IP based on [complex delay line discriminator](https://www.desktopsdr.com/).
* "AXI_S_To_Stream" - IP for receiving a stream of 24 bit audio samples and converting them into serial data supported by "audio_codec_ctrl_v1.0" IP
* "audio_codec_ctrl_v1.0" - ADAU1761 controller IP from https://github.com/Xilinx/PYNQ