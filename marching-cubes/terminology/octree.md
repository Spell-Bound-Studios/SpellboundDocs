# Octree

An Octree is a data structure that recursively subdivides a 3-Dimensional Region into 8 equal regions, by cutting it in half along each axis. \
\
In context, the Octree subdivides Chunks down to Octree Nodes small enough that one mesh can represent all it's voxels. The Octree is critical for Levels of Detail. The Octree of a distant Chunk will not subdivide, and will create a coarse mesh that spans the entire chunk, by reading voxels at coarse intervals. The Octree of a nearby Chunk will subdivide, possibly multiple times, and create smaller finer meshes, by reading the voxels at the finest resolution.&#x20;
