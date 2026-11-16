"""
Vibrational Spectra Analysis with Python (Google Colab)
Last updated: Feb 18, 2026.

This script was developed for the spectral analysis of Raman and FTIR (Fourier-transform infrared) spectroscopy data.

====================
DATA FORMAT REQUIRED
====================
- The input file must be in `.csv` or `.xlsx` format.
- Each row should represent an individual Raman/FTIR spectrum.
- The first row must contain the wavenumber values.
- The first column of each row (i.e., the first column of the file) must contain the class label for the corresponding spectrum.
- For group isolation in train/test, put ID on the first column and class on the second.

Make sure your file follows this format to ensure proper functioning of the script.

========
LICENSE
========
This code is licensed under the MIT License.

You are free to use, modify, and distribute this code, as long as proper credit is given to the original authors.

For full license details, refer to the LICENSE file.

Cite: Anjos, V. P., & Zezell, D. M. (2026). ViniciusAnjos96/VibrationalSpectra-DataAnalysis: Vibrational Spectroscopy Data Analysis (Version v1.0) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.24293827

========
RESEARCH BACKGROUND
========
This code is part of a Ph.D. research project conducted at the Laboratory of Biophotonics,
at Nuclear and Energy Research Institute (IPEN-CNEN), University of São Paulo, 
focusing on the use of spectroscopic and computational tools for the characterization 
of biological samples.

PhD Student - Vinicius Pereira dos Anjos, 
PhD Advisor - Prof. Dr. Denise Maria Zezell

Learn more about the lab: https://biophotonics.my.canva.site/

========
SUPPORT
========
This work was supported by CNPq (INCT-INTERAS 406761/2022-1; INCT INFO 409174/2024-6; Sisfoton 440228/2021-2; PQ 3134/2026-0;), FAPESP (2020/07065-4; 2025/03135-1), and CAPES (finance code 001). 
"""


