# 3D Sample Files for Digital Preservation Testing

This repository provides sample 3D files in various “archive-friendly” formats and subversions for testing with digital preservation tools developed as part of the NFDI4Culture project These formats include glTF, DAE, X3D, OBJ, PLY and STL for volume-based 3D models and E57 for point clouds. To convert the files into different 3D formats, the tools [Blender](https://www.blender.org/), [Meshlab](https://www.meshlab.net/) and [CloudCompare](https://www.danielgm.net/cc/) were used.

## Files

An empty scene (**minimal**), a simple box mesh (**cube**) and a photogrammetrically scanned porcelain cockatoo [^1] (**cockatoo**) are each provided in different archive-friendly formats.

| Object     | Description                   | Vertices | Triangles | Colors/Textures/Cameras/Lighting                | Preview                             |
| ---------- | ----------------------------- | -------- | --------- | ----------------------------------------------- | ----------------------------------- |
| `minimal`  | empty scene                   | 0        | 0         | no                                              | ![](.github/media/minimal.jpg)      |
| `cube`     | simple box mesh               | 8        | 12        | no                                              | ![](.github/media/cube.jpg)         |
| `cockatoo` | 3D scanned porcelain cockatoo | 518,889  | 776,822   | yes, if supported by the respective file format | ![](.github/media/cockatoo.jpg)[^1] |

All 3D sample files provided in this repository follow the following naming pattern:

`[object]-[format]-[version]-[modification]-[status].[extension]`

Files ending with `-valid` pass validation with the validator scripts developed as part of this project.

## Related projects

- [DAE Validator for Archivematica](https://github.com/JoergHeseler/dae-validator-for-archivematica)
- [glTF Metadata Extractor for Archivematica](https://github.com/JoergHeseler/gltf-metadata-extractor-for-archivematica)
- [glTF Validator for Archivematica](https://github.com/JoergHeseler/gltf-validator-for-archivematica)
- [Siegfried Falls Back on Fido Identifier for Archivematica](https://github.com/JoergHeseler/siegfried-falls-back-on-fido-identifier-for-archivematica)
<!-- - [STL Cleaner](https://github.com/JoergHeseler/stl-cleaner) -->
- [STL Metadata Extractor for Archivematica](https://github.com/JoergHeseler/stl-metadata-extractor-for-archivematica)
- [STL Validator for Archivematica](https://github.com/JoergHeseler/stl-validator-for-archivematica)
- [X3D Validator for Archivematica](https://github.com/JoergHeseler/x3d-validator-for-archivematica)

## Acknowledgments

Special thanks to Grischka Petri and the colleagues from the SLUB Dresden, specifically from the Infrastructure and Long-Term Availability division, for their support and valuable feedback during the development.

## Imprint

[NFDI4Culture](https://nfdi4culture.de/) – Consortium for Research Data on Material and Immaterial Cultural Heritage

NFDI4Culture is a consortium within the German [National Research Data Infrastructure (NFDI)](https://www.nfdi.de/).

Author: [Jörg Heseler](https://orcid.org/0000-0002-1497-627X)

This repository is licensed under a [Creative Commons Attribution 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

NFDI4Culture is funded by the German Research Foundation (DFG) – Project number – [441958017](https://gepris.dfg.de/gepris/projekt/441958017).

### Licenses

[^1]: The ["Kakadu von Johann Joachim Kaendler, Meissen" (Cockatoo by Johann Joachim Kaendler, Meissen) 3D models](https://sketchfab.com/3d-models/cockatoo-von-johann-joachim-kaendler-meissen-ddebac799fa14d389a6acc68f9cbfcdf) and associated textures used in this repository are by [ZDF Digital](https://zdf.digital/) and [Porzellansammlung, Staatliche Kunstsammlungen Dresden (Porcelain collection, Dresden State Art Collections)](https://www.skd.museum/). They are licensed under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The original GLB file from the Sketchfab page has been used and, if necessary, converted into other formats. The resulting files may have been intentionally syntactically or semantically altered to validate the functionality of tools developed for digital preservation.
