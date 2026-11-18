# HDQS 3D output generation report

Source notebook: `C:\Users\geeth\OneDrive\Desktop\sia_examples.ipynb` (read only).
Generation: original notebook code cells executed unchanged with `sia-script` 1.5.7 under Python 3.14. All outputs were written into this folder.
Installation: `python -m pip install sia-script` (Google Colab is not required; run from a writable working directory).
Verification: GLB header/version/length checked; OBJ references its generated MTL; STL binary triangle counts and lengths agree; all 3MF archives pass ZIP integrity checks and model XML parses; HTML outputs exist and are nonempty.

| Example | Generated filename | Format | Status |
|---:|---|---|---|
| 213 | `scene.glb` | GLB | SUCCESS |
| 214 | `bloch.obj` | OBJ | SUCCESS |
| 214 | `bloch.mtl` | MTL | SUCCESS |
| 215 | `bell.3mf` | 3MF | SUCCESS |
| 216 | `qubit.stl` | STL | SUCCESS |
| 217 | `terrain.3mf` | 3MF | SUCCESS |
| 218 | `quick.stl` | STL | SUCCESS |
| 219 | `report_demo.3mf` | 3MF | SUCCESS |
| 37 | `phasor.html` | HTML | SUCCESS |
| 40 | `my_qubit.html` | HTML | SUCCESS |
| 40 | `my_bell.html` | HTML | SUCCESS |
| 41 | `square_wave.html` | HTML | SUCCESS |

No example failed. The OBJ material dependency `bloch.mtl` is included. The ZIP contains all 12 generated 3D output files listed above; this report is separate.
