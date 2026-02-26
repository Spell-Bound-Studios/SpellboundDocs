# Octree

An Octree is a data structure that recursively subdivides a 3-Dimensional Region into 8 equal regions, by cutting it in half along each axis. \
\
A GeoForge Octree subdivides [chunk.md](chunk.md "mention")s down to Octree Nodes small enough that one mesh can represent all its [voxel.md](voxel.md "mention")s. The Octree is critical for Levels of Detail. The Octree of a distant [chunk.md](chunk.md "mention") will not subdivide at all and will create a coarse mesh that spans the entire [chunk.md](chunk.md "mention"), by reading [voxel.md](voxel.md "mention")s at coarse intervals. The Octree of a nearby [chunk.md](chunk.md "mention") will subdivide, possibly multiple times, and create smaller finer meshes, by reading the [voxel.md](voxel.md "mention")s at the finest resolution.&#x20;
