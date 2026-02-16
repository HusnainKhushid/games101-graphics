# Assignment 5 — Whitted-Style Ray Tracing

**Status:** ✅ done

- primary ray generation with aspect + pixel-center offset + y flip
- Moller-Trumbore triangle intersection

## What tripped me up
First pass forgot the aspect ratio and drew y downward -- image was stretched and upside-down. Standard rookie NDC → screen mistake.
