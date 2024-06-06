# chgnet-KD

This project is a fork of the [original repository](https://github.com/CederGroupHub/chgnet). Many thanks to the original project for their work.

## Changes

- Knowledge distillation using soft target has been added.
- The soft targets are the energies and forces calculated using the same structure data that was used for computing the hard targets.
- For that, data/dataset.py and trainer/trainer.py have been edited.

