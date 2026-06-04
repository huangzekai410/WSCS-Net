# WSCS-Net
Official implementation of WSCS-Net: A Weakly Supervised Cell Segmentation Network Based on a Cooperative Learning Framework.



# WSCS-Net: Weakly Supervised Cell Instance Segmentation via Collaborative Learning

This repository is the official PyTorch implementation of the paper:  
"Weakly Supervised Cell Instance Segmentation via Collaborative Learning Framework"

---

## 📢 News & Repository Status
- 🚀 The paper is currently under peer review. 
- To protect intellectual property and maintain compliance with the review process, the complete source code, preprocessing scripts, and pre-trained model weights **will be fully released immediately upon the acceptance of our paper**. Stay tuned!

---

## ✨ Abstract
This paper proposes a weakly supervised cell instance segmentation method based on a collaborative learning framework. Built upon CondInst, the proposed framework introduces a deformable convolution (DC) branch to enhance the adaptive receptive field, thereby facilitating the extraction of cell regions with diverse scales. An unsupervised loss function is designed to assist the training of the DC branch without requiring pixel-level annotations, thereby reducing the annotation workload. Experimental results on multiple datasets (including cervical cell and histopathological nuclear segmentation) demonstrate that our method achieves competitive performance against state-of-the-art weakly supervised approaches.

---

## 🏗️ Network Architecture
*(Optional: You can upload your framework/pipeline JPG/PNG into the repo and display it here)* ---

## ⚙️ Environment & Requirements (Prerequisites)
The repository is being developed using **PyTorch**. The finalized environment configuration will include:
- Python >= 3.8
- PyTorch >= 1.12.0
- CUDA >= 11.3
- OpenCV, Scikit-image, Albumentations

---

## 🚀 Expected Features upon Release
Once the paper is accepted, this repository will provide:
1. Full Training & Inference Code**: End-to-end pipeline for weakly supervised cell segmentation.
2. Pre-trained Weights**: Model weights evaluated on cervical and histopathological datasets.
3. Data Preprocessing**: Scripts for parsing bounding-box annotations to format required by WSCS-Net.

---

## ✍️ Citation
If you find our work or code useful in your research, please consider citing our paper (BibTeX placeholder):

```bibtex
@article{wscsnet2026,
  title={Weakly Supervised Cell Instance Segmentation via Collaborative Learning Framework},
  author={Your Name and Your Advisor and Others},
  journal={ },
  year={2026},
  publisher={Elsevier}
}



For any questions regarding the paper or the upcoming code release, please feel free to contact: zekaih0410@gmail.com
