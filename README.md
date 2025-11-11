Credits
-------

Developed by [UX3D](https://www.ux3d.io/), Scurest and [Julien Duroure](http://julienduroure.com/), with support from the [Khronos Group](https://www.khronos.org/), [Mozilla](https://www.mozilla.org/), and [Airbus Defense & Space](https://www.airbus.com/space.html).

Introduction
------------

Unofficial importer for MSFS glTF files.

Installation
------------

To install it — for example, when testing recent or upcoming changes — copy the `addons/io_scene_gltf2_msfs_kh` folder into the `scripts/addons/` directory of the Blender installation, then enable it under the *Add-ons* tab.

Make sure to set the paths in the addon configuration to get automatically converted textures.
Texture conversion only works for .DDS textures, .KTX2 are not supported.

<img width="1289" height="417" alt="{DFE93EDE-E088-4686-AE6A-C2F5B0901890}" src="https://github.com/user-attachments/assets/804ca8b8-bad7-47f9-8232-5b6fb1df0728" />

Requires the official MSFS exporter plugin to be installed and activated.
Make sure to **only have the 2020 version active**. Activating both 2020 and 2024 exporter plugins will lead to issues.

Linting
-------------------------

This project uses [Black](https://github.com/psf/black) code formatting. To install the Black formatter locally, open a new command shell at the project root and type `pip install -r requirements.txt`. To run the linter, type `black ./` at the project root. If that command doesn't work, type `python -m black ./`. Linting also runs with a pre-commit hook. To install that, type `pre-commit install` at the project root.
