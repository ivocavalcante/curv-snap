# curv-snap

Source for Snap package of Curv project **(unoficial)**.

Original project URL: [GitHub/curv](https://github.com/curv3d/curv).

Snap package URL: [snapcraft.io/curv](https://snapcraft.io/curv)

# curv

Curv is a programming language for creating art using mathematics. It's a 2D and 3D geometric modelling tool that supports full colour, animation and 3D printing.

Features:

- Curv is a simple, powerful, dynamically typed, pure functional programming language.
- Curv is easy to use for beginners. It has a standard library of predefined geometric shapes, plus operators for transforming and combining shapes. These can be plugged together like Lego to make 2D and 3D models.
- Coloured shapes are represented using Function Representation (F-Rep). They can be infinitely detailed, infinitely large, and any shape or colour pattern that can be described using mathematics can be represented exactly.
- Curv exposes the full power of F-Rep programming to experts. The standard geometry library is written entirely in Curv. Many of the demos seen on shadertoy.com can be reproduced in Curv, using shorter, simpler programs. Experts can package techniques used on shadertoy as high level operations for use by beginners.
- Rendering is GPU accelerated. Curv programs are compiled into fragment shaders which are executed on the GPU.
- Curv can export meshes to STL, OBJ and X3D files for 3D printing. The X3D format supports full colour 3D printing (on Shapeways.com, at least). These meshes are defect free: watertight, manifold, with no self intersections, degenerate triangles, or flipped triangles.

This snapped version doesn't support opening an external editor ("-e" command-line option); you have to open it yourself.

For example geometries, go to https://github.com/curv3d/curv/tree/master/examples .

This is an UNOFFICIAL package, not related to the project. There are known issues with some GPUs setup; if you're interested in troubleshooting, feel free to contact me.
