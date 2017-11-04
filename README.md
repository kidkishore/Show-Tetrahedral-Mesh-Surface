# Show-Tetrahedral-Surface

This algorithm generates and visualizes the surface of a tetrahedral mesh in the form of a triangle mesh in Unity. The tetrahedral mesh was generated from  a .stl model of a sphere with radius one, and passed into the Matlab function generateMesh().

By adjusting the parameters of the function to give a min-edge length of 0.1, we are given a tetrahedralized mesh of the sphere with 70 nodes and 198 tetrahedrons, organized as matrices in the 2 text files sphere_nodes.txt and sphere_elements.txt. 

The algorithm to generate the surface mesh is written in “assets/findSurface.cs”.
 
