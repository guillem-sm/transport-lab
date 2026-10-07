# Transport Lab

An interactive teaching tool showing how a solute moves through an aquifer: advection, dispersion, linear sorption (retardation) and first-order decay, in 1D and 2D.

**Open it:** https://guillem-sm.github.io/transport-lab/

## What students can do
- Play the plume through time and drag sources and the observation well on the map
- Change aquifer parameters (q, φ, αL, αT, Dm, R, λ, b) and watch the plume and breakthrough curve respond
- Pin a setup and compare it against a changed one
- Load ready-made scenarios (dispersion, sorption, decay, continuous leak, two spills, 1D column)
- Use presentation mode on a projector (keys: Space play, ←/→ step, P pin, F fullscreen)

## Model
Analytical solutions of the advection–dispersion equation for uniform flow in an infinite, homogeneous, confined aquifer (depth-averaged in 2D). Pulse sources use the Gaussian point-source solution; continuous and finite-duration sources are obtained by superposition in time. Concentrations are in mg/L.

The whole tool is one self-contained `index.html` file; it runs in any modern browser, with no installation.
