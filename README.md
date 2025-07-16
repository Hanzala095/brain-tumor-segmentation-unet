![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

# 🧠 Brain Tumor Segmentation using U-Net

This project implements a basic brain tumor segmentation pipeline using a custom-built U-Net model.  
Due to dataset and model access issues (BRATS, MedSAM-2), synthetic MRI slices were generated to simulate the segmentation task.

---

## 📌 Project Highlights

- ✅ Fully built in **Google Colab**
- ✅ Custom **U-Net model** using PyTorch
- ✅ Generated synthetic MRI and tumor masks (256x256)
- ✅ Trained and evaluated using **Dice score**
- ✅ Included **Colab Notebook + PDF Report**
- ✅ Lightweight and easy to reproduce

---

## 🗂 Files in This Repository

| File | Description |
|------|-------------|
| `tumor_segmentation_unet.ipynb` | Complete Colab notebook with training, inference, and evaluation |
| `Brain_Tumor_Segmentation_Report_Hanzala.docx` | Internship report in DOCX format |
| `LICENSE` | MIT License file |
| `README.md` | This project overview file |

---

## 📊 Dice Score

Due to limited training on a single synthetic image for demonstration purposes:
Dice Score ≈ 0.0000

> Note: This can be improved significantly by training on multiple real MRI slices (e.g. BRATS dataset) and increasing training epochs.

## 🔧 Tools & Libraries

- Python 3.10  
- Google Colab  
- PyTorch  
- OpenCV  
- NumPy  
- Matplotlib  

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.  
You are free to reuse, modify, and share with attribution.

## 👨‍💻 Author

Muhammad Hanzala Khan  
ARCH Technologies – Machine Learning Internship  

> 🔁 This project demonstrates the full pipeline of medical image segmentation from scratch, even without access to official datasets or pretrained models. A great showcase of adaptability and learning!


