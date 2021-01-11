### Instructions for Length-Controllable AoANet

1. Clone [original AoANet](https://github.com/husthuaan/AoANet/tree/94ffe176c3777bc54e53e9dd7b305b4046d91a70).
2. Put `AttModel.py` and `CaptionModel.py` in `/Path/to/AoANet/models/`, put `opts.py` in `/Path/to/AoANet/`.
3. Follow the instructions in original AoANet to train/inference/evaluate your model.
4. For evaluation, add `--eval_lvl N` to the inference script to generate captions on level `N'.
