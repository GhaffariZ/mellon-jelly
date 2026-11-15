# Melon Jelly — Material Studies / No. 009

An interactive real-time WebGPU physical material simulation and rendering study exploring jelly soft-body physics, fluid surface light transport, and tactile elasticity.

## Features

- **WebGPU Native Pipeline**: High-performance compute and graphics shaders.
- **Dynamic Jelly Deformation**: Real-time soft-body viscoelastic physics and impulse response.
- **Material Optical Rendering**: Subsurface scattering, fresnel reflection, specular highlights, and ambient occlusion.
- **Interactive Controls**: Touch, click, and drag to prod, wobble, and manipulate the jelly material.
- **Editorial UI**: Minimalist studio aesthetic with responsive viewport controls.

## Getting Started

Because this project uses native WebGPU, open `index.html` in a modern browser that supports WebGPU (e.g., Google Chrome 113+, Chromium, or Microsoft Edge):

```bash
# Optional: run a local static web server
npx serve .
# or
python3 -m http.server 8080
```

Then visit `http://localhost:8080` in your WebGPU-capable browser.

## License

MIT License.
