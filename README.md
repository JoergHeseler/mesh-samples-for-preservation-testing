# 3D Sample Files for Digital Preservation Testing

This repository provides sample 3D files in various “archive-friendly” formats and subversions for testing with digital preservation tools developed within the NFDI4Culture project.

## Files

A an empty scene (`minimal`), a simple box mesh (`cube`) and a photogrammetrically scanned 3D model of mask (`mask`) are each provided in different archive-friendly formats. Each file name consist of the object name, followed by the file format, the version or type, the changes made and finally the validation result. The tools [Blender](https://www.blender.org/), [Meshlab](https://www.meshlab.net/) and [CloudCompare](https://www.danielgm.net/cc/) were used for file conversion. Files ending with `-valid` pass validation with the validator scripts developed as part of this project. Invalid files, on the other hand, contain a short error description at the end of the file name.

| Name        | Description               | Vertices | Colors/Texture/Camera/Lighting | Thumb                     |
| ----------- | ------------------------- | -------- | ------------------------------ | ------------------------- |
| `minimal-*` | empty scene               | 0        | no                             | [](./images/minimal.jpg)! |
| `cube-*`    | simple box mesh           | 12       | no                             | [./images/cube.jpg]!      |
| `mask-*`    | 3D scanned demon mask[^1] | 62.323   | yes, if supported              | [./images/mask.jpg]!      |

## Related projects

- [DAE Validator for Archivematica](https://github.com/JoergHeseler/dae-validator-for-archivematica)
- [glTF Metadata Extractor for Archivematica](https://github.com/JoergHeseler/gltf-metadata-extractor-for-archivematica)
- [glTF Validator for Archivematica](https://github.com/JoergHeseler/gltf-validator-for-archivematica)
- [Siegfried Falls Back on Fido Identifier for Archivematica](https://github.com/JoergHeseler/siegfried-falls-back-on-fido-identifier-for-archivematica)
- [STL Metadata Extractor for Archivematica](https://github.com/JoergHeseler/stl-metadata-extractor-for-archivematica)
- [STL Validator for Archivematica](https://github.com/JoergHeseler/stl-validator-for-archivematica)
- [X3D Validator for Archivematica](https://github.com/JoergHeseler/x3d-validator-for-archivematica)

## Imprint

[NFDI4Culture](https://nfdi4culture.de/) – Consortium for Research Data on Material and Immaterial Cultural Heritage

NFDI4Culture is a consortium within the German [National Research Data Infrastructure (NFDI)](https://www.nfdi.de/).

Author: [Jörg Heseler](https://orcid.org/0000-0002-1497-627X)

This project is licensed under a [Creative Commons Attribution 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

NFDI4Culture is funded by the German Research Foundation (DFG) – Project number – [441958017](https://gepris.dfg.de/gepris/projekt/441958017).

## Licenses

[^1]: The ["Exotisch wirkende Maske aus Bali" (Exotic-looking mask from Bali) 3D models](https://sketchfab.com/3d-models/exotisch-wirkende-maske-aus-bali-ebdeba7d3e60499cb33037355b189acb) and associated textures used in this repository are by [Badisches Landesmuseum (Baden State Museum)](https://www.landesmuseum.de/) and are licensed under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
