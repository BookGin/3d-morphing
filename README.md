# 3D-morphing

## Roadmap

- [X] Split meshes to make the number of meshes identical
- [X] Split vertices to create independent faces
- [ ] Find the best corresponding mesh pairs
  - [X] Approach A: nearest-neighbor
  - [ ] Approach B: [edge ordering](http://web.mit.edu/manoli/morph/www/morph.html#algo)
  - [X] Future work: Approach C: parameterization, [See III.4.2.](https://tel.archives-ouvertes.fr/tel-00836048/file/ThA_se_MocanuBogdan.pdf).

- [X] linear interpolation for meshes

## Reference

- [three.js examples](https://stemkoski.github.io/Three.js/)
- [2D morphing demo](https://codepen.io/Sphinxxxx/pen/pZQRGB)
- [3D icosahedron morphing](https://codepen.io/rachsmith/post/beginning-with-3d-webgl-pt-4-animation)
- [3D Mesh Morphing using three.js](https://games.clarklavery.com/meshMorpher/index.html)
  - same number of meshes, pre-built meshes correspondence
