# Lab 5 — Spatial Filtering: Smoothing and Sharpening

This lab explores image smoothing, sharpening, and noise removal using Python and OpenCV in a Jupyter Notebook.

## Tasks

- Apply a manually created 7×7 box filter.
- Compare 5×5 and 21×21 Gaussian filters.
- Sharpen an image using a 3×3 Laplacian operator.
- Compare 3×3, 9×9, and 15×15 box filters.
- Compare median and Gaussian filtering on salt-and-pepper noise.
- Apply bilateral filtering to smooth images while preserving edges.
- Demonstrate unsharp masking.

## Libraries

- OpenCV
- NumPy
- Matplotlib
- scikit-image

## Key Observations

- Larger box filters produce stronger blur and greater detail loss.
- Gaussian filters use weighted averaging for smooth blur.
- Median filtering effectively removes salt-and-pepper noise.
- Bilateral filtering smooths regions while preserving major edges.
- Laplacian sharpening and unsharp masking enhance edges and fine details.

## How to Run

Open `Lab5_Spatial_Filtering.ipynb` in Jupyter Notebook or JupyterLab and run the cells from top to bottom.
