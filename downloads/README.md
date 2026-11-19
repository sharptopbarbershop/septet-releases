# SMOKEY VOX 1.7.0 (build 39) - preview download

macOS only (VST3 and Audio Unit, universal). This is a preview: installed copies do not update to it by themselves.

1. Download `SMOKEY-VOX-1.7.0-build39-mac.zip` and unzip it.
2. Put `Septet.vst3` in `~/Library/Audio/Plug-Ins/VST3/`.
3. Put `Septet.component` in `~/Library/Audio/Plug-Ins/Components/`.
4. If macOS blocks it, run these in Terminal, then restart your host:

```
xattr -dr com.apple.quarantine ~/Library/Audio/Plug-Ins/VST3/Septet.vst3
xattr -dr com.apple.quarantine ~/Library/Audio/Plug-Ins/Components/Septet.component
```

It appears in the plug-in browser as SMOKEY VOX (Cosby Audio). The files keep the name Septet so updates replace them in place.
