# SimpleVolume

SimpleVolume a default implementation of a GeoForge [volume.md](../../../terminology/volume.md "mention"). It can be used to represent things such as a hunk of destructible rock, an ice sculpture, or a large but finite Terrain. GeoForge supports infinite terrains, but SimpleVolume is for finite volumes.\
\
A SimpleVolume must have a [voxel-volume-config.md](voxel-volume-config.md "mention"), a [data-factory.md](data-factory.md "mention"), and a [boundary-overrides.md](boundary-overrides.md "mention") assigned. It must also have a Chunk Prefab that implements [ichunk](../../../advanced-usage/ichunk/ "mention"), for example the default GeoForge [chunk.md](../../../terminology/chunk.md "mention"), [simplechunk.md](../simplechunk.md "mention").\
\
You may also change the view distances to each of its Levels of Detail. View distances are forced to maintain a minimum distance between Levels of Detail to prevent seams and artifacts from forming.&#x20;

