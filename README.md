# Neural Network on ARM-Based Dev Boards
Collection of various setups for installing Neural Network frameworks on arm based dev-boards

# Usage
To install the whl files, clone the repository - 
```
git clone https://github.com/amrit-das/neural_network_on_arm64.git
```
To install PyTorch, run -
```
cd neural_network_on_arm64
pip3 install pytorch.whl
```
To install Tensorflow, wun - 
```
curl -L https://github.com/lherman-cs/tensorflow-aarch64/releases/download/r1.4/tensorflow-1.4.0rc0-cp35-cp35m-linux_aarch64.whl > /tmp/tensorflow-1.4.0rc0-cp35-cp35m-linux_aarch64.whl
python3 -m pip install /tmp/tensorflow-1.4.0rc0-cp35-cp35m-linux_aarch64.whl
```
## References:
The repository consists of whl files from various opensource projects. I do not own the copyrights of those files. The links from where I have collected the files could be found below. 
Links
  - PyTorch - https://github.com/huzz/Pytorch-aarch64
  - Tensorflow - https://github.com/lherman-cs/tensorflow-aarch64
