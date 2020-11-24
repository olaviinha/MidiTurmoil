# MIDI Generators

This is _to be_ a collection of Colab notebooks dedicated to generating MIDI files that are ready to be drag & dropped into a DAW.
All notebooks run in [Google Colaboratory](https://colab.research.google.com) (i.e. your browser), using your [Google Drive](https://drive.google.com/drive/my-drive) as data source and/or storage.

Currently only one is available.

---

## Random Arpeggio Sequencer

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/MidiGenerators/blob/main/RandomArpeggioSequencer.ipynb)

Generates arpeggio-like randomized sequence (technically not exactly an arpeggio) by given bpm, chord, notes per beat, length, octaves, randomized note velocities within selected range, and other settings. Preview audio player is also generated inside the notebook.

I.e. it generates notations like this (example) for your selected chord:

![Generated MIDI dragged to DAW](https://storage.googleapis.com/olaviinha/github/midi-generators/pianoroll.png)

### Audio Demos
All demos at 170 BPM.
Description | Generated MIDI | DAW render | 
------------ | ------------ | ------------- |
Amaj in 3 octaves | [.mid](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_Amaj_oct3-5__dynv.mid) | [.wav](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_Amaj_oct3-5__dynv.wav)
A9sus4 in 2 octaves | [.mid](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_A9sus4_oct3-4__ruxk.mid) | [.wav](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_A9sus4_oct3-4__ruxk.wav)
Cmaj in 2 octaves | [.mid](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_Cmaj_oct2-3__iimg.mid) | [.wav](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_Cmaj_oct2-3__iimg.wav)
F13#9 in 2 octaves | [.mid](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_F13s9_oct3-4__ifhx.mid) | [.wav](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_F13s9_oct3-4__ifhx.wav)
