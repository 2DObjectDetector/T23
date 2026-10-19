# T2.3 One-class Car detector

Trains the best configuration from T2.2 on `kitti3k_car_only` (Car annotations only) and compares its test-set Car AP50-95 with the three-class model. Part of [2D Object Detector](https://github.com/2DObjectDetector).

**Result:** One-class Car AP50 = 0.906 and AP50-95 = 0.663, against 0.902 and 0.665 for the three-class model. The difference is within noise, so specialising to one class made no meaningful difference for this dataset.

**Run:** Outputs are saved in the notebook, so the results are visible without running it. To rerun: use a Colab GPU runtime and add the `kitti3k_yolo` dataset (not included) and update its path.
