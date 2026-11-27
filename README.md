# PT Indocement Tunggal Prakarsa Tbk — Citeureup 3D Interactive Map (v3)

Interactive, photorealistic Indocement-only 3D Digital Twin built in **Blender 5.3 Cycles (`AgX`)** and powered online by Open-Source GitHub 3D Engines:

- **Live Online 3D Viewer (Three.js + N8AO + Sky + Water + BVH Path Tracer):** https://haysan10.github.io/indocement-3d-map/
- **Alternative Open Engine View (Babylon.js 7 SSAO2 + WaterMaterial + ACES):** https://haysan10.github.io/indocement-3d-map/babylon.html
- **Direct Download GLB (`17.88 MB`, WebP PBR, `273,892` tris):** `indocement_3d_map_full.glb`

## Open-Source GitHub 3D Engine Technologies Used
1. [`mrdoob/three.js`](https://github.com/mrdoob/three.js) (`v0.187.0`) — Physical `Sky.js`, dynamic planar reflection/refraction `Water.js` clipped along Sungai Cileungsi, `AgXToneMapping`, and HDR `UnrealBloomPass`.
2. [`N8python/n8ao`](https://github.com/N8python/n8ao) — High-speed Screen-Space Ambient Occlusion (`N8AOPass`) sharpening trusswork, domes, preheaters, and pipe racks.
3. [`gkjohnson/three-gpu-pathtracer`](https://github.com/gkjohnson/three-gpu-pathtracer) + [`three-mesh-bvh`](https://github.com/gkjohnson/three-mesh-bvh) — Interactive in-browser BVH Path Tracing mode.
4. [`BabylonJS/Babylon.js`](https://github.com/BabylonJS/Babylon.js) (`babylon.html`) — `SSAO2RenderingPipeline`, `WaterMaterial`, `SkyMaterial`, PCF shadows, and ACES HDR pipeline.
5. **O3DE (`o3de/o3de`) & Godot 4 (`godotengine/godot`) Ready Asset Pack:** Since Open 3D Engine (O3DE) builds desktop/native Atom binaries rather than WebGL, the full GLB and modular PBR maps in `export/indocement_o3de_godot_pack/` are packaged for direct import into O3DE Asset Processor or Godot 4.

## Key Features (PT Indocement Citeureup Estate Only)
- **Complete Indocement Industrial Layout:** 4 Raw Material Storage Domes + Clinker Dome & Barrel Vault, Dual 5/6-Stage Open Preheater Towers, Dual Inclined Rotary Kilns with Heat-Shell Refractory Zones, Baghouse, Twin Aviation-Marked Smokestacks, 5 Cement Silos + Rail Hoppers, Central Process Halls, GMO & Plant 14 Control Office, Main Gate + Dual Weighbridge, Tank Farm + LPG + Cooling Tower, Paper Bag Div, Logistic Div, and Mining/Mechanical DP 02.
- **Sungai Cileungsi Border & Geological Soil Cutaway:** Clean estate island silhouette bounded south by Sungai Cileungsi, floodwalls, river boulders, and layered limestone/clay soil strata.
- **Photoreal PBR Materials & Vegetation:** Procedural & PIL-baked textures (`T_Ground_Indocement_BC/R`, 54-cycle corrugated cladding, crisp Indonesian/Indocement signage), and realized Geometry Nodes tropical rain trees, pinnate palms, shrubs, and grass.
