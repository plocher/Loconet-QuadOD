# Loconet-QuadOD
## License: CERN Open Hardware Licence v1.2

A variation on [IO4-QuadOD](https://github.com/plocher/IO4-QuadOD) that replaces the
WemosD1 & IO4 connections with an Arduino Pro Mini and LocoNet-style
communications.

This simple 4-pack module should end up with a BOM cost between $5
and $10, so a full stand alone quad detector pack would run about
$60 with detector boards.

The [MRRWA Embedded Loconet library](https://github.com/mrrwa/LocoNet)
includes support for LN-SV V2 configuration management, which is
also supported by JMRI; it should be pretty easy to write an
addressable Detector sketch (TBD) with assorted XML definitions
suitable for DecoderPro3...



