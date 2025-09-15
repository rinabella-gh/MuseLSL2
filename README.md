# MuseLSL2

custom fork for my streaming purposes. rest of this readme is adapted from the forked repository. very hacky.

## Usage

Install with:

```
pip install https://github.com/rinabella-gh/MuseLSL2/zipball/main
```

Power up Muse EEG headset, Open console, run:

```
MuseLSL2 find
```

Once you have the mac address of your device, run for instance (but replace the address):

```
MuseLSL2 stream --address 00:55:DA:B5:E8:CF
```

In a new console, while streaming, run:

```
MuseLSL2 view
```

## Record

Best is to record the streams using [Lab Recorder](https://github.com/labstreaminglayer/App-LabRecorder).

