# System Overview

Marching Cubes is an algorithm that acts upon a 3D grid of voxels, encompassing a volume. In our implementation this is represented by the interface IVolume. The IVolume is subdivided into IChunks, small enough to handle within your frame budget. \
\
If you are utilizing or extending the system, your primary focus will be on implementing IVolume and IChunk to your liking, and on utilizing the SbVoxel static commands to interact with the IVolume(s). \
\
A simple implementation of IVolume and IChunk are provided in the package; SimpleVolume and SimpleChunk.&#x20;
