# DFz Reduction

DFz Reduction is a dynamic resonance suppressor for mixing and mastering.

It is designed to reduce harsh resonances while keeping the sound natural and musical.

## Features

- Dynamic resonance suppression
- Mix and Master modes
- Node-based sensitivity curve
- Delta mode for monitoring removed content
- FFT sizes: 4096 / 8192 / 16384
- VST3 for Windows (64-bit)

## Installation

1. Copy `DFz_Reduction.vst3` to your VST3 folder:
   `C:\Program Files\Common Files\VST3`
2. Rescan plugins in your DAW.

Note: Some DAWs require a full restart after copying the plugin.

## Quick Start

1. Insert DFz Reduction on a track or bus.
2. Increase `Amount`.
3. Adjust `Sensitivity` and `Focus` as needed.
4. Use the node graph to control where the plugin reacts.
5. Use `Mix` for tracks and buses, `Master` for full mixes.

## Controls

- `Amount`  
  Sets the overall reduction depth.

- `Sensitivity`  
  Controls how easily resonances are detected.

- `Focus`  
  Controls how narrow or broad the reduction behaves.

- `Attack`  
  Adjusts how quickly the reduction reacts.

- `Release`  
  Adjusts how quickly the reduction returns.

- `FFT Size`  
  Higher values are more precise but use more CPU.

- `Delta`  
  Lets you monitor the removed content.

## Node Types

- Peak
- Low Shelf
- High Shelf
- Low Cut
- High Cut

## Notes

- `16384` gives the highest precision.
- `8192` is a good general-purpose setting.
- Lower FFT sizes are lighter on CPU, but may sound less precise.

## License

Free to use. Please do not redistribute modified versions without permission.

## Contact

If you find bugs or have feedback, feel free to contact me at REITOU9601@gmail.com.
