# Molly look mechanics

Molly is a compact pixel-art Black Lab. Keep the planted paws, lower torso, baseline, scale, and tail root anchored. The eyes lead each gaze, followed by a modest head and neck turn, a slight shoulder/chest shift, and soft delayed floppy-ear follow-through. Never rotate or tilt the whole sprite.

Motion budget: each 22.5-degree step changes the eyes, muzzle angle, head yaw/pitch, ear overlap, and upper chest by a small even amount. Preserve head size, facial proportions, coat markings, paw placement, volume, and baseline across the loop.

- 000 up: pupils and muzzle lift; head tips back slightly; chest opens; ears hang slightly back; both eyes remain visible.
- 090 screen-right: head yaws clearly toward the viewer's right; nose crosses right of head center; the near right-facing cheek, eye, and ear dominate while the far eye and ear partly occlude; shoulders turn subtly.
- 180 down: pupils and muzzle lower; chin tucks toward the chest; upper lids soften; ears fall slightly forward; upper back rounds minimally.
- 270 screen-left: head yaws clearly toward the viewer's left; nose crosses left of head center; the near left-facing cheek, eye, and ear dominate while the far eye and ear partly occlude; shoulders turn subtly.

Diagonals interpolate evenly between adjacent cardinal families with continuous occlusion changes. The tail stays attached and nearly stable; paws never slide; ears follow rather than lead. Preserve Molly's warm expression, brown eyes, black coat, rounded muzzle, and red tongue only where already natural to the pose.
