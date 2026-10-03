<div align="center">

# 🎯 Object Tracking with Boundary Detection

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge)

**By [Somil Singh](https://github.com/somilsin)**

</div>

[← Computer Vision](../README.md)

I work with You Only Look Once version 4 to detect objects in images and video. I focus on targets near frame boundaries and inspect object counts and detailed detection information.

## ⚙️ Run from this project folder

```bash
git clone https://github.com/somilsin/Computer-Vision.git
cd Computer-Vision/Object-Tracking-with-Boundary-edge-detection-using-yolov4
conda env create -f conda-cpu.yml
conda activate yolov4-cpu
python detect.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --images ./data/images/kite.jpg
python detect_video.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --video ./data/video/video.mp4 --output ./detections/results.avi
```

I use `conda-gpu.yml` for the original GPU environment. These files describe the project's older TensorFlow environment so I check compatibility before using a newer runtime. I also check that the complete trained model is present before inference.

## 🔎 Other examples

```bash
python detect_video.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --video 0 --output ./detections/results.avi
python detect.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --images ./data/images/dog.jpg --count
python detect.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --images ./data/images/dog.jpg --info
```

## 📝 My notes

I keep the example images and video with the code so I can compare how the model behaves across inputs. Targets near the edge of a frame and partially hidden objects are useful cases to inspect. I keep the original license in [LICENSE](LICENSE).
