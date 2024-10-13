This is a template for a README file for a 3D design.

Prayers written in grey color (whit `>`) is a instruction for you, you can delete this. Also you delete `(mandatory)` and `(optional)`. Also you edit delete `[Prayer]` and write your configuration.

# Your Thing Name

> Brief description of the thing.

## Index (mandatory)

> Modify table of contents to match with your project (See Files Included, and Print and Assembly Guide).

- [Files Included](#files-included)
  - [Extras](#extras-optional)
  - [GCODE-3MF](#gcode-3mf-optional)
  - [Images](#images-at-least-1)
  - [Parts-Assemblys](#parts-assemblys-mandatory)
  - [STL](#stl-mandatory)
- [Print](#print)
  - [Print](#print-mandatory)
    - [thing1.stl](#thing1stl)
      - [Printer Settings](#printer-settings)
- [Assembly and extras](#assembly-and-extras-optional)
- [Creator](#creator)

## Images (at least 1)

> Use images included in `./images` folder.
>
> MUST include at least one image of the thing. You can add more images.
>
> Use the format that you prefer to display images. e.g. HTML, Markdown, etc.

> HTML example mosaic
>
> ```html
> <div
>   style="overflow-x: auto; white-space: nowrap; display: flex; align-items: center;"
> >
>   <img
>     src="./images/thing.png"
>     alt="description"
>     style="display: inline-block; width: 300px; margin-right: 10px;"
>   />
>   <img
>     src="./images/thing.png"
>     alt="description"
>     style="display: inline-block; width: 300px; margin-right: 10px;"
>   />
> </div>
> ```

> Markdown example
>
> ```markdown
> ![description](./images/thing.png)
> ```

## Files Included (mandatorty)

> Describe what files are included in each folder. You MUST describe all files included.
>
> All files name MUST written in [snake_case](https://en.wikipedia.org/wiki/Snake_case). e.g. `support_top_case_cover.extension`.

### Design (mandatory)

> **Permitted files**: `.FCStd`, `.blend`, `.svg` and others files of FOSS.
>
> **Considerations**: choose descriptive names for the files like `support_top_case_cover`.

- `freecad/file.FCStd`: brief description of the file (What parts are in this file?).
- `freecad/file.blend`: idem.
- `freecad/file.svg`: idem.
- ...

### Extras (optional)

> **Permitted files**: not restricted.
>
> **Suggestions**: 2D design files, assembly plans, electronics circuits, etc.

- `images/file.png`: brief description of the image
- `file.xxx`: brief description of your file (What is it? What does this contain? How use it?).
- ...

## Printer

> **Permitted files**: `.gcode`, `.3mf`, `.stl`.
>
> **Sugerences**: maintain the same name of the design file for consistency and understanding.

- `3mf/file.3mf`: brief description of the 3mf (What is this file?).
- `gcode/file.gcode`:
- `stl/file.stl`: idem.
- ...

## Print and Assembly Guide

### Print (mandatory)

Printer used: [printer name]

> You can add more pieces with the same structure, copy `#### thing1.stl` section (include `##### Printer Settings`) and paste below `Extra settings` of you `thing1.stl` and above of `Asembly and extras`.

#### `thing1.stl`

> You can add more pieces with the same printer settings, add the name next to thing1.stl.

##### Printer Settings

- Nozzle: [nozzle diameter. e.g. 0.40mm]
- Resolution: [resolution. e.g. 0.20mm]
- Infill: [yes, what percentage and infill type?/no. e.g. 20% honeycomb]
- Filament material: [filament material. e.g. PLA]
- Raft: [yes, how many layers?/no. e.g. 3 layers]
- Brim: [yes, how width?/no. e.g. 3mm]
- Supports: [yes, what type?/no. e.g. tree supports]

> Extra settings or considerations (description for supports, layer color change, pause prints, fan speed, etc).

## Assembly and extras (optional)

> Add a step-by-step guide to assemble the thing. Mount pieces, add glue, extra list of materials, etc.

## Creator

> Add your signature, web/contact/social media and how to tip you.
