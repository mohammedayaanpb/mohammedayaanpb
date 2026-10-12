# Ayaan Mohammed

I'm a master's student in robotics at the University of Minnesota and a graduate researcher in the [Minnesota Interactive Robotics and Vision (IRV) Lab](https://irvlab.cs.umn.edu/), where I work on underwater image restoration for downstream robotic tasks such as object detection and SLAM.

Before UMN, I was a graduate engineer trainee at TATA Advanced Systems doing quality engineering for Collins Aerospace projects. As an undergraduate I worked on [ghost net detection and underwater monocular depth estimation](https://link.springer.com/chapter/10.1007/978-3-031-93703-3_4). I have a B.Tech in Mechanical Engineering from National Institute of Technology Puducherry, India.

I'm interested in multi-modal perception for robots in challenging environments.

[Email](mailto:mhd.ayaan12@gmail.com) · [LinkedIn](https://www.linkedin.com/in/ayaan12/) · [Google Scholar](https://scholar.google.com/citations?user=C64-qB0AAAAJ&hl=en)

## Selected research

### Underwater image restoration for robot perception (ongoing)

My master's thesis at the IRV Lab: restoring underwater images so that downstream robotic tasks like object detection and SLAM stay robust in low-visibility water.

### Ghost net detection and monocular depth estimation

At NIT Puducherry, I designed a YOLOv5 + MiDaS pipeline for real-time detection and depth estimation of ghost nets (abandoned fishing gear). A ResNet50 fine-tuned with transfer learning reached 91.1% accuracy on a custom ghost net dataset. I benchmarked three depth estimation models, found MiDaS best suited to underwater environments, and incorporated wavelength-dependent attenuation to refine underwater monocular depth estimates.

> M. Ayaan and R. N. Raj. [Detection and Monocular Depth Estimation of Ghost Nets](https://doi.org/10.1007/978-3-031-93703-3_4). *International Conference on Computer Vision and Image Processing (CVIP 2024)*, Springer, pp. 45–58.

### Underwater photogrammetry

At CSIR-National Institute of Oceanography, Goa, I generated 3D reconstructions of underwater artifacts with Structure-from-Motion and multi-view stereo pipelines, improved point cloud generation with colour correction, and proposed a guideline for data acquisition in underwater photogrammetry.

## Projects

| Project | Work |
| --- | --- |
| [Image enhancement for underwater ORB-SLAM3](https://github.com/mohammedayaanpb/ORB_SLAM3_AQUALOC) | Evaluated image enhancement techniques for making ORB-SLAM3 more robust in low-visibility underwater scenes, using the AQUALOC dataset. FUnIE-GAN enhancement improved keyframe tracking by 24.7%. |
| [Marine mammal vocalization classification](https://github.com/mohammedayaanpb/Spectral-Graph-Methods-for-Marine-Mammal-Vocalization-Classification) | Catalogued 1,697 recordings across 32 species and extracted MFCCs and mel-spectrograms. Built spectral graph classifiers for 4 families and 17 dolphin species, with semi-supervised learning via k-NN graphs and harmonic label propagation. 72.47% family-classification accuracy, close to ResNet-18's 73.42%. |
| [Class-aware seam carving with multi-operator retargeting](https://github.com/sri299792458/cv5561-f25-team-asa) | Team course project. I integrated Depth Anything 3 to preserve 3D boundaries during class-aware resizing, and designed five composition-specific energy functions that combine classical computer vision with saliency maps to guide seam carving. |

## Skills

- **Languages:** Python, C/C++, MATLAB
- **Frameworks:** TensorFlow, PyTorch, OpenCV, Open3D, ROS/ROS 2, Gazebo, HoloOcean
- **Robotics:** State estimation (EKF, UKF), multi-sensor fusion, visual SLAM, robotics perception
- **CAD and 3D:** AutoCAD, CATIA, Fusion 360, Agisoft Metashape, Meshroom, MeshLab, VisualSfM, Blender
