
Studio Backend
==============

Overview
--------

This project is part of the radio studio project.  It has the goal of producing an open source and useable radio studio.  The feature set should include by the end:

 - Multiple live input sources     
   - From the device
   - From live streams
 - Multiple recorded input sources
   - From a library
   - From YouTube
   - From Bandcamp
 - Multiple live output sources
   - To devices
   - To live streams
   - A rolling recording file
 - Individual mapping and mixing between the inputs and outputs
 - Psuedo-devices for multi-channel output devices to allow, for example, 8 stereo streams to play back to a 16-channel output

Getting started
---------------

You can set up an environment to run the software by installing Python 3 and running the following:

```
python3 -m virtualenv venv
curl https://bootstrap.pypa.io/get-pip.py | venv/bin/python3
venv/bin/pip install -r requirements.txt
venv/bin/python3 server.py
```

Current State
-------------

The current implementation has the following functionality implemented:

 - Reading from audio files
 - Reading live input
 - Mixing multiple inputs
 - Playing to live output