# Voxel Material Database

The Voxel Material Database is how to assign materials and textures. If you want to Add/Remove Materials, or change one of their names or textures, follow these steps:

1. Make your changes in the List of Materials.
2. Rightclick on the asset and select Validate Material Names, to ensure names are valid/unique.
3. Rightclick on the asset and Select Build Texture Arrays.
4. Find the SpellboundTerrain Material, and drag the texture arrays into its texture array fields

Note, this asset is not expected to undergo frequent changes, particularly to the names and the length/order of the list. If you write data generation or terraforming scripts that reference materials by index or by name, you will likely need to edit them when you change this asset.&#x20;
