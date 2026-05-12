# Generation Notes

Pet name: `Xiao Hei`

Internal pet id: `nightleaf`

The pet was built from reference images of a rounded black cat-like character with pale green ears, oversized cream eyes, dark brown outlines, tiny paws, and a small cyan mouth.

## Animation Rows

The final atlas contains the standard Codex pet rows:

- `idle` - 6 frames
- `running-right` - 8 frames
- `running-left` - 8 frames, derived by mirroring `running-right`
- `waving` - 4 frames
- `jumping` - 5 frames
- `failed` - 8 frames
- `waiting` - 6 frames
- `running` - 6 frames
- `review` - 6 frames

## QA Summary

Generated rows were checked for frame count, identity consistency, transparent background cleanup, unclipped poses, and forbidden detached effects. The final contact sheet and validation outputs are stored under `qa/`.

Video previews were skipped because the local machine did not have the video rendering dependency available during packaging.
