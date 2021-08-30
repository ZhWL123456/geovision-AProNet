# AProNet: Detecting Objects with Precise Orientation from Aerial Images
This is the repository of paper "AProNet: Detecting Objects with Precise Orientation from Aerial Images"
## Installation
    Python: 3.6.7  
    PyTorch: 1.2.0.dev20190704  
    CUDA: 9.0  
    CUDNN: 7  
compile the DOTA-devikit dependency:
    sudo apt-get install swig
    cd DOTA_devkit/polyiou
    swig -c++ -python csrc/polyiou.i
    python setup.py build_ext --inplace

## Run

