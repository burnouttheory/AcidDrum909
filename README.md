<img width="1436" height="830" alt="Acid Drum 909 V1 0 2" src="https://github.com/user-attachments/assets/0e77acd8-b5b0-4877-b9ae-79941dc6c178" />
# Acid Drum 909

**Free Windows VST3 drum machine by Burnout Theory — v1.0.2**

Acid Drum 909 is a Roland TR-909-inspired rhythm workstation designed for creative beat production in DAWs such as FL Studio.

## Features

- 11 drum instruments: kick, snare, low/mid/high toms, rimshot, clap, closed/open hi-hat, crash and ride cymbals.
- 32 patterns per preset: **4 banks × 8 patterns**, with 1–16 steps and accents.
- 250 curated factory presets covering electronic dance-music styles.
- FL Studio tempo sync, live host BPM display and improved expressive Shuffle (0–100%).
- Native VST3 Shuffle parameter for host automation, including FL Studio context-menu actions.
- Short end-of-sound fades and smooth open-hi-hat choking to reduce clicks.
- Per-instrument processing and creative pattern tools, including MIDI import/export.
- Preset browser with separate Factory and User presets.

## Download

Download the latest installer from the [GitHub Releases page](https://github.com/burnouttheory/AcidDrum909/releases/latest).

**Requirements:** Windows 64-bit, a compatible VST3 host, and the Microsoft Edge WebView2 Runtime for the interface. FL Studio is the primary tested host.

## Installation

1. Quit FL Studio or the DAW.
2. Run `AcidDrum909_Setup_1.0.2_OFFICIEL.exe` as administrator.
3. The installer installs `AcidDrum909.vst3` into the standard system VST3 location.
4. Open FL Studio's Plugin Manager, rescan plugins and load a new Acid Drum 909 instance.
5. If the UI does not appear, check that Microsoft Edge WebView2 Runtime is installed.

Existing Factory/User presets are intended to be preserved by the installer. Keep a backup of personal presets before upgrading.

## FL Studio: Shuffle automation

Right-click the Shuffle control and select the host automation option (for example **Create automation clip** or **Link to controller**). The improvement changes playback timing rather than permanently rewriting the stored notes.

## Factory preset note

The 250-preset collection bundled with this release has **Ride cymbal note velocities reduced by 50%** compared with the previous pack. This is **not** the same as setting the Ride instrument volume knob to 0.5.

## Documentation

Read the French and English PDF manuals included in the release assets.

## Development and licenses

The source package is provided separately. The build uses iPlug2 and the Steinberg VST3 SDK; check all third-party licenses and instrument/sample rights before redistribution. See the packaged `LICENSES` directory and source notices.

© 2026 Burnout Theory. FL Studio is a trademark of Image-Line. References to TR-909 describe sound and style inspiration; this project is not affiliated with Roland.
