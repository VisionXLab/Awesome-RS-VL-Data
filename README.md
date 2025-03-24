[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](https://github.com/zytx121/Awesome-VLGFM/pulls)
<br />
# Awesome-RS-SFT-Data
This repository is proposed to facilitate training remote sensing Multimodal large language models (RS-MLLMs) by recommending high-quality supervised fine-tuning (SFT) data. If you find any work missing or have any suggestions, feel free to [pull requests](https://github.com/zytx121/Awesome-RS-SFT-Data/pulls).

## Summary of Contents

- [Summary of Contents](#summary-of-contents)
- [Comprehensive SFT](comprehensive-sft)
- [Task-specific SFT](task-specific-sft)
- [Benchmark](benchmark)
- [Meta Data](meta-data)

## Comprehensive SFT

|Year|Venue|Keywords|Name|Code/Project|Download|
|:-:|:-:|:-:|-|-|-|
|2023|arXiv| |[RS5M](https://arxiv.org/abs/2306.11300)|[Code](https://github.com/om-ai-lab/RS5M)|[link](https://huggingface.co/datasets/Zilun/RS5M)|
|2023|arXiv| |[LAION-EO](https://arxiv.org/abs/2309.15535)|N/A|[link](https://huggingface.co/datasets/mikonvergence/LAION-EO)|
|2023|arXiv| |[RSICap & RSIEval](https://arxiv.org/abs/2307.15266)|[Code](https://github.com/Lavender105/RSGPT)|N/A|
|2024|ICLR | |[NAIP-OSM](https://arxiv.org/abs/2312.06960)|[Project](https://graft.cs.cornell.edu)|N/A|
|2024|AAAI| |[SkyScript](https://arxiv.org/abs/2312.12856)|[Code](https://github.com/wangzhecheng/SkyScript)|[link](https://github.com/wangzhecheng/SkyScript#download)|
|2024|CVPR| |[GeoChat-Instruct & GeoChat-Bench](https://arxiv.org/abs/2311.15826)|[Code](https://github.com/mbzuai-oryx/geochat)|[link](https://huggingface.co/datasets/MBZUAI/GeoChat_Instruct)|
|2024|arXiv| |[SkyEye-968k](https://arxiv.org/abs/2401.09712)|[Code](https://github.com/ZhanYang-nwpu/SkyEyeGPT)|N/A|
|2024|arXiv| |[MMRS-1M](https://arxiv.org/abs/2401.16822)|[Project](https://github.com/wivizhang/EarthGPT)|N/A|
|2024|arXiv| |[LHRS-Align & LHRS-Instruct](https://arxiv.org/abs/2402.02544)|[Code](https://github.com/NJU-LHRS/LHRS-Bot)|N/A|
|2024|arXiv| |[VLEO-Bench](https://arxiv.org/abs/2401.17600)|[Code](https://vleo.danielz.ch/)|[link](https://huggingface.co/collections/mit-ei/vleo-benchmark-datasets-65b789b0466555489cce0d70)|
|2024|arXiv| |[LuoJiaHOG](https://arxiv.org/abs/2403.10887)|N/A|N/A|
|2024|arXiv| |[RS-GPT4V](https://arxiv.org/abs/2406.12479)|N/A|N/A|
|2024|arXiv| |[VRSBench](https://arxiv.org/abs/2406.12384)|[Project](https://github.com/lx709/VRSBench)|[link](https://huggingface.co/datasets/xiang709/VRSBench)|
|2024|arXiv| |[RSTeller](https://arxiv.org/abs/2408.14744)|[Project](https://github.com/SlytherinGe/RSTeller/)|[link](https://huggingface.co/datasets/SlytherinGe/RSTeller)|
|2024|arXiv| |[MME-RealWorld](https://arxiv.org/abs/2408.13257)|[Project](https://mme-realworld.github.io/home_page.html)|[link](https://huggingface.co/datasets/yifanzhang114/MME-RealWorld)|
|2024|arXiv| |[UrBench](https://arxiv.org/abs/2408.17267)|[Project](https://opendatalab.github.io/UrBench/)|N/A|
|2024|arXiv| |[MMM-RS](https://arxiv.org/abs/2410.22362)|[Project](https://github.com/ljl5261/MMM-RS)|N/A|
|2024|arXiv| |[DDFAV](https://arxiv.org/abs/2411.02733)|[Project](https://github.com/HaodongLi2024/rspope/)|N/A|
|2024|arXiv| |[COREval](https://arxiv.org/abs/2411.18145)|N/A|N/A|
|2024|arXiv| |[GEOBench-VLM](https://arxiv.org/abs/2411.19325)|[Project](https://github.com/The-AI-Alliance/GEO-Bench-VLM)|N/A|
|2025|arXiv| |[Falcon](https://arxiv.org/abs/2503.11070)|[Project](https://github.com/TianHuiLab/Falcon)|[link](https://www.modelscope.cn/datasets/TianHuiLab/FCD-78M)|


## Task-specific SFT

### Image Captioning

- `Change`: Change Captioning
- `Video`: Video Captioning

|Year|Venue|Keywords|Name|Code/Project|Download|
|:-:|:-:|:-:|-|-|-|
|2016|CITS| |[Sydney-Captions & UCM-Captions](https://ieeexplore.ieee.org/abstract/document/7546397)|[N/A]|[link](https://pan.baidu.com/s/1mjPToHq#list/path=%2F),[link2](https://pan.baidu.com/s/1hujEmcG#list/path=%2F)|
|2017|TGRS| |[RSICD](https://ieeexplore.ieee.org/document/8240966)|[Project](https://github.com/201528014227051/RSICD_optimal)|[Link](https://pan.baidu.com/s/1bp71tE3#list/path=%2F)|
|2021|TGRS| |[RSITMD](https://ieeexplore.ieee.org/document/9437331)|[Code](https://github.com/xiaoyuan1996/AMFMN)|[link](https://drive.google.com/file/d/1NJY86TAAUd8BVs7hyteImv8I2_Lh95W6/view)|
|2022|TGRS| |[NWPU-Captions](https://ieeexplore.ieee.org/document/9866055)|[Project](https://github.com/HaiyanHuang98/NWPU-Captions)|[link](https://github.com/HaiyanHuang98/NWPU-Captions)|
|2022|TGRS| |[UAV-Captions](https://ieeexplore.ieee.org/document/9521989)|N/A|N/A|
|2022|TGRS|`Change`|[LEVIR-CC](https://ieeexplore.ieee.org/abstract/document/9934924)|[Project](https://github.com/Chen-Yang-Liu/RSICC)|[link](https://github.com/Chen-Yang-Liu/LEVIR-CC-Dataset)|
|2022|RS|`Video`|[CapERA](https://www.mdpi.com/2072-4292/15/8/2139)|[Project](https://lcmou.github.io/ERA_Dataset/)|[link](https://drive.google.com/file/d/1yxXjDNAq5RAufSgSOE4QmdsNfAc4dOfM/view)|

### Visual Question Answering (VQA)

- `Temporal`: Multi-Image Question
- `Math`: Mathematical Question

|Year|Venue|Keywords|Name|Code/Project|Download|
|:-:|:-:|:-:|-|-|-|
|2020|TGRS| |[RSVQA-LR & RSVQA-HR](https://arxiv.org/abs/2003.07333)|[Project](https://rsvqa.sylvainlobry.com)|[link1](https://zenodo.org/records/6344334),[link2](https://zenodo.org/records/6344367)|
|2021|IGARSS| |[RSVQAxBEN](https://rsvqa.sylvainlobry.com/IGARSS21.pdf)|[Project](https://rsvqa.sylvainlobry.com)|[link](https://zenodo.org/records/5084904)|
|2021|Access| |[FloodNet](https://ieeexplore.ieee.org/abstract/document/9460988)|[Project](https://github.com/BinaLab/FloodNet-Supervised_v1.0)|[link](https://drive.google.com/drive/folders/1leN9eWVQcvWDVYwNb2GCo5ML_wBEycWD)|
|2021|TGRS| |[RSIVQA](https://ieeexplore.ieee.org/document/9444570)|[Code](https://github.com/spectralpublic/RSIVQA)|[link](https://github.com/spectralpublic/RSIVQA/tree/main/RSIVQA)|
|2022|TGRS|`Temporal`|[CDVQA](https://ieeexplore.ieee.org/abstract/document/9901476)|[Project](https://github.com/YZHJessica/CDVQA)|[link](https://github.com/YZHJessica/CDVQA)|
|2022|IJRS| |[VQA-TextRS](https://www.tandfonline.com/doi/abs/10.1080/01431161.2022.2145583)|N/A|N/A|
|2022|TGRS| |[CRSVQA](https://ieeexplore.ieee.org/abstract/document/10242124)|[Project](https://github.com/MeimeiZhang-data/MQVQA)|[link](https://drive.google.com/file/d/12DQwGzJ5OQK1rU0T5CmpNN9bEs38x_mQ/view)|
|2023|arXiv|`Math`|[RemoteCount](https://arxiv.org/abs/2306.11029)|[Code](https://github.com/ChenDelong1999/RemoteCLIP)|N/A|
|2024|AAAI |`SEG`|[EarthVQA](https://arxiv.org/abs/2312.12222)|[Project](https://junjuewang.top/EarthVQA)|N/A|

### Visual Grounding

- `HBB`: Horizontal Bounding Box 
- `OBB`: Oriented Bounding Box
- `SEG`: Segmentation

|Year|Venue|Keywords|Name|Code/Project|Download|
|:-:|:-:|:-:|-|-|-|
|2022|MM|`HBB`|[RSVG](https://dl.acm.org/doi/abs/10.1145/3503161.3548316)|[Project](https://sunyuxi.github.io/publication/GeoVG)|[link](https://drive.google.com/file/d/1kgnmVC6FVKdxCwaoG77sOfkaIHS_XiFt/view)|
|2023|TGRS|`HBB`|[DIOR-RSVG](https://ieeexplore.ieee.org/abstract/document/10056343)|[Project](https://github.com/ZhanYang-nwpu/RSVG-pytorch)|[link](https://drive.google.com/drive/folders/1hTqtYsC6B-m4ED2ewx5oKuYZV13EoJp_)|
|2024|ECCV|`HBB`|[GeoText](https://arxiv.org/abs/2311.12751)|[Project](https://multimodalgeo.github.io/GeoText/)|[link](https://huggingface.co/datasets/truemanv5666/GeoText1652_Dataset)|
|2024|TGRS|`HBB`|[RSVG-HR](https://ieeexplore.ieee.org/abstract/document/10542207)|[Project](https://github.com/LANMNG/LQVG)|N/A|
|2024|TGRS|`HBB`|[OPT-RSVG](https://ieeexplore.ieee.org/abstract/document/10584552)|[Project](https://github.com/like413/OPT-RSVG)|[link](https://drive.google.com/drive/folders/1e_wOtkruWAB2JXR7aqaMZMrM75IkjqCA)|
|2024|TGRS|`SEG`|[RRSIS](https://ieeexplore.ieee.org/abstract/document/10458079)|[Code](https://gitlab.lrz.de/ai4eo/reasoning/rrsis)|[link](https://huggingface.co/datasets/JessicaYuan/RefSegRS)|
|2024|CVPR|`SEG`|[RRSIS-D](https://arxiv.org/abs/2312.12470)|[Code](https://github.com/Lsan2401/RMSIN)|[link](https://drive.google.com/drive/folders/1Xqi3Am2Vgm4a5tHqiV9tfaqKNovcuK3A)|

## Meta Data

### Classification
|Year|Venue|Keywords|Name|Code/Project|Download|
|:-:|:-:|:-:|-|-|-|
|2023|ICCVW| |[SATIN](https://arxiv.org/abs/2304.11619)|[Project](https://satinbenchmark.github.io/)|[link](https://huggingface.co/datasets/jonathan-roberts1/SATIN)|

### Detection
|Year|Venue|Keywords|Name|Code/Project|Download|
|:-:|:-:|:-:|-|-|-|

### Segmentation
|Year|Venue|Keywords|Name|Code/Project|Download|
|:-:|:-:|:-:|-|-|-|
|2024|arXiv| |[ChatEarthNet](https://arxiv.org/abs/2402.11325)|[project](https://github.com/zhu-xlab/ChatEarthNet)|[link](https://doi.org/10.5281/zenodo.11003436)|
|2024|arXiv| |[FineGrip](https://arxiv.org/abs/2404.04608)|N/A|N/A|






