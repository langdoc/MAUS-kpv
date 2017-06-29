# MAUS-kpv

We would like to be able to use the tools developed in the [Bavarian Archive for Speech Signals](http://www.bas.uni-muenchen.de/Bas/BasHomeeng.html) with Komi data, and this repository contains documentation and data related to this work. In case you have questions, please contact Niko Partanen. This work is connected to the [Kone Foundation](http://www.koneensaatio.fi/en/) funded project [Language Documentation meets Language Technology](https://langdoc.github.io/IKDP-2/)

## Training data

- **Acoustic model:** 50-100 speakers of both gender each speaking 10-20 utterances; can be either read or spontaneous speech, but the phonetic segmentation & labelling  must be manually corrected.
- **Pronunciation model:** phonetic transcripts of as much spoken words as possible, 100 speakers with 100 words each is probably the minimum

## emuR notes

    emuR:::export_BPFCollection(db,"/tmp/BPFs",extractLevels = list(Words="ORT", Phonetic="SAP"),refLevel="Words",copyAudio=T)
