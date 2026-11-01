<div align="center">

<h1>🎯 Object Detection using Single Shot Detector</h1>
<h3><code>Inspecting detections in images</code></h3>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=900&lines=Inspecting%20detections%20in%20images;Learn+it.+Build+it.+Explain+it." alt="Inspecting detections in images" />

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

[Open this project](https://github.com/somilsin/Computer-Vision/tree/main/Object-Detection-using-SSD) · [My GitHub](https://github.com/somilsin) · [Main Portfolio](https://somilsin.github.io/Artificial-Intelligence/portfolio/)

</div>

<br>

I use this notebook to explore object detection with a Single Shot Detector and COCO class labels. It keeps the example images and detection outputs alongside the model setup.

## 📂 Files

| File or folder | Purpose |
| --- | --- |
| [Notebook](obj_det_jupyt.ipynb) | Image loading and detection examples with saved outputs. |
| [Text graph helper](tf_text_graph_ssd.py) | Conversion helper for the detector graph. |
| [Class labels](coco_class_labels.txt) | The COCO label names used for predictions. |
| [Images](images/) | Example images for the notebook. |
| [Models](models/) | The tracked graph configuration and model reference. |

## ⚙️ Try it

Open [obj_det_jupyt.ipynb](obj_det_jupyt.ipynb) from this folder so the relative image paths work. The notebook needs the frozen inference graph referenced in its model setup.

The displayed confidence scores describe individual predictions. They aren't an accuracy measurement for the detector.
