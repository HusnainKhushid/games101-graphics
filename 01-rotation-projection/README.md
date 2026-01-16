# Assignment 1 — Rotation and Projection

**Status:** ✅ done (bonus done)

- `get_model_matrix` — Z-axis rotation
- `get_projection_matrix` — perspective (fixed sign convention on the second try)
- Bonus: Rodrigues rotation about arbitrary axis

## What tripped me up
The zNear/zFar sign convention. Course uses positive distances in front of the camera; camera looks -z. Flipping the sign of both fixed the mirrored triangle.
