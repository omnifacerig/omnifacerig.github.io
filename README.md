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

## Copyright and use

Copyright © 2026 Meta Platforms, Inc. All rights reserved.

The 3D models, images, and videos in this repository (including `dataset_viewer/`) are provided solely for display on the project page. They are not part of the OmniFaceRig dataset release and are not licensed for download, redistribution, or any other use.

The released OmniFaceRig dataset is available at [facebookresearch/omnifacerig](https://github.com/facebookresearch/omnifacerig) under the FAIR Noncommercial Research License.

## Citation

If you find this work useful, please cite the [OmniFaceRig paper](https://doi.org/10.1145/3842582) (ACM Transactions on Graphics; the latest version is on [arXiv](https://arxiv.org/abs/2606.08043)):

```bibtex
@article{wang2026omnifacerig,
  title={OmniFaceRig: Fully Automatic Inner-Mouth-Aware Face Rigging Across Diverse 3D Character Topologies},
  author={Wang, Chao and Ma, Guangyao and Doublestein, John and Chen, Junming and Lin, Yiming and Su, Zhaoen and Luo, Xiaomin and Yin, Yushan and Cheng, Shiyang and Shen, Jie and Roble, Doug and Wang, Dilin and Li, Yilei and Ranjan, Rakesh},
  journal={ACM Transactions on Graphics},
  volume={45},
  number={6},
  articleno={231},
  numpages={16},
  year={2026},
  doi={10.1145/3842582}
}
```
