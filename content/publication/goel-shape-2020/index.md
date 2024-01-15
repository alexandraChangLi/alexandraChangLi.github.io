---
title: 'Shape from Tracing: Towards Reconstructing 3D Object Geometry and SVBRDF Material
  from Images via Differentiable Path Tracing'
authors:
- Purvi Goel
- Loudon Cohen
- James Guesman
- Vikas Thamizharasan
- James Tompkin
- Daniel Ritchie
date: '2020-11-01'
publishDate: '2024-01-15T06:08:03.665599Z'
publication_types:
- paper-conference
publication: '*2020 International Conference on 3D Vision (3DV)*'
doi: 10.1109/3DV50981.2020.00129
abstract: Reconstructing object geometry and material from multiple views typically
  requires optimization. Differentiable path tracing is an appealing framework as
  it can reproduce complex appearance effects. However, it is difﬁcult to use due
  to high computational cost. In this paper, we explore how to use differentiable
  ray tracing to reﬁne an initial coarse mesh and per-mesh-facet material representation.
  In simulation, we ﬁnd that it is possible to reconstruct ﬁne geometric and material
  detail from low resolution input views, allowing high-quality reconstructions in
  a few hours despite the expense of path tracing. The reconstructions successfully
  disambiguate shading, shadow, and global illumination effects such as diffuse interreﬂection
  from material properties. We demonstrate the impact of different geometry initializations,
  including space carving, multi-view stereo, and 3D neural networks. Finally, with
  input captured using smartphone video and a consumer 360◦ camera for lighting estimation,
  we also show how to reﬁne initial reconstructions of real-world objects in unconstrained
  environments.
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/9320395/
---
