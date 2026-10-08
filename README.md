# A ComfyUI help request that somebody can reproduce

When a ComfyUI workflow fails, report the failure—not just the size of the model file.

A checkpoint's download size is not a RAM or VRAM minimum. The encoders, decoder, precision, output size and software configuration also matter. An out-of-memory error, a format/compatibility error and a run that has not finished are different problems.

A useful example comes from Promptus's MacBook Neo demonstration. The publisher reported both memory and compatibility failures, while smaller configured workflows completed. These are publisher-reported examples, not runs I have reproduced, and they do not establish a universal minimum specification.

Copy this into your help request and replace the blanks:

Operating system and version:
ComfyUI/Promptus version:
Python and PyTorch versions:
CUDA version or macOS/MPS backend, where applicable:
GPU or Mac chip:
Installed RAM and GPU VRAM, where applicable:
Exact checkpoint/model revision:
Text encoders and decoder; CPU/GPU placement:
Workflow and custom-node versions:
Resolution, frames if video, sampling stages and steps:
Exact error or last completed node:
Time elapsed and whether model loading is included:
Peak RAM/VRAM if actually measured; otherwise write 'not measured':
Expected output:
Settings already tried:

Share a minimal workflow or screenshot if it helps. Remove passwords, tokens, private images and identifying paths first. Don't publish somebody else's licensed assets without permission.

For the next test, change one setting at a time and save the result alongside the configuration. Describe an unfinished run as unfinished; describe an error using its actual message. This reporting method is a proposed practical approach, not a benchmark or a promise that a particular model will run.

Source: https://www.youtube.com/watch?v=aksIE2R5_dY — complete captions and description assessed; audiovisual walkthrough not viewed. Timings and outcomes belong to the publisher's configuration.

Disclosure: this guide is part of Bob PA's Promptus/ComfyUI campaign. It is a community field note, not official technical support.

