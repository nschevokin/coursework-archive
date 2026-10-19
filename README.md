# coursework-archive

University coursework from the MSc in Artificial Intelligence at the University of Bologna, by [Nikita Chevokin](https://github.com/nschevokin). Each folder is a self-contained assignment in a Jupyter notebook.

For my main projects, see the [pinned repositories](https://github.com/nschevokin).

| Folder | What it is | Techniques |
|---|---|---|
| [`Point Cloud Reconstruction & Surface Processing`](./Point%20Cloud%20Reconstruction%20%26%20Surface%20Processing) | **3D preprocessing pipeline** turning car meshes into clean, uniform point clouds: Poisson-disk resampling, visible-surface extraction from 64 virtual viewpoints, Poisson reconstruction, Taubin smoothing | Python, Open3D |
| [`Object_Detection_for_Accessibility`](./Object_Detection_for_Accessibility) | **Pet breed classification** on Oxford-IIIT Pets (37 classes): a custom residual CNN, compared against ablations (no batch norm, fewer residual blocks); module 2, with Giacomo Antonelli | PyTorch, ResNet-style blocks, ablation study |
| [`Image_Preprocessing_and_Feature_Extraction`](./Image_Preprocessing_and_Feature_Extraction) | **Product recognition of books** on shelf images: detect and match each book against reference covers (Image Processing and Computer Vision, module 1); with Giacomo Antonelli | OpenCV, NumPy, classical feature extraction and matching |
| [`Infix-to-Postfix`](./Infix-to-Postfix) | **Transformer** that translates mathematical expressions from infix to postfix notation | PyTorch, Transformer, sequence-to-sequence |

## Notes

- These are course assignments, kept as submitted. Results and write-ups are inside each notebook.
- Folder names are historical and in two cases no longer describe the content: the object-detection folder holds the pet-classification assignment, and the preprocessing folder holds book recognition. I've kept the names to avoid breaking links.

## License

MIT, see [LICENSE](./LICENSE).
