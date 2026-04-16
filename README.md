
# VOIC: Visible–Occluded Integrated Guidance for 3D Semantic Scene Completion

**Zaidao Han, Risa Higashita, Jiang Liu**

---

## 📢 News / Updates

- **Coming Soon**: The code and pre-trained models will be released immediately upon publication.
- Please **star this repository** to receive future updates.

---

## 🏠 Abstract

Camera-based 3D Semantic Scene Completion (SSC) is a critical task for autonomous driving and robotic scene understanding, aiming to infer a complete 3D volumetric representation of both semantics and geometry from a single image.

Existing methods typically focus on end-to-end 2D-to-3D feature lifting and voxel completion, yet they often overlook the interference between high-confidence **visible-region perception** and low-confidence **occluded-region reasoning**.

To address these challenges, we introduce **VOIC (Visible-Occluded Interactive Completion Network)**. Our contributions are:

- **VRLE (Visible Region Label Extraction):** An offline strategy that explicitly separates and extracts voxel-level supervision for visible regions from dense 3D ground truth.
- **Dual-Decoder Framework:** Explicitly decouples SSC into visible-region semantic perception (**Visible Decoder**) and occluded-region scene completion (**Occlusion Decoder**).
- **State-of-the-Art Performance:** VOIC outperforms existing monocular SSC methods on **SemanticKITTI** and **SSCBench-KITTI360** benchmarks.

---

## 🎬 Visualization

### VOIC Result

<p align="center">
  <video src="assets/voic_demo.mp4" controls width="900"></video>
</p>

### Comparison Result

<p align="center">
  <video src="assets/comparison_demo.mp4" controls width="900"></video>
</p>

> Note: Please place the two MP4 files under the `assets/` directory.Recommended filenames:
>
> - `assets/voic_demo.mp4`
> - `assets/comparison_demo.mp4`

---

## 🏆 Results

VOIC achieves state-of-the-art performance on the SemanticKITTI hidden test set. For a detailed comparison with other methods, please refer to the full paper.

| Method                |     IoU (%)     |        mIoU (%) |
| :-------------------- | :-------------: | --------------: |
| **VOIC (Ours)** | **45.22** | **18.01** |

---
