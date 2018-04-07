# tensorflow-api
git clone https://github.com/tensorflow/models.git

I. Installation using anaconda, python 3.6
link: https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md

conda install tensorflow-gpu
sudo apt-get install protobuf-compiler python-pil python-lxml python-tk
conda install Cython
conda install matplotlib

# From tensorflow/models/research/
protoc object_detection/protos/*.proto --python_out=.
export PYTHONPATH=$PYTHONPATH:`pwd`:`pwd`/slim
#test
python object_detection/builders/model_builder_test.py

II. Creating own object detection
link: https://pythonprogramming.net/introduction-use-tensorflow-object-detection-api-tutorial/
