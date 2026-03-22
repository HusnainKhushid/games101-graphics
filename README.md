# GAMES101 — Introduction to Computer Graphics

Python notebook translations of the [GAMES101](https://sites.cs.ucsb.edu/~lingqi/teaching/games101.html)
(Lingqi Yan, UCSB) assignments. Nine assignments, from a rotate-a-point warm-up
to a Cornell-box path tracer.

The course ships C++ starter code; I did the same tasks as `.ipynb` notebooks in
numpy so I could iterate on the math without a build cycle.

---

## Progress

⬜ not started · 🔨 in progress · ✅ complete

| | Assignment | Topic | Block |
|:-:|---|---|---|
| ✅ | [`00-vectors-matrices`](00-vectors-matrices/) | Vectors and Matrices | Environment |
| ✅ | [`01-rotation-projection`](01-rotation-projection/) | Rotation and Projection | Rasterisation |
| ✅ | [`02-triangles-zbuffer`](02-triangles-zbuffer/) | Triangles and Z-buffering | Rasterisation |
| ✅ | [`03-shading-textures`](03-shading-textures/) | Pipeline and Shading | Rasterisation |
| ✅ | [`04-bezier`](04-bezier/) | Bézier Curves | Geometry |
| ✅ | [`05-whitted-raytracing`](05-whitted-raytracing/) | Whitted-Style Ray Tracing | Ray tracing |
| ✅ | [`06-bvh`](06-bvh/) | Acceleration Structure | Ray tracing |
| ✅ | [`07-path-tracing`](07-path-tracing/) | Path Tracing | Ray tracing |
| ✅ | [`08-rope-simulation`](08-rope-simulation/) | Mass-Spring Rope | Animation |

**9 / 9 complete**

---

## The arc

| Block | Assignments | Ends with |
|---|---|---|
| **Rasterisation** | 0 – 3 | a textured, bump-mapped cow with Blinn-Phong shading |
| **Geometry** | 4 | anti-aliased Bézier curves |
| **Ray tracing** | 5 – 7 | a Cornell box rendered by Monte-Carlo path tracing |
| **Animation** | 8 | a mass-spring rope, and a lesson in integrator stability |

## Layout

```
NN-assignment-name/
├── README.md    the tasks, the functions to implement, notes
├── src/*.ipynb  the notebook(s) I wrote
└── results/     rendered images (where relevant)
```
