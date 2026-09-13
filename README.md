# Procedural Fields

C++ externals for Max/MSP/Jitter: procedural geometry, noise, harmonic motion, control analysis, and audio-reactive features.

![Procedural Fields](media/20_ProceduralFields_System_Showcase.gif)

## Externals

### Jitter

- `jit.lh.arraylayout`
- `jit.lh.radialdistort`
- `jit.lh.noise3d`
- `jit.lh.fbm3d`
- `jit.lh.harmonicfield`
- `jit.lh.noisebuffer`

### Max

- `lh.noisegenerator`
- `lh.harmonicdeformer`
- `lh.valuewatcher`
- `lh.stats`
- `lh.mix`

### MSP

- `lh.pcmfeatures~`
- `lh.multiband~`
- `lh.multibandfeatures~`

## Download

Prebuilt universal macOS externals (`x86_64 + arm64`) are available in [`externals/`](externals/).

Put the `.mxo` bundles somewhere in Max's search path, or inside your own Max package/folder.

If macOS blocks a downloaded external because of quarantine, remove the quarantine attribute from the downloaded folder:

```bash
xattr -dr com.apple.quarantine /path/to/externals
```

## Showcases

![Radial distortion](media/18_RadialDistort_Shockwave_Showcase.gif)

![Value watcher](media/19_ValueWatcher_EventDrivenVisual_Showcase.gif)

![Harmonic field](media/10_HarmonicField_Showcase.gif)

## Status

Shared as-is as part of an ongoing computational practice. No support schedule or compatibility commitment is implied.
