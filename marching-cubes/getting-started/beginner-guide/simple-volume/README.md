# Simple Volume

Simple Volume a default implementation of a finite Volume where Marching Cubes will occur. You can add one or none or many to your scene. \
\
It must have a Voxel Volume Config, a Data Factory, and a Boundary Overrides Asset assigned. It must also have a Chunk Prefab that implements IChunk, for example SimpleChunk.\
\
You may also edit the view distances to each of it's Levels of Detail. The view distance rules enforce a minimum required distance between Levels of Detail to prevent visible artifacts from forming.&#x20;
