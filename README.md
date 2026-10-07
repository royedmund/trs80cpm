# Lifeboat CP/M on the TRS-80 Model I

An experiment to run Lifeboat CP/M 1.4 on a TRS-80 Model I using FreHD.

**Status:** exploratory. Successful booting or FreHD support is not established here. The original project notes indicate that the release had no hard-drive support; whether this can be adapted remains an open question.

## Repository contents

| File | Purpose |
| --- | --- |
| [Lifeboat_CPM_1_41.DMK](Lifeboat_CPM_1_41.DMK) | Supplied CP/M disk image in DMK format |
| [User notes (PDF)](User_Notes_on_TRS-80_CPM_19xx_Small_System_Software.pdf) | Historical TRS-80 CP/M reference |
| [LICENSE](LICENSE) | Repository licence text |

## Before testing

Read the user notes and establish the CP/M memory-map and hardware requirements. A DMK floppy image is not a FreHD hard-disk image. Use a compatible emulator or image-transfer workflow and keep an untouched copy of the supplied disk image.

## Useful next results to record

- TRS-80 configuration, memory and any required hardware modifications.
- Emulator or FreHD version and the exact disk-image setup.
- Boot output, failure point and any patches made.

The flat layout is appropriate for this small reference-and-disk-image project. Keep future test notes separate from the original image. The repository licence text should not be taken as a new licence grant for historical third-party software contained in the image.
