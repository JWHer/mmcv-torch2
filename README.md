# MMCV v1.4.0 for pytorch

This version v1.4.0 MMCV is specifically tailored for integration with torch>=2.0

## Compatibility
MMCV v1.4.0 is compatible with PyTorch versions greater than 2.0.
It has been rigorously tested on Linux systems with PyTorch v2.1.2 and CUDA v12.0.

## Installation

mmcv
```bash
pip install -e . -v
```

mmcv-full
```bash
MMCV_WITH_OPS=1 FORCE_CUDA=1 pip install -e . -v
```

For more detailed installation guide, check out the
[mmcv v1.4.0](https://github.com/open-mmlab/mmcv/blob/v1.4.0/README.md).
