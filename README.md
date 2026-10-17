# Catapult Projectile Physics Simulation Canvas
Simulate medieval siege weapon projectile trajectories with accurate physics including optional air resistance drag.
## Features
- Three weapon types: Catapult (45° medium velocity), Trebuchet (high velocity optimal angle), Ballista (flat trajectory, high speed)
- Launch angle (1°–89°), initial velocity (5–120 m/s), and projectile mass controls with sliders
- Optional air resistance using Euler integration with drag force F_d = ½ρC_dAv²
- Animated projectile flying along the arc with real-time range/height/time-of-flight readout
- Comparison mode: plots 5 trajectories (15°/30°/45°/60°/75°) simultaneously to show 45° optimum
## Usage
Select a weapon type, adjust sliders, then click Launch to animate the projectile. Use "Compare 5 Angles" to overlay trajectories. Toggle "Range Graph" to see a range vs. angle curve in the canvas corner.
