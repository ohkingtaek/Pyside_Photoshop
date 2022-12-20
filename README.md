# Pyside_Photoshop

### Projects : PySide PhotoShop Program (Computer Vision I Assignments)
- Tech Stack
  - [Python](https://www.python.org)
  - [PySide](https://wiki.qt.io/PySide/ko)
  - [Pytorch](https://pytorch.org/)
  - [EfficientNet](https://arxiv.org/abs/1905.11946)
  - [YOLOv7](https://arxiv.org/abs/2207.02696)
  - [Detectron2](https://github.com/facebookresearch/detectron2)

![image](https://user-images.githubusercontent.com/49676680/208640544-e30e3eeb-becc-4cc7-8997-2103091594c8.png)

### Installation & Settings
```
python 3.8.13
pytorch 1.11.0
cuda 11.3
```

```
git clone https://github.com/ohkingtaek/Pyside_Photoshop.git
cd Pyside_photoshop
git clone https://github.com/facebookresearch/detectron2.git
conda create -n photoshop python=3.8 -y
conda activate photoshop
pip install -r requirements.txt
```
Checkpoint Download (Object Detection)
- [yolov7.pt](https://drive.google.com/file/d/1GeUhf_MHBBcEPyZf9Cg95kR1rMpcqkIA/view)
- [trace_model.pt](https://drive.google.com/file/d/1lEgiWru9c53Rtin3NbeBRJ0Nw9o3NY4U/view)

### Function Implementation
- Menu
  + PhotoShop(Image Processing)
    * Image Open
    * Refresh
    * Symmetry
    * Normalization
    * Sharpening
    * Edge Detection
    * Rotate
    * Binarization
    * Mosaic
    * Face Detection
    * Pose Detection
    * Warping (After preprocess, click Result)
    * Enlargement (After preprocess, click Result)
    * Result
  + Image Classification (Efficientnet-B0)
  + Object detection (YOLOv7)
  + Semantic Segmentation (Mask R-CNN Resnet 50 FPN)

