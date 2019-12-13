# Kangaroo
Image detection by finetuning a pretrained CNN

### Clone and install the Mask R-CNN
```bash
git clone https://github.com/matterport/Mask_RCNN.git
cd Mask_RCNN
python setup.py install
```

### Install dataset
```bash
git clone https://github.com/experiencor/kangaroo.git
```

### Dependencies
Make sure both Tensorflow and Keras are in the versions bellow. Otherwise, uninstall and install the correct ones.
* To run on CPU
```bash
pip install tensorflow==1.13.1
pip install keras==2.2.5
```
* To run on GPU
```bash
pip install tensorflow-gpu==1.14.0
pip install keras==2.2.5
```
