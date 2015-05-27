## Indic Keyboard
AOSP keyboard ported to support more languges.

Indic keyboard is a free and open source Indian language input keyboard application for Android mobile devices. At present supporting about 16+ Indic languages, this application has multiple input methods for each language - direct input (characters mapped to keys), inscript and transliteration. Though support for Indian languages was already available in some phones, Android officially started support with Jelly bean (4.1) version. Device need to haave font and rendering support for the keyboard to work.

This keyboard requires Android 4.1+.

## Requirements

* Android 4.1 and above.

## Supported Languages & Layouts
* Arabic
* Assamese: Inscript, Transliteration
* Bengali: Probhat, Avro, Inscript
* Gujarati: Phonetic, Inscript, Transliteration
* Hindi: Phonetic, Inscript, Transliteration
* Kannada:  Compact, Phonetic, Inscript, Inscript Mobile, Transliteration
* Kashmiri/Kashur: Inscript, Transliteration
* Malayalam: Compact, Phonetic (based on lalitha), Phonetic (based on swanalekha) Inscript, Transliteration
* Marathi: Transliteration
* Mon
* Myanmar (Burmese): xkb
* Nepali: Phonetic, Traditional, Transliteration, Inscript
* Oriya/Odia:  Inscript, Transliteration
* Punjabi:  Phonetic, Inscript, Transliteration
* Sanskrit: Transliteration
* Sinhalese: Transliteration
* Tamil: Tamil-99 (initial support), Inscript, Phonetic, Compact, Transliteration
* Telugu:  Phonetic, Inscript, Transliteration, KaChaTaThaPa, Compact
* Urdu: Transliteration

## License 

Apache License, Version 2.0

## HOWTO Build
1. Install gradle (1.x), Android Support Repository, SDK and other usual android stuffs.
2. Clone the repository
3. Initialize submodules
4. `cd java`
5. Use `gradle assembleDebug` to build the package.

## Credits
This project is originally initiated by Jishnu Mohan in 2012 as part of his `androidtweak.in` project.

1.0 version was supported by DIT R & D Project undertaken by ICFOSS, Govt. of Kerala. Anivar Aravind co-ordinated the project for ICFOSS and Hiran Venugopalan designed the icon.

This project uses code from jquery.ime project of Wikimedia and some of the layouts are ported from there.

## TODO

