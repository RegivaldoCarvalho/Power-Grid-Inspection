# Power-Grid-Inspection
A novel approach to automate the inspection of power lines.

## Requirements

Install the programs above:

### Python 3.6.6 - https://www.python.org/downloads/release/python-366/

### TensorFlow - https://www.tensorflow.org/install/ 

To install the CPU-only version of TensorFlow, enter the following command:
```bash
pip3 install --upgrade tensorflow
```
To install the GPU version of TensorFlow you need a GPU card with CUDA Compute Capability 3.0 or higher.
If you have it, install the CUDA® Toolkit 9.0 and cuDNN v7.0 for CUDA 9.0 
- https://docs.nvidia.com/cuda/cuda-installation-guide-microsoft-windows/

- https://developer.nvidia.com/cudnn

- https://docs.nvidia.com/deeplearning/sdk/cudnn-install/index.html#ixzz56wCXCTwH

Copy cuDNN files to directories below:

-`cudnn64_7.dll (cuda\bin\cudnn64_5.dll) into C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0\bin\;`

-`cuda\include\cudnn.h to C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0\include\;`

-`and cuda\lib\x64\cudnn.lib to C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0\lib\x64\`

WHERE C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0 is the install PATH for the CUDA toolkit.

Then add this diretory to environment variable on windows:
C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0\bin\

```bash
control sysdm.cpl
```

After that use the following command to intall TensorFlow for GPU

```bash
pip3 install --upgrade tensorflow-gpu
```

### Keras - https://keras.io/#installation

Enter the following command:

```bash
pip3 install --upgrade keras
```






## Test
