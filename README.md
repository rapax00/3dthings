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

### Why free and open?

I believe that the best way to learn and grow is by sharing and receiving knowledge.

### Mision

To share and collaborate with the 3D maker community to create better things.

### Vision

FOST concept: Free and Open Source Things.

To create a large collection of 3D designs for free use and collaboration.

### Software stack

> All software used are FOSS.

- FreeCAD: For 3D modeling.
- PrusaSlicer: For slicing.
- Inkscape: For 2D design.

## Repo structure and files

```
3DThings
├───Thing
│   ├───Extras
│   │   ├───file.xxx
│   ├───GCODE-3MF
│   │   ├───printable.gcode
│   │   ├───project.3mf
│   ├───Images
│   │   ├───thing.png
│   ├───Parts
│   │   ├───part.FCStd
│   │   ├───part.STEP
│   ├───STL
│   │   ├───thing.stl
│   ├───README.md
├───README.md
```

- Thing: Folder with all files of the thing. One folder per thing.
  - Extras (optional): Extra files like 2D designs, plans, electronics, etc.
  - GCODE-3MF (optional): GCODE and 3MF files for printing and configuration.
  - Images (at least 1): Images of the thing. Render, STL, real print, etc.
  - Parts (mandatory): Parts/designs of the thing in native editable format.
  - STL (mandatory): STL files of the thing.
  - README.md: Description of the thing.
- CONTRIBUTING.md: Guidelines for contributions.
- README.md: Main description of the repo.
- LICENSE: License of the repo and all things.

## Considerations

- All designs in this repo are under the license in the main folder.
- All software used is FOSS.

## To Do

- [ ] Add License
- [ ] Contribution guidlines

## Contributors

<a href="https://github.com/rapax00/3dthings/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=rapax00/3dthings" />
</a>
