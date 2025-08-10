# Cell Counting Dataset (cell_counting_dataset)

## Overview

This DeepTrackAI repository provides a copy of the **BBBC039v1** dataset  
[Caicedo et al., Cytometry Part A, 2019](https://doi.org/10.1002/cyto.a.23863),  
available from the [Broad Bioimage Benchmark Collection (BBBC)](https://bbbc.broadinstitute.org/BBBC039/)  
([Ljosa et al., Nature Methods, 2012](https://doi.org/10.1038/nmeth.2083)).

The dataset contains fluorescence microscopy images of Hoechst-stained nuclei of U2OS cells, intended for segmentation and cell counting benchmarking.

The collection includes 200 fields of view containing approximately 23,000 manually annotated nuclei, providing a high-quality ground truth for evaluating image segmentation methods.

### Summary

- **Number of images**: 200  
- **Approximate nuclei count**: 23,000  
- **Image size**: 520 × 696 pixels  
- **Format**:  
  - Images: 16-bit grayscale TIFF  
  - Labels: Segmentation masks (PNG)  
- **Color**: Grayscale  
- **Annotations**: Binary masks indicating nuclei locations

---

## Original Source

- **Title**: BBBC039 – Nuclei of U2OS cells in a chemical screen
- **Authors**: Juan C. Caicedo, et al.
- **Source**: [Broad Bioimage Benchmark Collection – BBBC039v1](https://bbbc.broadinstitute.org/BBBC039/)  
- **License**: [CC0 1.0 Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)

If you use this dataset in your research, please follow the original licensing terms and cite the original publications.

---

## Dataset Structure

```bash
/cell_counting_dataset
├── images/            # Raw 16-bit grayscale TIFF images
└── labels/            # Segmentation masks (PNG)
```

---

## How to Access the Data

### Clone the Repository
```bash
git clone https://github.com/DeepTrackAI/cell_counting_dataset
cd cell_counting_dataset
```

---

## Attribution

When using this replication dataset, please cite the original dataset as follows:  
*"We used image set BBBC039v1 (Caicedo et al., Cytometry Part A, 2019), available from the Broad Bioimage Benchmark Collection (Ljosa et al., Nature Methods, 2012)."*

### Cite the papers:
Caicedo JC, et al. *Evaluation of Deep Learning Strategies for Nucleus Segmentation in Fluorescence Images.* Cytometry Part A 95(9): 952-965 (2019). [https://doi.org/10.1002/cyto.a.23863](https://doi.org/10.1002/cyto.a.23863)  

```bibtex
@article{caicedo2019evaluation,
  title={Evaluation of deep learning strategies for nucleus segmentation in fluorescence images},
  author={Caicedo, Juan C and Roth, Jonathan and Goodman, Allen and Becker, Tim and Karhohs, Kyle W and Broisin, Matthieu and Molnar, Csaba and McQuin, Claire and Singh, Shantanu and Theis, Fabian J and others},
  journal={Cytometry Part A},
  volume={95},
  number={9},
  pages={952--965},
  year={2019},
  publisher={Wiley Online Library},
  doi={10.1002/cyto.a.23863}
}
```

Ljosa V, et al. *Annotated high-throughput microscopy image sets for validation.* Nature Methods 9: 637–637 (2012). [https://doi.org/10.1038/nmeth.2083](https://doi.org/10.1038/nmeth.2083)  

```bibtex
@article{ljosa2012annotated,
  title={Annotated high-throughput microscopy image sets for validation},
  author={Ljosa, Vebjorn and Sokolnicki, Katherine L and Carpenter, Anne E},
  journal={Nature methods},
  volume={9},
  number={7},
  pages={637},
  year={2012},
  publisher={Nature Publishing Group},
  doi={10.1038/nmeth.2083}
}
```

---

## License

This replication dataset is shared under the **CC0 1.0 Public Domain Dedication**, following the original licensing terms.
