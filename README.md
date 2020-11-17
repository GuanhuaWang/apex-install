# apex-install

## AWS Environment

AMI: Deep Learning AMI (Ubuntu 18.04) Version 36.0 

PyTorch 1.7, Python3.7, CUDA 11.0


## Apex install

``` 
pip uninstall apex
git clone https://www.github.com/nvidia/apex
cd apex
pip install -v --no-cache-dir --global-option="--cpp_ext" --global-option="--cuda_ext" ./
```
