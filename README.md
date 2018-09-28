# PD-Looper-Sequencer

SequenceWitcher is the main file with all the other pieces put together. It contains 8 different sequa objects, each with a seqi (textfile sequencer object) connected to a stsampw (stereo sampler object). Luupers can loop audio input through the adc~, each can be given different lengths based on beats of the TapTempo. Midi CC's can be configured in the midibiz subpatch. txsq's have some textfile sequences, PD has some sample beats.
