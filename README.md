# Real-Time Augmented Reality with Feature Matching and Planar Mapping

This project showcases a full-stack, real-time Augmented Reality (AR) application built using classical computer vision techniques. The system performs robust feature detection and matching to accurately overlay virtual graphics on live video streams, supporting both planar mapping and panoramic stitching.

## 📌 Project Highlights

- ✅ Built an end-to-end AR pipeline using OpenCV and Python
- ✅ Detected FAST keypoints and computed BRIEF descriptors for efficient feature representation
- ✅ Matched features using Hamming distance to track consistent points between frames
- ✅ Overlaid virtual graphics on real-time video with low-latency processing

## 🧠 Geometric Vision & Robust Mapping

- Implemented **Direct Linear Transform (DLT)** homography estimation
- Applied **normalization** and **RANSAC** to ensure robust planar alignment
- Achieved sub-pixel accuracy across challenging image pairs

## ⚙️ Performance Optimization

- Optimized image-warping routines to sustain **30+ FPS** in live settings
- Added an optional **panorama-stitching module** to blend multiple perspectives into a seamless view

## 📚 Technical Domains

- Feature Detection (FAST)
- Binary Descriptors (BRIEF)
- Feature Matching (Hamming distance)
- Homography & RANSAC
- Real-Time Image Warping
- Panorama Stitching
- GPU-Accelerated Computer Vision
- Linear Algebra (SVD, eigen decomposition)

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- (Optional) CUDA or OpenCV GPU modules for acceleration

## Acknowledgements

I would like to thank my Computer Vision professor, Srinivasa Narasimhan, for his guidance regarding this project. 

