<div align="center">

# 👁️ Object Detection using Single Shot Detector

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge)

**By [Somil Singh](https://github.com/somilsin)**

</div>

[← Computer Vision](../README.md)

I use this project to explore object detection with a Single Shot Detector and COCO class labels. The notebook displays image examples and the Python helper builds a TensorFlow text graph for the detector.

## 📂 What I keep here

| File or folder | Purpose |
| --- | --- |
| [Notebook](obj_det_jupyt.ipynb) | Image loading and detection examples with saved outputs. |
| [Text graph helper](tf_text_graph_ssd.py) | Conversion helper for the detector graph. |
| [Class labels](coco_class_labels.txt) | The COCO label names used for predictions. |
| [Images](images/) | Example images for the notebook. |
| [Models](models/) | The tracked graph configuration and model reference. |

## 📝 My notes

I open the notebook from this project folder so its relative image paths resolve correctly. A model confidence score describes a prediction. I would need an independent labelled evaluation to describe the detector's accuracy.

The detector also needs the frozen inference graph referenced by the notebook. I check that the complete model is available before running it on new images.
