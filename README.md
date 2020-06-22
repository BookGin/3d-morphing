# 3D-morphing

## Roadmap

- [X] Load custom objects rathan than nerdy polyhedrons
- [X] Normalize the object
- [X] Split meshes to make the number of meshes identical
- [X] Split vertices to create independent faces
- [X] Find the best corresponding mesh pairs
  - [X] Approach A: nearest-neighbor
  - [X] Approach B: [edge ordering](http://web.mit.edu/manoli/morph/www/morph.html#algo)
  - [X] Future work: Approach C: parameterization, [See III.4.2.](https://tel.archives-ouvertes.fr/tel-00836048/file/ThA_se_MocanuBogdan.pdf).
- [X] linear interpolation for meshes
- [X] User interaction interface, [See upper-right control window](https://threejs.org/docs/scenes/geometry-browser.html#BoxGeometry)
      By [data.gui](http://workshop.chromeexperiments.com/examples/gui/#1--Basic-Usage)

## Reference

- [three.js examples](https://stemkoski.github.io/Three.js/)
- [2D morphing demo](https://codepen.io/Sphinxxxx/pen/pZQRGB)
- [3D icosahedron morphing](https://codepen.io/rachsmith/post/beginning-with-3d-webgl-pt-4-animation)
- [3D Mesh Morphing using three.js](https://games.clarklavery.com/meshMorpher/index.html)
  - same number of meshes, pre-built meshes correspondence
