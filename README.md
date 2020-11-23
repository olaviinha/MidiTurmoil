# Midi Generators

This is to be a collection of Colab notebooks dedicated to generate drag & drop MIDI files.
All notebooks run in [Google Colaboratory](https://colab.research.google.com) (i.e. your browser), using your [Google Drive](https://drive.google.com/drive/my-drive) as data source and/or storage.

Currently only one is available.

---

## Random Arpeggio Sequencer

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/MidiGenerators/blob/main/RandomArpeggioSequencer.ipynb)

Generates random arpeggio sequence by given chord (scale & quality), length, octaves, and randomized note velocities within selected range. Preview audio player is also generated within the notebook.

I.e. it generates notation like this for your selected chord:

![Generated MIDI dragged to DAW](https://storage.googleapis.com/olaviinha/github/midi-generators/pianoroll.png)

### Audio Demos
All demos at 170 BPM, 4 notes per beat, velocity range 80-100.
Description | Generated MIDI | Audio | 
------------ | ------------ | ------------- |
Amaj in 3 octaves | [.mid](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_Amaj_oct3-5__dynv.mid) | [.wav](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_Amaj_oct3-5__dynv.wav)
Cmaj in 2 octaves | [.mid](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_Cmaj_oct2-3__iimg.mid) | [.wav](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_Cmaj_oct2-3__iimg.wav)
F13#9 in 2 octaves | [.mid](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_F13s9_oct3-4__ifhx.mid) | [.wav](https://storage.googleapis.com/olaviinha/github/midi-generators/ra_170bpm_F13s9_oct3-4__ifhx.wav)
