# CZI Studio — downloads

CZI Studio is a Mac program for looking through folders of Zeiss confocal
microscope images (`.czi` and `.lsm`): browsing them, deciding which ones
matter, measuring them, marking them up, and sharing the result.

It runs entirely on your own Mac. Nothing is uploaded, and your image files are
never written to.

**This repository holds the builds and nothing else.** The source is kept
privately; what you want is on the [Releases page](../../releases/latest).

## Installing

1. Download the `CZI-Studio` zip from the newest release.
2. Unzip it, and drag **CZI Studio** into your Applications folder.
3. The first time only, macOS will refuse to open it, because it is not signed
   with an Apple Developer ID:
   - **macOS 15 (Sequoia) or newer** — double-click it once and let it be
     refused, then open **System Settings → Privacy & Security**, find the line
     about CZI Studio, and click **Open Anyway**.
   - **macOS 14 or older** — right-click the app and choose **Open**, then
     Open again.

After that it opens normally, like anything else.

## Checking what you downloaded

Every release carries a `CHECKSUM.txt`. To confirm the file is the one that was
published:

    shasum -a 256 CZI-Studio-*.zip

## Updating

The program checks for new versions on its own and says so when one exists. You
can let it install the update itself, or come back here and download it.

Your library, tags and measurements live outside the app, so replacing it never
touches them.
