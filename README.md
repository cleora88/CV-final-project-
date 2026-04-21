<h1 style="color:red;">License Plate Deblurring - Final Project</h1>

<p style="color:red;"><strong>This README was prepared for direct use in GitHub and Google Colab.</strong></p>

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cleora88/CV-final-project-/blob/main/License_Plate_Deblurring.ipynb)

## Project Overview

This project restores motion-blurred license plate images using:

- Synthetic plate generation
- Motion blur PSF simulation
- PSF parameter estimation (cepstrum and spectrum methods)
- Wiener deconvolution
- Quality metrics (PSNR, SSIM)

## Repository Structure

- `License_Plate_Deblurring.ipynb`: Main notebook report and runnable pipeline
- `src/`: Core implementation modules
- `data/`: Input/output data folders
- `code/` and `notebooks/`: Additional project materials
- `report.pdf`: Project report export
- `requirements.txt`: Python dependencies

## Run Locally

1. Create and activate a virtual environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open and run:

- `License_Plate_Deblurring.ipynb`

## Run in Google Colab

1. Click the **Open in Colab** button above.
2. If prompted, allow notebook execution permissions.
3. Run all cells from top to bottom.

<p style="color:red;"><strong>Important:</strong> For best results, run cells in order from the setup section.</p>
