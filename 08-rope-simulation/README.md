# Assignment 8 — Mass-Spring Rope

**Status:** ✅ done

- explicit Euler (unstable — the point)
- semi-implicit Euler with damping (stable)
- Verlet with tiny damping (nicest)

## What tripped me up
Explicit Euler blows up in ~half a second at k=100, dt=1/60. Semi-implicit stabilises just by using the freshly-updated velocity for position. Verlet needs almost no damping and it still converges.
