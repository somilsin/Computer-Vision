<div align="center">

<h1>📹 Object Tracking with Boundary Detection</h1>
<h3><code>Following objects with You Only Look Once version 4</code></h3>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=900&lines=Following%20objects%20with%20You%20Only%20Look%20Once%20version%204;Learn+it.+Build+it.+Explain+it." alt="Following objects with You Only Look Once version 4" />

<p>
<img src="https://img.shields.io/badge/Computer%20Vision-6E40C9?style=for-the-badge" alt="Computer Vision" />
<img src="https://img.shields.io/badge/Maintained%20by%20Somil%20Singh-58A6FF?style=for-the-badge&logo=github&logoColor=white" alt="Maintained by Somil Singh" />

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge" alt="Python" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge" alt="TensorFlow" />
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/somil-singh)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:somils@andrew.cmu.edu)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Skywalkerlyzv)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@thesomilsinghofficial)
[![Substack](https://img.shields.io/badge/Substack-FF6719?style=for-the-badge&logo=substack&logoColor=white)](https://thesomilsingh.substack.com/)

[Open this project](https://github.com/somilsin/Computer-Vision/tree/main/Object-Tracking-with-Boundary-edge-detection-using-yolov4) · [My GitHub](https://github.com/somilsin) · [Main Portfolio](https://somilsin.github.io/Artificial-Intelligence/portfolio/)

</div>

<br>

<div align="center">

📄 **Published in IJISRT · August 2023**

### [Object Detection Classification and Tracking of Everyday Common Objects](https://www.ijisrt.com/object-detection-classification-and-tracking-of-everyday-common-objects)

Shiwansh Bhargav · Somil Singh

*International Journal of Innovative Science and Research Technology · Vol. 8, Issue 8 · pp. 2188 to 2192 · ISSN 2456-2165*

[![Journal](https://img.shields.io/badge/IJISRT-Aug%202023-1f6feb)](https://www.ijisrt.com/object-detection-classification-and-tracking-of-everyday-common-objects) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8330641.svg)](https://doi.org/10.5281/zenodo.8330641) [![Paper PDF](https://img.shields.io/badge/Paper-PDF-b31b1b)](https://www.ijisrt.com/assets/upload/files/IJISRT23AUG1545.pdf)

</div>

---

I worked on object detection and tracking with YOLOv4 for images and video. The examples include object counts, detection details and cases where a target sits near the edge of a frame.

## ⚙️ Run it

```bash
git clone https://github.com/somilsin/Computer-Vision.git
cd Computer-Vision/Object-Tracking-with-Boundary-edge-detection-using-yolov4
conda env create -f conda-cpu.yml
conda activate yolov4-cpu
python detect.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --images ./data/images/kite.jpg
python detect_video.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --video ./data/video/video.mp4 --output ./detections/results.avi
```

Use `conda-gpu.yml` for the original GPU environment. These environment files use an older TensorFlow version and the trained weights need to be present before inference.

## 🔎 More examples

```bash
python detect_video.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --video 0 --output ./detections/results.avi
python detect.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --images ./data/images/dog.jpg --count
python detect.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --images ./data/images/dog.jpg --info
```

## 📚 Paper and source

The paper and author details are linked above. The original [license](LICENSE) is included with the code.
