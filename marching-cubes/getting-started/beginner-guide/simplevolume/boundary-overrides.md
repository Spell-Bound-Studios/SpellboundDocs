# Boundary Overrides

Boundary Overrides is an asset to override the initial data and any terraforming changes at the boundaries of the [volume.md](../../../terminology/volume.md "mention"). Assets are provided for a variety of boundaries. Some examples:

* "AllEmpty" guarantees that the [voxel.md](../../../terminology/voxel.md "mention")s at the boundaries of the [volume.md](../../../terminology/volume.md "mention")will all be empty, so a 3D shape will close properly so you won't be able to see inside it.&#x20;
* "Landscape" guarantees that the [voxel.md](../../../terminology/voxel.md "mention")s at the top boundary will stay empty, and the [voxel.md](../../../terminology/voxel.md "mention")s at the bottom boundary will stay full. So if you dig to the bottom of the [volume.md](../../../terminology/volume.md "mention"), you won't dig thru it, and if you build to the top of the [volume.md](../../../terminology/volume.md "mention"), you won't overflow to above it. The boundaries on the sides are unaffected.&#x20;





