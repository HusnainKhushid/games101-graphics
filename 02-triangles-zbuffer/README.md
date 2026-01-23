# Assignment 2 — Triangles and Z-buffering

**Status:** ✅ done (MSAA bonus done)

- barycentric inside test + depth interp
- MSAA 2x2 with per-sample z, resolved on write

## What tripped me up
First pass rasterised silhouettes but used one z per triangle so overlap looked wrong. The MSAA seam fix was the interesting bit: keep sub-samples independent and only average at resolve.
