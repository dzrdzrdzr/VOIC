# VOIC: Visible-Occluded Decoupling for Monocular 3D Semantic Scene Completion

**[论文标题]**: VOIC: Visible-Occluded Decoupling for Monocular 3D Semantic Scene Completion  
**[作者]**: Zaidao Han, Risa Higashita, Jiang Liu  
**[期刊]**: IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)

---

## 📢 News / Updates

* **2025-03**: Our paper has been submitted to IEEE TCSVT.
* **Coming Soon** 🚀: The code and pre-trained models will be released immediately upon publication. Please **star ⭐ this repository** to receive notifications!

---

## 🏠 Abstract

Camera-based 3D Semantic Scene Completion (SSC) is a critical task for autonomous driving and robotic scene understanding, aiming to infer a complete 3D volumetric representation of both semantics and geometry from a single image.

Existing methods typically focus on end-to-end 2D-to-3D feature lifting and voxel completion, yet they often overlook the interference between high-confidence **visible-region perception** and low-confidence **occluded-region reasoning**.

To address these challenges, we introduce **VOIC (Visible-Occluded Interactive Completion Network)**. Our contributions are:

* **VRLE (Visible Region Label Extraction):** An offline strategy that explicitly separates and extracts voxel-level supervision for visible regions from dense 3D ground truth.
* **Dual-Decoder Framework:** Explicitly decouples SSC into visible-region semantic perception (**Visible Decoder**) and occluded-region scene completion (**Occlusion Decoder**).
* **SOTA Performance:** VOIC outperforms existing monocular SSC methods on **SemanticKITTI** and **SSCBench-KITTI360** benchmarks.

---

## 🏆 Results

VOIC achieves state-of-the-art performance on the SemanticKITTI hidden test set. For a detailed comparison with other methods, please refer to our full paper.

| Method | IoU (%) | mIoU (%) |
| :--- | :---: | ---: |
| **VOIC (Ours)** | **45.69** | **17.42** |

---

## 📝 Methodology

  
**Figure:** The proposed VOIC framework. (a) Visible Embedding Feature Constructor (VEFC); (b) Visible Decoder (VD); (c) Occlusion Decoder (OD).

---

## 📅 TODO

* [ ] Release training and inference code.
* [ ] Release pre-trained models (SemanticKITTI & SSCBench).
* [ ] Provide VRLE preprocessing scripts.

---

## 🔗 Citation

If you find our work useful in your research, please consider citing:

```bibtex
@article{han2025voic,
  title={VOIC: Visible-Occluded Decoupling for Monocular 3D Semantic Scene Completion},
  author={Han, Zaidao and Higashita, Risa and Liu, Jiang},
  journal={IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)},
  year={2025}
}
