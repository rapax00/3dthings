This is a template for a README file for a 3D design.

Prayers written in grey color (whit `>`) is a instruction for you, you can delete this. Also you delete `(mandatory)` and `(optional)`. Also you edit delete `[Prayer]` and write your configuration.

# Your Thing Name

> Brief description of the thing.

## Index (mandatory)

> Modify table of contents to match with your project (See Files Included, and Print and Assembly Guide).

- [Images](#images-at-least-1-1-mandatory)
- [Print and Assembly Guide](#print-and-assembly-guide-mandatory)
- [Creator](#creator)

## Images (at least 1) (mandatory)

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

## Print and Assembly Guide (mandatory)

### Print (mandatory)

Printer used: [printer name]

> You can add more pieces with the same structure, copy `#### file.stl` section (include `##### Printer Settings`) and paste below `Extra settings` of you `file.stl` and above of `Asembly and extras`.

#### `file.stl`

> You can add more pieces with the same printer settings, add the name next to file.stl.

##### Printer Settings

- Nozzle: [nozzle diameter. e.g. 0.40mm]
- Resolution: [resolution. e.g. 0.20mm]
- Infill: [yes, what percentage and infill type?/no. e.g. 20% honeycomb]
- Filament material: [filament material. e.g. PLA]
- Raft: [yes, how many layers?/no. e.g. 3 layers]
- Brim: [yes, how width?/no. e.g. 3mm]
- Supports: [yes, what type?/no. e.g. tree supports]

> Extra settings or considerations (description for supports, layer color change, pause prints, fan speed, etc).

### Assembly and extras (optional)

> Add a step-by-step guide to assemble the thing. Mount pieces, add glue, extra list of materials, etc.

## Creator

> Add your signature, web/contact/social media and how to tip you.
