# paper2415
---
## Environment setting

```bash
conda env create -f environment.yml
```
---
## Run test-time adaptation
Source model, CIFAR10-to-10C example:
```bash
python test_time.py --cfg cfgs/cifar10_c/source.yaml
```
