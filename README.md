# Notes

## Performance Comparison of Different Methods on Various Benchmarks
| Method | V*   | Hallusion Bench | ScienceQA | MMVP | MMStar | Blink | HRBench4k | HRBench8k |  NoteLink |
| ------ | ---- | --------------- | --------- | ---- | ------ | ----- | --------- | --------- | ---- |
|[LaViT](https://github.com/Svardfox/LaViT)|      |                 |           |      |        |       |           |           |[:link:]()|
|[DMLR](https://mllm-dmlr.github.io/)| | | | | | | | | [:link:]() |
|[Monet](https://github.com/NOVAglow646/Monet)| | | | | | | | | [:link:]() |
|[LVR](https://github.com/VincentLeebang/lvr)| | | | | | | | | [:link:]() |

## Content
### 1. LaViT
**Core challenge**: Student models frequently mimic a teacher’s textual output while attending to fundamentally divergent visual regions, effectively relying on language priors rather than grounded perception.  
**Method**: LaViT compels the student to autoregressively reconstruct the teacher’s visual semantics and attention trajectories prior to text generation, employing a curriculum sensory gating mechanism to prevent shortcut learning.  
**Contributions**: LaViT-15K dataset, semantic reconstruction loss, trajectory alignment loss, curriculum sensory gating.  

### 2. DMLR
**Core challenge**:  
**Method**:  
**Contributions**:  

### 3. Monet
**Core challenge**:  
**Method**:  
**Contributions**:  

### 3. LVR
**Core challenge**:  
**Method**:  
**Contributions**:  
