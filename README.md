# Notes

## Performance Comparison of Different Methods on Various Benchmarks

| Method           | V*   | Hallusion Bench | ScienceQA | MMVP | MMStar | Blink | HRBench4k | HRBench8k |
| ---------------- | ---- | --------------- | --------- | ---- | ------ | ----- | --------- | --------- |
| [LaViT](#LaViT)  |      |                 |           |      |        |       |           |           |
| [DMLR](#DMLR)    |      |                 |           |      |        |       |           |           |
| [Monet](#Monet)  |      |                 |           |      |        |       |           |           |
| [LVR}(LVR)       |      |                 |           |      |        |       |           |           |

## Content

### LaViT

**Core challenge**: Student models frequently mimic a teacher’s textual output while attending to fundamentally divergent visual regions, effectively relying on language priors rather than grounded perception.  

**Method**: LaViT compels the student to autoregressively reconstruct the teacher’s visual semantics and attention trajectories prior to text generation, employing a curriculum sensory gating mechanism to prevent shortcut learning.  

**Contributions**: LaViT-15K dataset, semantic reconstruction loss, trajectory alignment loss, curriculum sensory gating.  

[Github](https://github.com/Svardfox/LaViT)

```bibtex

@misc{wu2026lavitaligninglatentvisual,

   title={LaViT: Aligning Latent Visual Thoughts for Multi-modal Reasoning}, 

   author={Linquan Wu and Tianxiang Jiang and Yifei Dong and Haoyu Yang and Fengji Zhang and Shichaang Meng and Ai Xuan and Linqi Song and Jacky Keung},

   year={2026},

   eprint={2601.10129},

   archivePrefix={arXiv},

   primaryClass={cs.CV},

   url={https://arxiv.org/abs/2601.10129}, 

}

```

### DMLR

[Github](https://mllm-dmlr.github.io/)

**Core challenge**:  

**Method**:  

**Contributions**:  

### Monet

[Github](https://github.com/NOVAglow646/Monet)

**Core challenge**:  

**Method**:  

**Contributions**:  

### LVR

[Github](https://github.com/VincentLeebang/lvr)

**Core challenge**:  

**Method**:  

**Contributions**:  
