installing anaconda on NCI
https://www.anaconda.com/tensorflow-in-anaconda/

note there are environments for CPU and GPU - only installed CPU initially.

### Setup

1. Add conda to path

1. Setup conda tensor flow environment (not use the cpu or gpu environment): `conda create -n tensorflow tensorflow-gpu`

1. Activate environment: `conda activate tensorflow`

1. `conda install -c conda-forge jupyterlab ipywidgets nodejs jupyter numpy scipy Pillow cython matplotlib scikit-image opencv h5py IPython pycocotools`

1. `pip install imgaug`

1. `git clone https://github.com/joshua-wx/Mask_RCNN`

1. `python setup.py install`
