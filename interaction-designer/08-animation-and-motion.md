# Animation & Motion

Use motion to clarify, connect, and delight—never to distract.

- Guide Attention and Feedback: Animate state changes and results (e.g., slide-in menus, error shake, item fade-in) to show cause-and-effect.
- Easing and Natural Movement: Prefer non-linear curves (ease-out, ease-in-out) or physics-based springs for realistic feel over rigid linear motion.
- Duration and Timing: Keep transitions brisk (≈100–500ms for simple changes, up to ~1s for complex sequences). Respect reduce-motion preferences.
- Motion Meaning: Animate with purpose—clarify relationships, provide continuity, or add brief delight. Avoid gratuitous motion.
- Consistency and Style: Establish a motion language aligned to product personality and platform norms; apply consistently.
- Performance: Favor GPU-friendly properties (transform, opacity). Avoid animating layout/paint-heavy properties at scale.
- Transition Design: Connect states with shared element transitions and layered choreography to reduce cognitive load.
- Hierarchy via Staging: Sequence animations (e.g., backdrop fades then dialog pops) to lead the eye.
- Delight vs Distraction: Keep celebratory effects optional/non-blocking and quick.

Aim for motion that feels invisible in service of comprehension and responsiveness.

