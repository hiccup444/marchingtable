These two arrays allow for easy lookup of the indices of the two corner points that form an edge.
The edge index can be obtained from the triangulation table further below.

Values from http://paulbourke.net/geometry/polygonise/
Lookup table giving the index of the edge that each vertex lies on for any cube configuration.

The first index is the cube configuration.
Since a cube has 8 corners, there are 2^8 = 256 possible configurations.

The second index is the vertex index. No configuration has more than 16 vertices.
An entry of -1 means that there are no further vertices in the configuration.
