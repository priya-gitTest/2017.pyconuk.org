original_id: E711
title: "Building a real-time audio sampling app on the PyBoard"
subtitle: "A talk exploring MicroPython, the PyBoard and the PyBoard audio module"
speaker: alan-christie
track: 
video: https://www.youtube.com/watch?v=EYcxfIQySuw
---
While demonstrating the pyboard to a group of colleagues, a challenge was set to produce a practical demonstration of the device that would provide automatic and continuous voice recording and playback of short spoken phrases similar to that found in a number of talking toys.

This talk covers the process of designing and testing the embedded real-time Python solution and includes the architecture, test methodologies and recordings as the stages progressed to the final source code. The talk concludes with a live demonstration of the final application. The solution uses MicroPython (an embedded implementation of Python 3), the pyboard and its AMP Audio skin.

MicroPython is a lean implementation of Python 3 that is optimised to run in a very small footprint on micro-controllers and in constrained environments. It was created by the Australian programmer and physicist Damien George, after a successful Kickstarter backed campaign in 2013.

The pyboard is the original reference hardware created to host MicroPython. It is a compact low-power board based on an ARM processor with a heap of approximately 100kBytes that can run at 168MHz. It has sufficient hardware services and real-time capabilities to control all kinds of electronic projects.

The AMP Audio skin is a small additional module that attaches to the pyboard that adds a small power amplifier, speaker and a microphone with a pre-amp.