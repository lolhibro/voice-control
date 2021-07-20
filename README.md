# voice-control
Control system that uses voice commands to affect motors that manually switch on/off my lights

Before doing anything, run <code>wget https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.pbmm</code>
 to get the .pbmm model that the code runs on, if you're using a Mac/PC, or <code>wget https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.tflite</code> if you're using a Raspberry Pi or any other device with an ARM processor.

Run <code>python mic_vad_streaming.py -m path/to/pbmm.pbmm -s path/to/scorer.scorer</code> to get started.
