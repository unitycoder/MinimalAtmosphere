![Preview shots](Preview.jpg)

# MinimalAtmosphere
A minimal (single cginc file) atmospheric scattering implementation for Unity to use as a base for further work and as a reference for anyone wanting to learn. Includes a simple skybox and object shader. No optimizations are used and so it probably should not be used in an actual application.

Supports Rayleigh and Mie scattering (single) + ozone absorption. The object shader also shows how atmospheric transmittance can be used to attenuate the directional light (planet shadow).

The project is using URP (just to get screen tonemapping and dithering) but you can export the atmosphere part to any pipeline, just grab the Atmosphere directory from Assets.

This repository represents my current best understanding of atmospheric scattering, so I happily accept corrections on things that are implemented incorrectly, just raise an issue and I will check it out.

# Recommended reading
[A Scalable and Production Ready Sky and Atmosphere Rendering Technique](https://sebh.github.io/publications/egsr2020.pdf)
