# Video-Data-Processing-with-Python-and-OpenCV

This project focuses on the automated processing, annotation, and visualization of video data using Python and OpenCV. It demonstrates how pre-labeled object detection data can be overlaid on raw video footage to generate an annotated output video, helping developers and researchers better understand and validate visual datasets.

The system reads a video frame-by-frame, applies bounding boxes and category labels (e.g., car, pedestrian, cyclist) using structured CSV annotation files, and outputs both visual previews and a fully annotated video. Designed for clarity and extensibility, this project is ideal for use in computer vision pipelines, dataset exploration, or as a foundation for AI/ML model validation.

## Key Objectives

- Read and manipulate video streams with OpenCV  
- Integrate object detection labels (bounding boxes + categories)  
- Annotate frames with color-coded bounding boxes and text overlays  
- Export the final annotated video in MP4 format  
- Visualize frame samples interactively within Jupyter notebooks  

## ✅ Features

- Annotates video frames with category-specific bounding boxes  
- Visual distinction using color-coded overlays  
- Modular function design for annotation, video generation, and visualization  
- Optional: Play annotated video directly inside Jupyter Notebook  

## 📦 Input & Output

- **Input:** A raw driving scene video (`.mp4`) and object detection labels in CSV format  
- **Output:** A new annotated video showing each object class with bounding boxes and text labels  

## 🚀 Highlights

- **Category-specific colors** make visual distinction easy  
- **Frame-by-frame annotation** allows high-resolution analysis  
- **Jupyter integration** enables easy demonstration and validation  
- **Simple architecture** — no deep learning or heavy models used; ready for fast prototyping or integration with future object detection systems  

## Folder Structures

![image](https://github.com/user-attachments/assets/ea2c5d90-7915-492e-bdb5-d960d7700a2c)

## Technologies Used

- Python  
- OpenCV  
- Pandas  
- Matplotlib  
- Jupyter Notebook  
- TQDM for progress tracking  

## 🔍 Future Enhancements

- Integration with YOLO or Faster R-CNN for real-time object detection  
- Export annotations in COCO/YOLO format  
- Real-time webcam stream annotation  

---

> Built with a focus on clarity, modularity, and educational value.
