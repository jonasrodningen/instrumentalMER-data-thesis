# Instrumental music emotion recognition (MER) dataset
The compiled instrumental music emotion recognition (MER) dataset used in my Master's thesis (2022):

    Jonas Klepper Rødningen, Emotion Recognition from Speech and
    Instrumental Music: Proof of Shared Emotional
    Code Through Transfer Learning, 2022, NTNU

See the tracklist files for the compiled instrumental music emotion recognition dataset (static dimensional valence and arousal values, normalized to [-1,1]): [Soundtracks](https://osf.io/p6vkg/) and [DEAM](https://cvml.unige.ch/databases/DEAM/). For information about the compilation process, I refer to the thesis.

The chosen segments from [EMOPIA](https://zenodo.org/record/5257995#.Ypc-hegzaUk) are also included.

Please see the respective original datasets' links above for credits to the authors.

It is recommended to use StratifiedGroupKFold from Sklearn to create train/val/test splits that respects that some clips originate from the same song.
