# gammapy-benchmarks

Performance benchmarks for Gammapy.

Note that we have validation separately, see [here](../README.md).

## Analyses

We have the following typical science cases tested:

- [maps_3d.py](maps_3d.py) - Stacked data preparation for the 3D case
- [analysis_3d.py](analysis_3d.py) - Stacked data fitting in 3D
- [spectrum_1d.py](spectrum_1d.py) - 1D stacked spectral extraction and fitting
- [spectrum_1d_joint.py](spectrum_1d_joint.py) - 3D stacked spectral extraction and fitting
- [lightcurve_1d.py](lightcurve_1d.py) - Light-curve extraction in 1D
- [lightcurve_3d.py](lightcurve_3d.py) - Light-curve extraction in 3D (tbd)
- [joint_maps_3d.py](joint_maps_3d.py) - Data preparation for the 3D case for joint analysis (tbd)
- [joint_analysis_3d.py](joint_analysis_3d.py) - Joint Data fit in 3D (tbd)

## Execution

To run a specific benchmark use [make.py](make.py).

```bash
python make.py run-benchmark benchmark-name
```

To run all benchmarks:
```bash
python make.py run-benchmark all
```