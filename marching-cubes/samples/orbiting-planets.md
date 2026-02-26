# Orbiting Planets

This sample demonstrates multiple GeoForge [volume.md](../terminology/volume.md "mention")s in motion. It's a mini-solar system, where each planet is a [volume.md](../terminology/volume.md "mention").

For each planet, the [volume.md](../terminology/volume.md "mention")is a [simplevolume](../getting-started/beginner-guide/simplevolume/ "mention"), the [chunk.md](../terminology/chunk.md "mention")is a [simplechunk.md](../getting-started/beginner-guide/simplechunk.md "mention").  Each planet's [data-factory.md](../getting-started/beginner-guide/simplevolume/data-factory.md "mention")is a "Noisy Sphere" of a different size and different material. Each planet's [boundary-overrides.md](../getting-started/beginner-guide/simplevolume/boundary-overrides.md "mention")are "AllEmpty" to make them proper closed 3D Shapes, but they are seperate assets to match the material to the material the planet is made of. \
\
Each planet's [volume.md](../terminology/volume.md "mention") is 64 x 64 x 64 units with a resolution of 0.5 units per [voxel.md](../terminology/voxel.md "mention").

Each planet's [volume.md](../terminology/volume.md "mention")has "IsMoving" set to true. While this is true, it updates the Triplanar material shader every frame with a new position and rotation to use as its origin. If you try running the scene with "IsMoving" set to false you will see that the textures appear to "scroll across" the mesh, rather than stick to the mesh.\
\
Terraforming has a "laser beam" visual effect, just for fun to lean into the space/sci-fi setting of the scene.&#x20;

<figure><img src="../../.gitbook/assets/gf8 (1).png" alt=""><figcaption></figcaption></figure>

