# **Building Segmentation with Segment Anything Model (SAM)**

**An innovative geospatial project leveraging Meta's Segment Anything Model (SAM) to identify and segment buildings in satellite images.**  
This project combines advanced zero-shot segmentation with geospatial tools for precise and interactive analysis.

---

## 🚀 **Overview**

This project applies **SAM (Segment Anything Model)** to segment buildings in high-resolution satellite imagery. By integrating **Leafmap** and **Rasters**, it enables:
- Automated building identification.
- Customizable bounding box selection.
- Interactive map visualization of segmentation results.

**Use Cases**:
- Urban development analysis.
- Disaster recovery planning.
- Environmental monitoring.

---

## ✨ **Features**

- **Zero-shot Segmentation**: No need for task-specific training.
- **Customizable ROIs**: Define regions of interest interactively or use default bounding boxes.
- **Interactive Maps**: Visualize segmentation on geospatial maps.
- **Exportable Results**: Save masks for downstream applications.

---


## 📖 **Usage**

### 1. **Load Your Satellite Image**
Add your satellite image (GeoTIFF, JPEG, etc.) to the project folder.

### 2. **Run the Segmentation**
Here's an example to segment buildings using a custom ROI:

### 3. **Visualize Results**
Overlay results on interactive maps with **Leafmap**.

---

## 🗂️ **Project Structure**

```
your-repo-name/
│
├── data/                # Input satellite images
├── outputs/             # Generated segmentation masks
├── notebooks/           # Jupyter notebooks for experiments
├── scripts/             # Python scripts
├── requirements.txt     # Dependencies
├── README.md            # Documentation
└── main.py              # Main executable script
```

---

## 🖼️ **Results**

### **Input Satellite Image**
![image](https://github.com/user-attachments/assets/4c8491e3-e369-4c71-a080-49ccd83167a2)



### **Segmented Buildings**
![image](https://github.com/user-attachments/assets/515923be-c9c7-4973-99bb-6a5de8a070c0)


