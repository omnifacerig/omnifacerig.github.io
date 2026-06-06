# OmniFaceRig — Project Page

Public project page for **OmniFaceRig: Fully Automatic Inner-Mouth-Aware Face Rigging Across Diverse 3D Character Topologies**.

Live site: https://omnifacerig.github.io

## Structure

- `index.html` — main page (hero, abstract, interactive Three.js showcase, results, pipeline, BibTeX)
- `libs/` — vendored three.js r164 (`three.module.js` + addons) and `meshopt_decoder.module.js`
- `assets/` — figures and videos (demo video, teaser, qualitative results, hero background)
- `dataset_viewer/` — 50 interactive GLB assets across 4 topology categories, **meshopt-compressed** (`EXT_meshopt_compression` + `KHR_mesh_quantization`), decoded in-browser by `MeshoptDecoder`
- `.nojekyll` — disables Jekyll so GitHub Pages serves all files verbatim

## Deploy (GitHub Pages)

This folder is self-contained. Push its contents to the root of the Pages repo:

```bash
git add . && git commit -m "project page" && git push
```

Everything loads via relative paths, so it works from any repo/subpath.
