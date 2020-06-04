---
layout: sidebar
sidebar: s1
version: "dev"
title: "Musical Instrument Digital Interface (MIDI)"
sectionid: "midiGuidelines"
---

This chapter describes the MIDI encoding functionality present in MEI. The purpose of this module is to allow for integrating MIDI data into MEI-encoded notation, to both aid software in translating MEI to MIDI, and to permit the capture of information in files that have been translated from MIDI to MEI. The MIDI model in MEI is similar to that of Mup, and the user is directed to the [Mup User Guide](http://www.arkkra.com/doc/uguide.ps){:.link_ref} for further reading.

The MIDI module defines certain generally-accepted MIDI units that may be used outside of a MIDI context. For example, the **@dur.ppq** attribute accepts MIDI **ppq** (Pulses Per Quarter) as a valid measurement of duration. Similarly, the **@pnum** attribute allows MIDI note numbers for specifying a pitch value.
