# Voxel Material Database

The Voxel Material Database is how to assign materials and textures. If you want to Add/Remove Materials, or change one of their names or textures, follow these steps:

* Make your changes in the List of Materials.
* Rightclick on the asset and select Validate Material Names, to ensure names are valid/unique.
* Rightclick on the asset and Select Build Texture Arrays.
* Find the SpellboundTerrain Material, and drag the texture arrays into it's texture array fields.

Note, this asset is not expected to undergo frequent changes, particularly to the names and the length/order of the list. If you write data generation or terraforming scripts that reference materials by index or by name, you will likely need to edit them when you change this asset.&#x20;
