# 3DThings

![Stars](https://badgen.net/github/stars/rapax00/3dthings/?color=yellow)
![License](https://badgen.net/github/license/rapax00/3dthings/?color=cyan)

## Index

- [About](#about)
  - [Why free and open?](#why-free-and-open)
  - [Mision](#mision)
  - [Vision](#vision)
  - [Software stack](#software-stack)
- [Repo structure and files](#repo-structure-and-files)
- [Considerations](#considerations)
- [To Do](#to-do)
- [Contributors](#contributors)

## About

This is an open collection of 3D designs of projects, hobby creations ands comercial things.

> Also available on [Thingiverse](https://www.thingiverse.com/rapax00).

### Why free and open?

I believe that the best way to learn and grow is by sharing and receiving knowledge.

> All designs in this repository are licensed under the MIT License unless a LICENSE file is included inside a Thing folder.

### Mision

To share and collaborate with the 3D maker community to create better things.

### Vision

FOST concept: Free and Open Source Things.

To create a large collection of 3D designs for free use and collaboration.

### Software stack

> All software used are FOSS.

- FreeCAD: For 3D modeling.
- Blender: For 3D modeling.
- PrusaSlicer: For slicing.
- Inkscape: For 2D design.
- etc.

## Repo structure and files

```
3DThings
├───Thing
│   ├───designs
│   │   ├───blender
│   │   │   └───file.blend
│   │   ├───freecad
│   │   |   └───file.FCStd
│   │   └───inkscape
│   │       └───file.svg
│   ├───extras
│   │   └───images
│   │       └───file.png
│   ├───printer
│   │   ├───3mf
│   │   │   └───file.3mf
│   │   ├───gcode
│   │   │   └───file.gcode
│   │   └───stl
│   │       └───file.stl
│   ├───README.md
│   └───LICENSE
├───README.md
└───LICENSE
```

- **Thing**: Template folder structure for each thing.
  - **designs**: Folder for source design files.
    - _blender_
    - _freecad_
    - _inkscape_
    - _other_
  - **extras**: Extra files like 2D designs, plans, electronics, etc.
    - _images_ (Images of the thing. Render, STL, real print, etc.)
  - **printer**: Files related to printing.
    - _3mf_
    - _gcode_
    - _stl_
  - **README.md**: Description of the thing (you have a template).
  - **LICENSE**: License of the thing.

> **Important:**
>
> - All folders in bold are mandatory
> - You MUST include editable project files in **desings** folder (from any software mention above or FOSS)
> - You MUST include STL files in **printer/stl** folder.
> - You MUST include at least 1 image of the thing in **extras/images** folder.
> - If you want to use a license different from MIT, you MUST include a LICENSE file with the license in **Thing** folder.

## Considerations

- All designs in this repository are licensed under the MIT License unless a LICENSE file is included inside a Thing folder.
- All software used is FOSS.

## To Do

- [x] Add License
- [ ] Contribution guidlines

## Contributors

<a href="https://github.com/rapax00/3dthings/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=rapax00/3dthings" />
</a>
