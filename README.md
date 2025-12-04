VOIC: Visible-Occluded Decoupling for Monocular 3D Semantic Scene Completion

Zaidao Han, Risa Higashita, Jiang Liu


📢 News / Updates

Coming Soon
The code and pre-trained models will be released immediately upon publication.
Please star ⭐ this repository to receive notifications!

🏠 Abstract

Camera-based 3D Semantic Scene Completion (SSC) is a critical task for autonomous driving and robotic scene understanding, aiming to infer a complete 3D volumetric representation of both semantics and geometry from a single image.

Existing methods typically focus on end-to-end 2D-to-3D feature lifting and voxel completion, yet they often overlook the interference between high-confidence visible-region perception and low-confidence occluded-region reasoning.

To address these challenges, we introduce VOIC (Visible-Occluded Interactive Completion Network).
Our contributions are:

VRLE (Visible Region Label Extraction): An offline strategy that explicitly separates and extracts voxel-level supervision for visible regions from dense 3D ground truth.

Dual-Decoder Framework: Explicitly decouples SSC into visible-region semantic perception (Visible Decoder) and occluded-region scene completion (Occlusion Decoder).

SOTA Performance: VOIC outperforms existing monocular SSC methods on SemanticKITTI and SSCBench-KITTI360 benchmarks.

🏆 Results

VOIC achieves state-of-the-art performance on the SemanticKITTI hidden test set.

Method	IoU (%)	mIoU (%)
VOIC (Ours)	45.69	17.42

For detailed comparisons with other methods, please refer to our full paper.



📅 TODO

 Release training and inference code

 Release pre-trained models (SemanticKITTI & SSCBench)

 Provide VRLE preprocessing scripts

