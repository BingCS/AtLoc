[![License CC BY-NC-SA 4.0](https://img.shields.io/badge/license-CC4.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)
![Python 2.7](https://img.shields.io/badge/python-2.7-green.svg)
# AtLoc-Attention-Guided-Camera-Localization

## License
Licensed under the CC BY-NC-SA 4.0 license, see [LICENSE](LICENSE.md).

## Documentation 

This is the PyTorch implementation of our AAAI 2020 paper:

[AtLoc: Attention Guided Camera Localization](https://arxiv.org/abs/1909.03557) - AAAI 2020 (Oral).

[Bing Wang](https://www.cs.ox.ac.uk/people/bing.wang/), [Changhao Chen](http://www.cs.ox.ac.uk/people/changhao.chen/website/), [Chris Xiaoxuan Lu](https://christopherlu.github.io/), [Peijun Zhao](https://www.cs.ox.ac.uk/people/peijun.zhao/), [Niki Trigoni](https://www.cs.ox.ac.uk/people/niki.trigoni/), and [Andrew Markham](https://www.cs.ox.ac.uk/people/andrew.markham/)

## Setup

AtLoc uses a Conda environment that makes it easy to install all dependencies.

1. Install [miniconda](https://docs.conda.io/en/latest/miniconda.html) with Python 2.7.

2. Create the `AtLoc` Conda environment: `conda env create -f environment.yml`.

3. Activate the environment: `conda activate py27pt04`.

4. Note that our code has been tested with PyTorch v0.4.1 (the environment.yml file should take care of installing the appropriate version).

## Citation
If you find this code useful for your research, please cite our paper

```
@article{wang2019atloc,
  title={AtLoc: Attention Guided Camera Localization},
  author={Wang, Bing and Chen, Changhao and Lu, Chris Xiaoxuan and Zhao, Peijun and Trigoni, Niki and Markham, Andrew},
  journal={arXiv preprint arXiv:1909.03557},
  year={2019}
}
```
## Acknowledgements
Our code partially builds on [MapNet](https://github.com/NVlabs/geomapnet) and [PoseLstm](https://github.com/hazirbas/poselstm-pytorch)
