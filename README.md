# N4x4-T8-characterization
Code and data used in the paper "Calibration and characterization of an active photonic nulling interferometer"

## Contents

| Path | Description |
|---|---|
| `N4x4-T8_characterisation.ipynb` | Bench pipeline: injection balancing, phase-shifter calibration, systematic scans, null calibration, phasors, distributions vs. RMS |
| `bench_config.yml` | Bench configuration loaded by the pipeline |
| `src/N4x4_T8_characterisation/` | Systematic scan and matrix-model fitting (MPE, CMPCE and variants) |
| `src/utils/latexio.py` | Export of matrices/vectors to LaTeX |
| `test_fit_18.03-18h52.ipynb`, `test_fit_18.03-20h36.ipynb` | Model fits of the two characterizations (18h52 and 20h36) |
| `highlighted_results/2026-03-18_b38b520/` | Raw and processed data of both runs (`1_` = 18h52, `2_` = 20h36): `systematic_scan.npz`, `Model.npz`, `null_calibration.npz`, output frames, figures |
| `to_share/` | Gauge-corrected matrices, comparison of both runs, null calibration and phasor analysis |
| `detector_optimal_frame_size/`, `io_utils.py` | Optimal detector window size analysis |

External dependencies: `numpy`, `scipy`, `matplotlib`, `numba`, `seaborn`, `pandas`, `phise`, `phobos`, `pltedit`, `vfscitools`.
