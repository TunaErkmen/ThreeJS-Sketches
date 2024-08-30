# getting-started-with-threejs

To actually be able to display anything with three.js, we need three things: scene, camera and renderer, so that we can render the scene with camera.

"**antialias**: true softens the sharp edges in the scene."
fov : field of view, measured in degrees,
aspect: is the ratio of the camera's width to its height. it ensures that the scene's proportions are correct.
near and far: define the range of distances from the camera at which objects are visible.


**const geo**= new THREE.IcosahedronGeometry(1.0, 2);
THREE.IcosahedronGeometry: This class creates the geometry for an icosahedron, which is a polyhedron with 20 faces.
1.0: This defines the radius of the icosahedron. In other words, all vertices of the icosahedron are 1.0 units away from the center.
2: This parameter sets the level of detail (subdivision) for the geometry. As the level of detail increases, the icosahedron has more faces and vertices, making it appear smoother and more detailed.