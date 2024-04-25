---
layout: tools
title: "meico"
subtitle: "Converter framework for MEI files"
image: https://github.com/cemfi/meico/raw/master/figures/meico_title_small.png
website: http://www.cemfi.de/
repository: https://github.com/cemfi/meico
tags: [conversion, sonification, xslt]
---

[meico](https://github.com/cemfi/meico) is a converter framework for MEI files that is being developed at the Center of Music and Film Informatics, Detmold ([cemfi](http://www.cemfi.de/)). It translates MEI data into a series of formats relevant to many other applications. It can be used as a Java programming framework or standalone app. For the latter case, the meicoApp provides a command line interface as well as an elaborate graphical user interface. Meico's feature list includes

- MEI export to MIDI, MSM, MPM, audio (WAV, MP3),
- MIDI to audio rendering with third-party soundbanks (SF2, DLS),
- musical performance rendering via the official Music Performance Markup API and rendering engine,
- built-in MIDI and audio playback (perfect for proof-reading/listening),
- Verovio integration in the graphical user interface,
- Chroma export,
- XSLT processing of all XML-based data formats, and
- several MEI convenience features such as XML validation against RNG schemata, and expansion of abbreviations (copyof, sameas, expan).
