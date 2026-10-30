# Radtel RT-400 CHIRP Driver

Independent driver release by **SV1TSD**. Version **0.1.0**.

Supports 256 channels, CTCSS/DCS, split frequencies and TX inhibit, scrambler/FHSS, both VFOs, and general radio settings including TOT, VOX, beeps and side keys.

## Installation

1. Install a current [CHIRP-next](https://chirpmyradio.com/projects/chirp/wiki/Download) release.
2. In CHIRP, enable **Help > Developer Mode**, then restart CHIRP.
3. Before opening an image or downloading, select **File > Load Module** and choose `radtel_rt400.py`.
4. Use **Radio > Download From Radio**, select your cable's port, then **Radtel > RT-400**.

Load the module again each time CHIRP starts. This release does not include CHIRP itself.

## Basic use

Download and save an original backup before editing. Save your changes to a separate `.img` file.

**After an upload, switch the radio off and back on before downloading again.** Download again to verify the changes.

## Feedback

Report the problem, CHIRP version, steps to reproduce, and debug log in this repository's Issues section.

License: **GPL-3.0-or-later**; see `LICENSE`.
