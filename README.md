# Cell Counting Dataset

Welcome to the GitHub page of DeepTrackAI's Cell Counting dataset. The repository contains the image set BBBC039v1 [Caicedo et al., 2018](https://www.biorxiv.org/node/103064.full), available from the [Broad Bioimage Benchmark Collection](https://bbbc.broadinstitute.org/BBBC039/) and described in [Ljosa et al., Nature Methods, 2012](https://www.nature.com/articles/nmeth.2083).

The data set has a total of 200 fields of view of nuclei captured with fluorescence microscopy using the Hoechst stain. The collection has around 23,000 single nuclei manually annotated to establish a ground truth collection for segmentation evaluation.

This dataset has been used for evaluating the performance of Deep Learning models. More details of the evaluation framework can be found in this [bioRxiv preprint by Caicedo et al. 2018](https://www.biorxiv.org/node/103064.full).


## Description

The Cell Counting dataset contains 200 images. Each image is a 16-bit grayscale picture in TIFF, and the associated label is the manually-annotated segmentation map in PNG.

- **Dataset Size**: 200 images
- **Image Size**: 520x696 pixels
- **Color**: Grayscale
- **Labels**: Segmentation map

## Usage

To use the Cell Counting dataset in your project:

1. Clone this repository to your local machine.
2. Import the dataset into your machine learning framework of choice.
3. Train or evaluate your models using the dataset.

### Download via Command Line

To clone the repository and access the Cell Counting dataset:

```bash
git clone -b cell_counting_dataset github.com/DeepTrackAI/cell_counting_dataset
cd cell_counting_dataset
```

## License

[Copyright: CC0](https://creativecommons.org/publicdomain/zero/1.0/). To the extent possible under law, the various contributors of the image sets have waived all copyright and related or neighboring rights to BBBC039v1.

## Contributing

If you find any issues with the dataset or have suggestions for improvements, please open an issue or submit a pull request.
