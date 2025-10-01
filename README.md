# Indoor Localization (ENS491/492)

Swin Transformer–based **camera pose regression** on 7-Scenes (3D translation + quaternion).  
Includes MiDaS depth checks and YOLO experiments used in the reports.

## What's here
- **Code/Notebooks:** `notebooks/` (e.g., `swin.ipynb`, `posemat.ipynb`, `yolo.ipynb`, MiDaS tests)
- **Model impl:** `swin_functions_and_classes.py` (next to the notebook or under `src/models/`)
- **Reports/Slides:** `docs/reports/`, `docs/slides/` (PDFs)
- **Results (txt):** `docs/results/` (`train_loss_epoch_500.txt`, `test_loss_*.txt`)
- **Env:** `requirements.txt`
- **Data notes:** `data/README.md` (how to get 7-Scenes)

## Quickstart

1) Python deps
pip install -r requirements.txt

2) Data (not included)
   
3) Download 7-Scenes; keep as zip at: ./data/7scenes.zip
  See src/data/README.md for details.

## Open and run:

src/train/swin.ipynb – training/eval for Swin pose model

notebooks/midas*.ipynb – MiDaS depth sanity checks

notebooks/yolo.ipynb – object detection experiments

## Results

Single-number summaries are in:

docs/results/train_loss_epoch_500.txt

docs/results/test_loss_epoch_500.txt

docs/results/test_loss_coor_epoch_500.txt

docs/results/test_loss_orien_epoch_500.txt

## Data

We do not commit the dataset. See data/README.md.

## License

Code: MIT
