# Assignment 7 — Path Tracing

**Status:** ✅ done (multithread bonus done, microfacet skipped)

- explicit direct sampling on emitters
- indirect via cosine-weighted hemisphere, RR termination
- row-parallel MT

## Timings (Cornell box, 16 spp)

| Config | Time |
|---|---|
| single-thread | 4m03s |
| 8 threads     | 34s   |

## What tripped me up
Double-counting emission was the crux. If you evaluate direct lighting AND let indirect paths hit the light, the box is way too bright. Skip emitters on indirect bounces (`depth > 0`).
