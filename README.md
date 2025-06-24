# **Medical Large Vision Language Models with Multi-Image Visual Ability**

---
## Release
- [June 24, 2025] Med-MIM Benchmark dataset is open-sourced.
- [June 23, 2025] Med-MIM Instruction dataset is open-sourced.
- [June 18, 2025] Med-MIM has been accepted by MICCAI 2025.



## Model Download

- Both MIM-LLaVA-Med and Med-Mantis will be released soon.


## Data Download
| Med-MIM Instruction Dataset | Data Sources |
| --- | --- |
| [Med_MIM_train_inherent_Temporal.json](Instruction_Dataset/Med_MIM_train_inherent_Temporal.json) | EMBED, LUMIERE |
| [Med_MIM_train_inherent_Reasoning.json](Instruction_Dataset/Med_MIM_train_inherent_Reasoning.json) | EMBED |
| [Med_MIM_train_inherent_Comparison.json](Instruction_Dataset/Med_MIM_train_inherent_Comparison.json) | LUMIERE, MS-CXR-T |
| [Med_MIM_train_inherent_Coreference.json](Instruction_Dataset/Med_MIM_train_inherent_Coreference.json) | EMBED, LUMIERE |
| [Med_MIM_train_Composed.json](Instruction_Dataset/Med_MIM_train_Composed.json) | PMC-15M |

| Med-MIM Benchmark | Data Sources |
| --- | --- | 
| [Med_MIM_benchmark_Held_in_Temporal.json](Benchmark_Dataset/Med_MIM_benchmark_Held_in_Temporal.json) | EMBED, LUMIERE |
| [Med_MIM_benchmark_Held_in_Reasoning.json](Benchmark_Dataset/Med_MIM_benchmark_Held_in_Reasoning.json) | EMBED |
| [Med_MIM_benchmark_Held_in_Comparison.json](Benchmark_Dataset/Med_MIM_benchmark_Held_in_Comparison.json) | LUMIERE, MS-CXR-T |
| [Med_MIM_benchmark_Held_in_Coreference.json](Benchmark_Dataset/Med_MIM_benchmark_Held_in_Coreference.json) | EMBED, LUMIERE |
| [Med_MIM_benchmark_Held_out_ODIR.json](Benchmark_Dataset/Med_MIM_benchmark_Held_out_ODIR.json) | ODIR |
| [Med_MIM_benchmark_Held_out_RAD.json](Benchmark_Dataset/Med_MIM_benchmark_Held_out_RAD.json) | VQA-RAD |


**Dataset Usage Notices**
The imaging dataset is comprised of six datasets:
- [EMBED](https://registry.opendata.aws/emory-breast-imaging-dataset-embed/)
- [LUMIERE](https://springernature.figshare.com/collections/The_LUMIERE_Dataset_Longitudinal_Glioblastoma_MRI_with_Expert_RANO_Evaluation/5904905/1)
- [MS-CXR-T](https://physionet.org/content/ms-cxr-t/1.0.0/)
- [PMC-15M](https://arxiv.org/abs/2303.00915) 
- [ODIR](https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k) 
- [VQA-RAD](https://osf.io/89kps/) 

Access requirements:
- You need to apply for access of the dataset: [EMBED](https://registry.opendata.aws/emory-breast-imaging-dataset-embed/) and [MS-CXR-T](https://physionet.org/content/ms-cxr-t/1.0.0/).
- For PMC-15M, refer to the [LLaVA-Med project](https://github.com/microsoft/LLaVA-Med) for download instructions.

## Citation

```bibtex
@article{yang2025medical,
  title={Medical Large Vision Language Models with Multi-Image Visual Ability},
  author={Yang, Xikai and Miao, Juzheng and Yuan, Yuchen and Wang, Jiaze and Dou, Qi and Li, Jinpeng and Heng, Pheng-Ann},
  journal={arXiv preprint arXiv:2505.19031},
  year={2025}
}

```
