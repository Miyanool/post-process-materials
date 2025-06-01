# post-process-materials

This repository is a sandbox project focused on experimenting with **post-process materials** in Unreal Engine.

## Installation

To get started with this project:

1. Clone the repository (Git LFS is required):

```bash
    # Make sure Git LFS is installed: https://git-lfs.github.com/
    $ git clone https://github.com/Miyanool/post-process-materials.git
```

2. Open the `PostProcessMaterials.uproject` file with Unreal Engine 5.

## Tested with

- Unreal Engine 5.4.4

## Post Process Materials

| Material Name                | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| M_PP_BaseScanLine           | Horizontal lines simulating old video noise (X-axis direction).             |
| M_PP_ScanLine               | Thick horizontal lines moving top to bottom, created procedurally.          |
| M_PP_ScanLineTextureBased   | Thick horizontal lines moving bottom to top, created using a texture.       |
| M_PP_RGBSplit               | Subtle RGB channel separation effect with optional overexposure.            |
| M_PP_GlitchNoiseSubtle      | Persistent subtle glitch noise.                                             |
| M_PP_GlitchNoisePulse       | Strong glitch noise that pulses at regular intervals.                       |
| M_PP_HighContrastBW         | High-contrast black-and-white effect. (WIP)                                 |

## License

This project is licensed under the [MIT License](LICENSE).
