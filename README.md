# subtittler

Basic renamer for subtitles TV-Series- it works well for my use case-  I use Plex media server (which expects to be the subtitles in the same folder as video files), but the WebRips (e.g. from ion10) have them in the sub-folder Subs and name of the Episode

Example:
```bash
├── RARBG.txt
├── Sex.Education.S02E01.WEBRip.x264-ION10.mp4
├── Sex.Education.S02E02.WEBRip.x264-ION10.mp4
├── Sex.Education.S02E03.WEBRip.x264-ION10.mp4
├── Sex.Education.S02E04.WEBRip.x264-ION10.mp4
├── Sex.Education.S02E05.WEBRip.x264-ION10.mp4
├── Sex.Education.S02E06.WEBRip.x264-ION10.mp4
├── Sex.Education.S02E07.WEBRip.x264-ION10.mp4
├── Sex.Education.S02E08.WEBRip.x264-ION10.mp4
└── Subs
    ├── Sex.Education.S02E01.WEBRip.x264-ION10
    │   ├── 10_Portuguese.srt
    │   ├── 11_Portuguese.srt
    │   ├── 12_Dutch.srt
    │   ├── 13_Turkish.srt
    │   ├── 14_Swedish.srt
    │   ├── 15_Indonesian.srt
    │   ├── 16_Finnish.srt
    │   ├── 17_Polish.srt
    │   ├── 18_German.srt
    │   ├── 19_Russian.srt
    │   ├── 20_Danish.srt
    │   ├── 2_English.srt
    │   ├── 3_Spanish.srt
    │   ├── 4_Greek.srt
    │   ├── 5_French.srt
    │   ├── 6_nor.srt
    │   ├── 7_Czech.srt
    │   ├── 8_Italian.srt
    │   └── 9_Spanish.srt
    ├── Sex.Education.S02E02.WEBRip.x264-ION10
    │   ├── 10_Portuguese.srt
    │   ├── 11_Portuguese.srt
    │   ├── 12_Dutch.srt
    │   ├── 13_Turkish.srt
    │   ├── 14_Swedish.srt
    │   ├── 15_Indonesian.srt
    │   ├── 16_Finnish.srt
    │   ├── 17_Polish.srt
    │   ├── 18_German.srt
    │   ├── 19_Russian.srt
    │   ├── 20_Danish.srt
    │   ├── 2_English.srt
    │   ├── 3_Spanish.srt
    │   ├── 4_Greek.srt
    │   ├── 5_French.srt
    │   ├── 6_nor.srt
    │   ├── 7_Czech.srt
    │   ├── 8_Italian.srt
    │   └── 9_Spanish.srt
    ├── Sex.Education.S02E03.WEBRip.x264-ION10
    │   ├── 10_Portuguese.srt
    │   ├── 11_Portuguese.srt
    │   ├── 12_Dutch.srt
    │   ├── 13_Turkish.srt
    │   ├── 14_Swedish.srt
    │   ├── 15_Indonesian.srt
    │   ├── 16_Finnish.srt
    │   ├── 17_Polish.srt
    │   ├── 18_German.srt
    │   ├── 19_Russian.srt
    │   ├── 20_Danish.srt
    │   ├── 2_English.srt
    │   ├── 3_Spanish.srt
    │   ├── 4_Greek.srt
    │   ├── 5_French.srt
    │   ├── 6_nor.srt
    │   ├── 7_Czech.srt
    │   ├── 8_Italian.srt
    │   └── 9_Spanish.srt
    ├── Sex.Education.S02E04.WEBRip.x264-ION10
    │   ├── 10_Portuguese.srt
    │   ├── 11_Portuguese.srt
    │   ├── 12_Dutch.srt
    │   ├── 13_Turkish.srt
    │   ├── 14_Swedish.srt
    │   ├── 15_Indonesian.srt
    │   ├── 16_Finnish.srt
    │   ├── 17_Polish.srt
    │   ├── 18_German.srt
    │   ├── 19_Russian.srt
    │   ├── 20_Danish.srt
    │   ├── 2_English.srt
    │   ├── 3_Spanish.srt
    │   ├── 4_Greek.srt
    │   ├── 5_French.srt
    │   ├── 6_nor.srt
    │   ├── 7_Czech.srt
    │   ├── 8_Italian.srt
    │   └── 9_Spanish.srt
    ├── Sex.Education.S02E05.WEBRip.x264-ION10
    │   ├── 10_Portuguese.srt
    │   ├── 11_Portuguese.srt
    │   ├── 12_Dutch.srt
    │   ├── 13_Turkish.srt
    │   ├── 14_Swedish.srt
    │   ├── 15_Indonesian.srt
    │   ├── 16_Finnish.srt
    │   ├── 17_Polish.srt
    │   ├── 18_German.srt
    │   ├── 19_Russian.srt
    │   ├── 20_Danish.srt
    │   ├── 2_English.srt
    │   ├── 3_Spanish.srt
    │   ├── 4_Greek.srt
    │   ├── 5_French.srt
    │   ├── 6_nor.srt
    │   ├── 7_Czech.srt
    │   ├── 8_Italian.srt
    │   └── 9_Spanish.srt
    ├── Sex.Education.S02E06.WEBRip.x264-ION10
    │   ├── 10_Portuguese.srt
    │   ├── 11_Portuguese.srt
    │   ├── 12_Dutch.srt
    │   ├── 13_Turkish.srt
    │   ├── 14_Swedish.srt
    │   ├── 15_Indonesian.srt
    │   ├── 16_Finnish.srt
    │   ├── 17_Polish.srt
    │   ├── 18_German.srt
    │   ├── 19_Russian.srt
    │   ├── 20_Danish.srt
    │   ├── 2_English.srt
    │   ├── 3_Spanish.srt
    │   ├── 4_Greek.srt
    │   ├── 5_French.srt
    │   ├── 6_nor.srt
    │   ├── 7_Czech.srt
    │   ├── 8_Italian.srt
    │   └── 9_Spanish.srt
    ├── Sex.Education.S02E07.WEBRip.x264-ION10
    │   ├── 10_Portuguese.srt
    │   ├── 11_Portuguese.srt
    │   ├── 12_Dutch.srt
    │   ├── 13_Turkish.srt
    │   ├── 14_Swedish.srt
    │   ├── 15_Indonesian.srt
    │   ├── 16_Finnish.srt
    │   ├── 17_Polish.srt
    │   ├── 18_German.srt
    │   ├── 19_Russian.srt
    │   ├── 20_Danish.srt
    │   ├── 2_English.srt
    │   ├── 3_Spanish.srt
    │   ├── 4_Greek.srt
    │   ├── 5_French.srt
    │   ├── 6_nor.srt
    │   ├── 7_Czech.srt
    │   ├── 8_Italian.srt
    │   └── 9_Spanish.srt
    └── Sex.Education.S02E08.WEBRip.x264-ION10
        ├── 10_Portuguese.srt
        ├── 11_Portuguese.srt
        ├── 12_Dutch.srt
        ├── 13_Turkish.srt
        ├── 14_Swedish.srt
        ├── 15_Indonesian.srt
        ├── 16_Finnish.srt
        ├── 17_Polish.srt
        ├── 18_German.srt
        ├── 19_Russian.srt
        ├── 20_Danish.srt
        ├── 2_English.srt
        ├── 3_Spanish.srt
        ├── 4_Greek.srt
        ├── 5_French.srt
        ├── 6_nor.srt
        ├── 7_Czech.srt
        ├── 8_Italian.srt
        └── 9_Spanish.srt
```
Instalation is quite basic: you just need copy the script to /usr/local/bin/ and for sure make the script executable: chmod +x /usr/local/bin/subtittler , change the language you want to move- line 4 (Im looking for __Czech.srt_ )

Then you can start it like this:

```bash
subtittler /plex/Sex\ Education/Sex.Education.S02.WEBRip.x264-ION10/
```

the first and only parametr is the folder I want sort out /plex/Sex\ Education/Sex.Education.S02.WEBRip.x264-ION10/

