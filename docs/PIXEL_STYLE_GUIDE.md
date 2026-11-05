# Pixel Night — Visual Style Guide

## Creative direction
A quiet, cinematic pixel-art short about two strangers meeting on a rainy street. The mood is restrained, warm, and human: loneliness gives way to a small moment of connection.

## Canvas and rendering
- Logical canvas: 320 × 180 pixels (16:9).
- Scale only by integer-friendly nearest-neighbor rendering.
- Keep silhouettes and important props readable at the native resolution.
- Prefer deliberate clusters of pixels over noisy single-pixel detail.
- Use a compact palette; reuse colors across scenes.

## Palette
- Deep navy for night and shadow.
- Muted blue for buildings, pavement, and clothing.
- Warm amber for windows, lamps, and small emotional accents.
- Muted rose for the second character.
- Pale blue-grey for rain and distant highlights.

## Animation
- Target 8–12 visual updates per second for sprite-like motion.
- Keep character motion subtle: alternating steps, small turns, and pauses.
- Rain should move consistently and remain secondary to the story.
- Scene transitions should feel calm, not flashy.

## Composition
- Preserve negative space.
- Use the street and shop window to establish depth.
- Keep characters small enough to belong to the environment, but readable.
- Text should be brief and placed away from faces and key action.

## Avoid
- Gradients, bloom, heavy blur, photorealistic textures, excessive particles, and noisy post-processing.
- Tiny text that becomes unreadable after scaling.
- Overly fast cuts or exaggerated character movement.
- Third-party copyrighted sprites, music, or sound effects.

## Quality checklist
- [ ] Canvas remains 320 × 180.
- [ ] Pixel edges remain crisp when scaled.
- [ ] Palette stays consistent across scenes.
- [ ] Timeline seeking redraws the correct frame.
- [ ] Playback can pause, resume, and restart.
- [ ] No external assets are required for the prototype.
