<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This chip is a keyword-spotting inference accelerator. It implements a small depthwise-separable convolutional neural network that classifies short audio segments into a set of wake-word categories.

## How to test

Testing requires a microcontroller to drive the SPI interface. Bring up procedure:
1. Apply power and release reset. 
2. Load weigts
3. Load at least one wake word template
4. Stream MFCC features
5. Read result

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
