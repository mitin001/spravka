# Spravka

This is the Adobe Audition session project for the spravka mixdown.

This 1-minute track was used as a background instrumental at least 348 times in NNF during its spravka segments. This repository contains all of the spravka clips extracted from across over 100 NNF episodes along with the Audition file (spravka.sesx) where the segments with minimal voiceover were chosen and mixed together in an attempt to restore the background instrumental:

![image](https://github.com/user-attachments/assets/31bb5e9e-7a70-4e5c-bb1b-10c80700af8e)

The regex for the filename structure of each clip:

```re
([0-9]+)-([0-9.]+)-([0-9]+)
```

* Group 1: episode number.
* Group 2: start position of the spravka segment in seconds.
* Group 3: end position.

For example, from the filename 61-974.017-1006.06.mp3, we know that episode 61 contained a spravka segment between 974.017 s and 1006.06 s (16:14 to 16:46).
