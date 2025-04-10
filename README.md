# 🌀 Google Colab Blender Renderer

A simplified Google Colab notebook to automate Blender rendering (single frame or animation) using the latest **Blender 4.4** with **GPU acceleration**, **ACES color management**, and **Google Drive integration**.

---

## 🚀 Features

- ✅ Installs **Blender 4.4** in the Colab environment  
- ✅ Automatically sets up **GPU rendering** (CUDA, OptiX, OpenCL)  
- ✅ Installs **required Linux libraries** for Blender to work  
- ✅ Optionally mounts your **Google Drive** for easy `.blend` file access  
- ✅ Adds **ACES OCIO config** for better color management  
- ✅ Supports **animation rendering** or **single frame rendering**

---

## 📁 Folder Structure

- `/content/blender/` – Blender install location  
- `/content/drive/` – Your Google Drive files  
- `setgpu.py` – Script to force GPU usage in Cycles

---

## 🛠 How to Use

1. Open the notebook in Google Colab  
2. Run all cells in order  
3. Upload your `.blend` file to Google Drive  
4. Update the render paths (frame or animation) as needed  
5. Sit back and let Colab do the rendering! ☁️

---

## ⚠️ Requirements

- Google Colab with GPU runtime enabled (`Runtime > Change runtime type > GPU`)
- `.blend` file inside Google Drive

---

## 🙏 Credits

Original notebook by [@ynshung](https://github.com/ynshung)  
🔗 [Blender Colab Notebook](https://colab.research.google.com/github/ynshung/blender-colab/blob/master/blender_render.ipynb)

This version is a simplified fork to make the workflow even easier.  


> Just helping my girlfriend study.

> Special thanks to the guys at Escola Revolution for the 3D course with Blender

---

## 📎 License

This notebook is provided under the [MIT License](LICENSE).
