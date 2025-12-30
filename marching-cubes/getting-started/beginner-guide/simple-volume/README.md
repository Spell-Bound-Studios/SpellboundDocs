# Simple Volume

Simple Volume a default implementation of a finite [volume.md](../../../terminology/volume.md "mention") where Marching Cubes will occur. You can add one or none or many to your scene. \
\
It must have a [voxel-volume-config.md](voxel-volume-config.md "mention") assigned. It must also have a Chunk Prefab that implements [ichunk](../../../advanced-usage/ichunk/ "mention"), for example [simple-chunk](../simple-chunk/ "mention").\
\
You may also edit the view distances to each of its Levels of Detail. The view distance rules enforce a minimum required distance between Levels of Detail to prevent seams and artifacts from forming.&#x20;
