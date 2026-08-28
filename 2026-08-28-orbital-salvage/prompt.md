# Prompt

Pasted as-is. One shot. No follow-ups.

```text
Create a single self-contained HTML file using Three.js via CDN.

Build a cinematic PS2-era orbital salvage mission above Earth. It must autoplay with no keyboard, mouse, button, or touch input.

Requirements:
1. Start with meaningful motion within one second and run a deterministic 32-second sequence that loops cleanly.
2. Show a damaged communications satellite tumbling above a curved Earth with a thin blue atmosphere, moving cloud bands, stars, and a sunrise at the horizon.
3. Animate a small service spacecraft approaching the satellite, firing visible maneuvering thrusters, matching the satellite's rotation, and locking on with two robotic arms or magnetic clamps. The approach must slow with believable relative motion instead of teleporting.
4. After docking, deploy a repair drone. The drone must leave the service craft, travel to a visibly damaged power coupler, remove the broken part, install a new glowing module, and return to the craft.
5. Make the repair change the scene: electrical sparks stop, warning-red lights turn stable green, the satellite stops tumbling, and both solar arrays unfold fully.
6. Choreograph six readable camera shots on a fixed timeline: debris-level approach, side tracking shot, close docking shot, repair-drone close-up, solar-array deployment orbit, and a final wide pullback with the repaired satellite crossing the sunrise.
7. Preserve object and state continuity. The service craft, satellite, drone, damaged coupler, and replacement module must remain spatially coherent across every camera cut. Keep the active subject in frame. Do not let the camera clip through geometry.
8. Add restrained debris, thruster plumes, repair sparks, navigation lights, metallic materials, bloom, and subtle lens flare. Use a fixed random seed so the sequence is repeatable.
9. Generate every mesh and texture procedurally. No external 3D assets.
10. Keep a stable 16:9 composition. Do not show controls, menus, title cards, debug geometry, axes, wireframes, or developer overlays.
```
