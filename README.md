# &#x1F50A; opus-codec-arduino

# Opus Audio Codec for Arduino

This is a fork of the https://github.com/Palatis/arduino-opus library.

Removed unnecessary post-installation scripts. Fix bugs.

Removed all processor-specific optimized code (e.g., amd64, 386) so that it will compile with the same code on all environements.

## Overview

Opus is a totally open, royalty-free, highly versatile audio codec. 
Opus is unmatched for interactive speech and music transmission over the Internet, but is also intended for storage and streaming applications. 

It is standardized by the Internet Engineering Task Force (IETF) as [RFC 6716](https://datatracker.ietf.org/doc/html/rfc6716) which incorporated technology from Skype’s SILK codec and Xiph.Org’s CELT codec.

## Technology

Opus can handle a wide range of audio applications, including Voice over IP, videoconferencing, in-game chat, and even remote live music performances. It can scale from low bitrate narrowband speech to very high quality stereo music. Supported features are:

- Bitrates from 6 kb/s to 510 kb/s
- Sampling rates from 8 kHz (narrowband) to 48 kHz (fullband)
- Frame sizes from 2.5 ms to 60 ms
- Support for both constant bitrate (CBR) and variable bitrate (VBR)
- Audio bandwidth from narrowband to fullband
- Support for speech and music
- Support for mono and stereo
- Support for up to 255 channels (multistream frames)
- Dynamically adjustable bitrate, audio bandwidth, and frame size
- Good loss robustness and packet loss concealment (PLC)
- Floating point and fixed-point implementation

You can read the full specification, including the reference implementation, in [RFC 6716](https://datatracker.ietf.org/doc/html/rfc6716).



## NOTE
This library is mainly targeted for [Platform.io](https://platformio.org), because I have no idea how to specify compiler flags in Arduino library.

If someone actually DO find a way to do that, I'm open for PR.

## Library usage
**TBD**

## License
- **this library**: [APACHE 2.0](https://github.com/Palatis/esp8266-arduino-opus/blob/master/LICENSE)
- **ogg**: BSD-3 (link wanted!)
- **opus**: [BSD-3](https://opus-codec.org/license/)
- **opusfile**: [BSD-3](https://opus-codec.org/license/)
