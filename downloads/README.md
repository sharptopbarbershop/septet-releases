# SMOKEY VOX 1.7.0 downloads

Build 42 for Mac and Windows. Pitch correction, Full Choir, Stadium Chant and Talkbox in one plug-in.

| | Download | What is in it |
|---|---|---|
| **Mac** (Apple silicon and Intel) | [SMOKEY-VOX-1.7.0-mac.zip](https://raw.githubusercontent.com/sharptopbarbershop/septet-releases/main/downloads/SMOKEY-VOX-1.7.0-mac.zip) | VST3 and Audio Unit |
| **Windows 64-bit** | [SMOKEY-VOX-1.7.0-win64-vst3.zip](https://raw.githubusercontent.com/sharptopbarbershop/septet-releases/main/downloads/SMOKEY-VOX-1.7.0-win64-vst3.zip) | VST3 |

## Install on Mac

1. Download the Mac zip and unzip it.
2. Put `Septet.vst3` in `~/Library/Audio/Plug-Ins/VST3/`.
3. Put `Septet.component` in `~/Library/Audio/Plug-Ins/Components/`.
4. If macOS blocks it, run these in Terminal:

```
xattr -dr com.apple.quarantine ~/Library/Audio/Plug-Ins/VST3/Septet.vst3
xattr -dr com.apple.quarantine ~/Library/Audio/Plug-Ins/Components/Septet.component
```

5. Restart your DAW and rescan plug-ins.

## Install on Windows (64-bit)

1. Download the Windows zip and unzip it.
2. Close your DAW.
3. Copy the whole `Septet.vst3` folder into `C:\Program Files\Common Files\VST3`. Windows asks for administrator permission.
4. Open your DAW and rescan plug-ins. In Ableton Live: Settings > Plug-Ins, switch on "Use VST3 Plug-In System Folders", then Rescan.

The Windows version does not update itself. Come back to this page for new versions.

## Good to know

- It appears in the plug-in browser as **SMOKEY VOX** under Cosby Audio. The files keep the name Septet so new versions replace the old one in place.
- Talkbox and MIDI target notes need the VST3. The Audio Unit cannot receive MIDI.
- Neither build is signed with a paid developer certificate, which is why macOS may ask for the Terminal step.
- The earlier Mac preview is still here: [SMOKEY-VOX-1.7.0-build39-mac.zip](https://raw.githubusercontent.com/sharptopbarbershop/septet-releases/main/downloads/SMOKEY-VOX-1.7.0-build39-mac.zip).

Checksums (SHA-256):
- Mac: `7ee1caa6168367d20e395e698d8ec5183802f909ec1a2383510859e982ce88cd`
- Windows: `61fe607e23ee73c6bab481681f0206c48be4f7e2fdb2623929e22063a745c100`
