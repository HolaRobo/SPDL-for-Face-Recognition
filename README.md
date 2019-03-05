# SPDL-for-Face-Recognition
Self-paced Robust Deep Face Recognition with Label Noise

## Requirements
1. [Caffe](http://caffe.berkeleyvision.org/installation.html)
2. [MTCNN](https://github.com/kpzhang93/MTCNN_face_detection_alignment)

## Dataset
#### Training Dataset

`CASIA-WebFace`

[`MS-Celeb-1M`](https://www.microsoft.com/en-us/research/project/ms-celeb-1m-challenge-recognizing-one-million-celebrities-real-world/)

#### Testing Dataset

[`LFW`](http://vis-www.cs.umass.edu/lfw)

[`YTF`](https://www.cs.tau.ac.il/~wolf/ytfaces)

[`MegaFace`](http://megaface.cs.washington.edu)

## Code

Please put the `include/softmax_selfpace_loss_layer.hpp` into the `YOUR-CAFFE-HOME/include/caffe/layers/`,  
put the `src/softmax_selfpace_loss_layer.cpp` and `src/softmax_selfpace_loss_layer.cu` into the `YOUR-CAFFE-HOME/src/caffe/layers/`.
Then modify your `caffe.proto`.

## Model 
Waiting

## Citaion
Waiting

## Contact
[Wenya Ma](wyma@tju.edu.cn)

## License
SPDL is released under the MIT License
