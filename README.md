# Relativistic-Gravitational-Lensing-Einstein-Ring-Simulator
# 🌌 Relativistic Gravitational Lensing & Einstein Ring Simulator

A computational physics simulation modeling **General Relativity photon deflection** and strong gravitational lensing by massive astrophysical bodies. The project numerically solves the gravitational lens equation and ray-traces background light sources to visualize magnified Einstein rings, arcs, and critical caustic curves.

---

## 🔬 Theoretical Background & Physics Model

According to Albert Einstein's Theory of General Relativity, massive objects (such as galaxy clusters or massive elliptical galaxies) warp surrounding spacetime, causing light rays from distant background sources to bend. 

### Key Equations Implemented:
1. **Deflection Angle ($\alpha$):** Calculated using the point-mass gravitational lens bending formula scaled by the Einstein radius ($\theta_E$):
   $$\alpha(\theta) = \frac{\theta_E^2}{\theta}$$
2. **Lens Mapping Equation:** Maps observer sky coordinates ($\theta_x, \theta_y$) back to source plane coordinates ($\beta$):
   $$\vec{\beta} = \vec{\theta} - \vec{\alpha}(\vec{\theta})$$
3. **Magnification Matrix:** Computes the Jacobian determinant of the lens mapping equation to model gravitational amplification and critical caustic curves where background flux density is magnified.

---

## 🚀 Key Features

* **General Relativity Ray-Tracing:** Vectorized mapping of observer pixels back to distant source galaxies.
* **Einstein Ring Visualization:** Accurately renders circular and arcuate image distortions around foreground gravitational lenses.
* **Magnification & Caustic Mapping:** Simulates localized brightness amplifications using Jacobian determinant calculations.

---
Result
EinsteinRing.png
