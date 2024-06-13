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

> HTML example horizontal scroll
>
> ```html
> <div
>   style="overflow-x: auto; white-space: nowrap; display: flex; align-items: center;"
> >
>   <img
>     src="./images/thing.png"
>     alt="description 1"
>     style="display: inline-block; width: 300px; margin-right: 10px;"
>   />
>   <img
>     src="./images/thing.png"
>     alt="description 1"
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
>
> What are **Permitted files**? Extensions that you SHOULD include in the folder, only allowed files that are on the list.
>
> What are **Considerations**? You MUST comply with this.
>
> What are **Sugerences**? Recommendations, not mandatory.

### Extras (optional)

> **Permitted files**: not restricted.
>
> **Sugerences**: 2D design files (like SVG or DXF), assembly plans, electronics circuts, etc.

- `file.xxx`: brief description of your file (What is it? What does this contain? How use it?).
- ...

### GCODE-3MF (optional)

> **Permitted files**: GCODE and 3MF.
>
> **Considerations**: maintain the same name of the PART for consistency and understanding.
>
> **Sugerences**: files plug and play ready for print (GCODE), files with all settings for print (3MF). Include files (GCODE and 3MF) for each STL you include in the STL folder (you can place many STLs in one GCODE/3MF).

- `printable.gcode`: brief description of your gcode (What parts are here? Does it contain extra code?).
- `project.3mf`: brief description of you project (STLs included, estimated time, etc).
- ...

### Images (optional)

> This section is optional in the sense that it is not necessary to explain the images, but it is MUST to include at least one image in the Images folder.

> **Permitted files**: PNG.
>
> **Sugerences**: add images such as render, real print, STL, FreeCAD design, etc. If are image of a PART use the same name of the PART file for consistency and understanding.

- `thing.png`: brief description of the image (Is it a render or real print? What part/assembly is this?).
- ...

### Parts-Assemblys (mandatory)

> **Permitted files**: FCSTD, STEP.
>
> **Considerations**: choose descriptive names for the files like support_top_case_cover (You use this name for [GCODE-3MF](#gcode-3mf-optional) and [STL](#stl-mandatory)). For each FCSTD file, you MUST have one or more STEP files.
>
> **Sugerences**: if you have an FCSTD with many pieces, you can export one STEP for each one. Use the same name of parts to [Images](#images-at-least-1-1).

- `part.FCStd`: brief description of the part (What is this part?).
- `part.STEP`: idem.
- ...

### STLs (mandatory)

> **Permitted files**: STL.
>
> **Considerations**: maintain the same name of the PART for consistency and understanding.
>
> **Sugerences**: if you have an FCSTD with many pieces, you can export one STL for each one.

- `thing.stl`: brief description of the STL (What is this part? What face is better for touch the printer bed?).
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
