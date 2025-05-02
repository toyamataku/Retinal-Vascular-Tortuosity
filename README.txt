# SnakeRateSoftWare

SnakeRateSoftWare is a Windows-based software tool designed for semi-automatic retinal vessel tortuosity analysis. It utilizes advanced Livewire segmentation to assist with vessel tracing, offers customizable circle multipliers based on optic-disc diameters, and generates quantitative Excel outputs detailing vessel tortuosity angles and intersections.

---

##  Key Features

* **Livewire Segmentation**: Easy and precise tracing of retinal vessels.
* **Circle Multipliers**: Draw circles at multiples of optic-disc diameter (2× to 20×).
* **Automatic Quantification**: Outputs detailed Excel reports and annotated images.

---

##  System Requirements

* **Operating System**: Windows 10/11 (64-bit only)
* **Standalone EXE**: No additional Python installation required
* **Python source (optional)**: Python 3.12 (Windows ×64) with specific dependencies:

  ```
  Cython==3.0.11
  numpy==2.1.1
  pandas==2.2.3
  opencv-python==4.10.0.84
  scikit-image==0.24.0
  scipy==1.14.1
  networkx==3.3
  ```

---

##  Quick Start (Using Standalone EXE)

1. Download `SnakeRate_v1_win64.exe` from the latest [GitHub release](https://github.com/toyamataku/Retinal-Vascular-Tortuosity/releases/latest).
2. Double-click the EXE file to launch.
3. Select a retinal image (JPG/PNG).
4. Click two opposite points on the optic-disc edges.
5. Select desired circle multipliers (e.g., 4×, 8×, 12×).
6. Use Livewire tracing to detect vessels:

   * Press **Z** to zoom in.
   * Press **R** to undo the previous tracing step.
   * Press **Q** to complete tracing.
7. Results (annotated image and `result.xlsx`) are saved automatically in the image's folder.

---

##  Checksum (for EXE verification)

SHA-256:

```
7b6777a6b2bfabf5ede5b0050d6329c4ca4875c0a89babde6f2d1f2e556d28e7
```

Verify integrity:

```
certutil -hashfile SnakeRate_v1_win64.exe SHA256
```

---

##  Citation

Please cite this software using the following DOI:

Toyama, T. SnakeRateSoftWare (v1.0). Zenodo, 2025. DOI: [10.5281/zenodo.15321286](https://doi.org/10.5281/zenodo.15321286)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15321286.svg)](https://doi.org/10.5281/zenodo.15321286)

---

##  License

* MIT License for non-commercial academic use.
* Commercial use requires separate licensing agreements.

Contact: **[toyama.ophthalmol@gmail.com](mailto:toyama.ophthalmol@gmail.com)**

---

##  Disclaimer

This software is provided "as is," without any warranty. The author is not liable for any direct or indirect damages arising from its use.
