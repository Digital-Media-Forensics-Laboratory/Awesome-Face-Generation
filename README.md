# 🎬 Awesome Face Generation

本仓库系统整理了 **人脸生成与伪造（DeepFake）相关的代表性方法**，涵盖以下三大方向：

- 🧩 **FaceSwap（人脸替换）**：将目标人物的人脸特征替换到另一人物的视频或图像上；
- 🎭 **Face Reenactment（人脸重演）**：根据参考视频或动作驱动源视频的人脸表情与姿态；
- 🗣️ **Talking Face（语音驱动说话人脸）**：通过语音输入生成同步的说话人脸图像或视频。

本项目旨在建立一个统一的实验与复现平台，为研究者和开发者提供高质量的参考实现与对比环境。

---

## 📁 仓库结构
```bash
Awesome-FaceGeneration/
│
├── FaceSwap/                      # 人脸替换方法
│   ├── Celeb-DF_Improved/
│   ├── SimSwap/
│   ├── InSwapper/
│   ├── HiFiFace/
│   ├── GHOST/
│   ├── UniFace/
│   ├── MobileFaceSwap/
│   ├── BlendFace/
│   ├── FaceFusion/
│   └── README.md
│
├── FaceReenactment/               # 人脸重演方法
│   ├── DaGAN/
│   ├── TPSMM/
│   ├── MCNet/
│   ├── HyperReenact/
│   ├── LIA/
│   ├── LivePortrait/
│   └── README.md
│
├── TalkingFace/                   # 语音驱动说话人脸方法
│   ├── SadTalker/
│   ├── IP-LAP/
│   ├── AniTalker/
│   ├── EDTalk/
│   ├── Real3D-Portrait/
│   ├── EchoMimic/
│   ├── FLOAT/
│   └── README.md
│
├── utils/                         # 通用工具与预处理脚本
│   ├── face_crop.py
│   ├── video2frames.py
│   ├── merge_results.py
│   ├── evaluate_metrics.py
│   └── visualization.py
```
---
## 📚 模块划分与方法概览

---

### 🧩 FaceSwap（人脸替换）

| 方法名称 | 年份 | GitHub 原地址 |
|-----------|------|----------------|
| Celeb-DF Improved | — | — |
| [SimSwap](https://github.com/neuralchen/SimSwap) | 2020 | https://github.com/neuralchen/SimSwap |
| InSwapper | — | — |
| HiFiFace | — | — |
| GHOST | — | — |
| UniFace | — | — |
| MobileFaceSwap | — | — |
| BlendFace | — | — |
| FaceFusion | — | — |

---

### 🎭 Face Reenactment（人脸重演）

| 方法名称 | 年份 | GitHub 原地址 |
|-----------|------|----------------|
| DaGAN | — | — |
| TPSMM | — | — |
| MCNet | — | — |
| HyperReenact | — | — |
| LIA | — | — |
| LivePortrait | — | — |

---

### 🗣️ Talking Face（语音驱动说话人脸）

| 方法名称 | 年份 | GitHub 原地址 |
|-----------|------|----------------|
| [SadTalker](https://github.com/OpenTalker/SadTalker) | 2023 | https://github.com/OpenTalker/SadTalker |
| [IP-LAP](https://github.com/Weizhi-Zhong/IP_LAP) | 2023 | https://github.com/Weizhi-Zhong/IP_LAP |
| AniTalker | — | — |
| EDTalk | — | — |
| Real3D-Portrait | — | — |
| EchoMimic | — | — |
| FLOAT | — | — |

---
