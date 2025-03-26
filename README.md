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


|Year|Venue|Keywords|Name|Download|Discuss|
|:-:|:-:|:-:|-|-|:-:|
|2023|arXiv| |[RS5M](https://arxiv.org/abs/2306.11300)|[link](https://github.com/om-ai-lab/RS5M)| |
|2023|arXiv| |[LAION-EO](https://arxiv.org/abs/2309.15535)|[link](https://huggingface.co/datasets/mikonvergence/LAION-EO)| |
|2023|arXiv| |[RSICap & RSIEval](https://arxiv.org/abs/2307.15266)|[link](https://github.com/Lavender105/RSGPT)| |
|2024|ICLR | |[NAIP-OSM](https://arxiv.org/abs/2312.06960)|[link](https://graft.cs.cornell.edu)| |
|2024|AAAI| |[SkyScript](https://arxiv.org/abs/2312.12856)|[link](https://github.com/wangzhecheng/SkyScript)| |
|2024|CVPR| |[GeoChat](https://arxiv.org/abs/2311.15826)|[link](https://github.com/mbzuai-oryx/geochat)| |
|2024|arXiv| |[SkyEye-968k](https://arxiv.org/abs/2401.09712)|[link](https://github.com/ZhanYang-nwpu/SkyEyeGPT)| |
|2024|arXiv| |[MMRS-1M](https://arxiv.org/abs/2401.16822)|[link](https://github.com/wivizhang/EarthGPT)| |
|2024|arXiv| |[LHRS-Align & LHRS-Instruct](https://arxiv.org/abs/2402.02544)|[link](https://github.com/NJU-LHRS/LHRS-Bot)| |
|2024|arXiv| |[VLEO-Bench](https://arxiv.org/abs/2401.17600)|[link](https://vleo.danielz.ch/)| |
|2024|arXiv| |[LuoJiaHOG](https://arxiv.org/abs/2403.10887)|N/A| |
|2024|arXiv| |[RS-GPT4V](https://arxiv.org/abs/2406.12479)|N/A| |
|2024|arXiv| |[VRSBench](https://arxiv.org/abs/2406.12384)|[link](https://github.com/lx709/VRSBench)|[![](https://img.shields.io/badge/%E2%9D%A4-ff69b4.svg)](https://github.com/zytx121/Awesome-RS-SFT-Data/issues/1)|
|2024|arXiv| |[RSTeller](https://arxiv.org/abs/2408.14744)|[link](https://github.com/SlytherinGe/RSTeller/)| |
|2024|arXiv| |[MME-RealWorld](https://arxiv.org/abs/2408.13257)|[link](https://mme-realworld.github.io/home_page.html)| |
|2024|arXiv| |[UrBench](https://arxiv.org/abs/2408.17267)|[link](https://opendatalab.github.io/UrBench/)| |
|2024|arXiv| |[MMM-RS](https://arxiv.org/abs/2410.22362)|[link](https://github.com/ljl5261/MMM-RS)| |
|2024|arXiv| |[DDFAV](https://arxiv.org/abs/2411.02733)|[link](https://github.com/HaodongLi2024/rspope/)| |
|2024|arXiv| |[COREval](https://arxiv.org/abs/2411.18145)| |
|2024|arXiv| |[GEOBench-VLM](https://arxiv.org/abs/2411.19325)|[link](https://github.com/The-AI-Alliance/GEO-Bench-VLM)| |
|2025|arXiv| |[Falcon](https://arxiv.org/abs/2503.11070)|[link](https://github.com/TianHuiLab/Falcon)| |


## Task-specific SFT

### Image Captioning

- `Change`: Change Captioning
- `Video`: Video Captioning

|Year|Venue|Keywords|Name|Download|
|:-:|:-:|:-:|-|-|
|2016|CITS| |[Sydney-Captions & UCM-Captions](https://ieeexplore.ieee.org/abstract/document/7546397)|[link](https://pan.baidu.com/s/1mjPToHq#list/path=%2F),[link2](https://pan.baidu.com/s/1hujEmcG#list/path=%2F)|
|2017|TGRS| |[RSICD](https://ieeexplore.ieee.org/document/8240966)|[link](https://github.com/201528014227051/RSICD_optimal)|
|2021|TGRS| |[RSITMD](https://ieeexplore.ieee.org/document/9437331)|[link](https://github.com/xiaoyuan1996/AMFMN)|
|2022|TGRS| |[NWPU-Captions](https://ieeexplore.ieee.org/document/9866055)|[link](https://github.com/HaiyanHuang98/NWPU-Captions)|
|2022|TGRS| |[UAV-Captions](https://ieeexplore.ieee.org/document/9521989)|N/A|
|2022|TGRS|`Change`|[LEVIR-CC](https://ieeexplore.ieee.org/abstract/document/9934924)|[link](https://github.com/Chen-Yang-Liu/RSICC)|
|2022|RS|`Video`|[CapERA](https://www.mdpi.com/2072-4292/15/8/2139)|[link](https://lcmou.github.io/ERA_Dataset/)|

### Visual Question Answering (VQA)

- `Temporal`: Multi-Image Question
- `Math`: Mathematical Question

|Year|Venue|Keywords|Name|Download|
|:-:|:-:|:-:|-|-|
|2020|TGRS| |[RSVQA-LR & RSVQA-HR](https://arxiv.org/abs/2003.07333)|[link](https://rsvqa.sylvainlobry.com)|
|2021|IGARSS| |[RSVQAxBEN](https://rsvqa.sylvainlobry.com/IGARSS21.pdf)|[link](https://rsvqa.sylvainlobry.com)|
|2021|Access| |[FloodNet](https://ieeexplore.ieee.org/abstract/document/9460988)|[link](https://github.com/BinaLab/FloodNet-Supervised_v1.0)|
|2021|TGRS| |[RSIVQA](https://ieeexplore.ieee.org/document/9444570)|[link](https://github.com/spectralpublic/RSIVQA)|
|2022|TGRS|`Temporal`|[CDVQA](https://ieeexplore.ieee.org/abstract/document/9901476)|[link](https://github.com/YZHJessica/CDVQA)|
|2022|IJRS| |[VQA-TextRS](https://www.tandfonline.com/doi/abs/10.1080/01431161.2022.2145583)|N/A|
|2022|TGRS| |[CRSVQA](https://ieeexplore.ieee.org/abstract/document/10242124)|[link](https://github.com/MeimeiZhang-data/MQVQA)|
|2023|arXiv|`Math`|[RemoteCount](https://arxiv.org/abs/2306.11029)|[link](https://github.com/ChenDelong1999/RemoteCLIP)|
|2024|AAAI |`SEG`|[EarthVQA](https://arxiv.org/abs/2312.12222)|[link](https://junjuewang.top/EarthVQA)|

### Visual Grounding

- `HBB`: Horizontal Bounding Box 
- `OBB`: Oriented Bounding Box
- `SEG`: Segmentation

|Year|Venue|Keywords|Name|Download|
|:-:|:-:|:-:|-|-|
|2022|MM|`HBB`|[RSVG](https://dl.acm.org/doi/abs/10.1145/3503161.3548316)|[link](https://sunyuxi.github.io/publication/GeoVG)|
|2023|TGRS|`HBB`|[DIOR-RSVG](https://ieeexplore.ieee.org/abstract/document/10056343)|[link](https://github.com/ZhanYang-nwpu/RSVG-pytorch)|
|2024|ECCV|`HBB`|[GeoText](https://arxiv.org/abs/2311.12751)|[link](https://multimodalgeo.github.io/GeoText/)|
|2024|TGRS|`HBB`|[RSVG-HR](https://ieeexplore.ieee.org/abstract/document/10542207)|[link](https://github.com/LANMNG/LQVG)|
|2024|TGRS|`HBB`|[OPT-RSVG](https://ieeexplore.ieee.org/abstract/document/10584552)|[link](https://github.com/like413/OPT-RSVG)|
|2024|TGRS|`SEG`|[RRSIS](https://ieeexplore.ieee.org/abstract/document/10458079)|[link](https://gitlab.lrz.de/ai4eo/reasoning/rrsis)|
|2024|CVPR|`SEG`|[RRSIS-D](https://arxiv.org/abs/2312.12470)|[link](https://github.com/Lsan2401/RMSIN)|

## Meta Data

### Classification
|Year|Venue|Keywords|Name|Download|
|:-:|:-:|:-:|-|-|
|2017|TGRS| |[AID](https://captain-whu.github.io/AID/)|[link](https://captain-whu.github.io/AID/)|
|2017|Proc. IEEE| |[NWPU-RESISC45](https://ieeexplore.ieee.org/abstract/document/7891544)|[link](https://gcheng-nwpu.github.io/#Datasets)|
|2019|JSTARS| |[EuroSAT](https://ieeexplore.ieee.org/abstract/document/8736785)|[link](https://zenodo.org/records/7711810)|
|2020|Website| |AiRound|[link](http://patreo.dcc.ufmg.br/2020/07/22/multi-view-datasets/)|
|2020|Website| |airplane_det|[link](https://aistudio.baidu.com/datasetdetail/131179)|
|2020|Sensor| |[CLRS](https://www.mdpi.com/1424-8220/20/4/1226)|[link](https://huggingface.co/datasets/jonathan-roberts1/CLRS)|
|2021|Website| |ship_det|[link](https://aistudio.baidu.com/datasetdetail/134218)|
|2023|ICCVW| |[SATIN](https://arxiv.org/abs/2304.11619)|[link](https://satinbenchmark.github.io/)|


### Detection
|Year|Venue|Keywords|Name|Download|
|:-:|:-:|:-:|-|-|
|2014|ISPRS JPRS| |[NWPU VHR-10](https://www.sciencedirect.com/science/article/abs/pii/S0924271614002524)|[link](https://gcheng-nwpu.github.io/#Datasets)|
|2018|CVPR| |[DOTA](https://arxiv.org/abs/1711.10398)|[link](https://captain-whu.github.io/DOTA/dataset.html)|
|2018|Kaggle| |ASD|[link](https://www.kaggle.com/c/airbus-ship-detection)|
|2020|ISPRS JPRS| |[DIOR](https://www.sciencedirect.com/science/article/abs/pii/S0924271619302825)|[link](https://gcheng-nwpu.github.io/#Datasets)|
|2022|JRS| |[MAR20](https://www.ygxb.ac.cn/en/article/doi/10.11834/jrs.20222139/)|[link](https://gcheng-nwpu.github.io/#Datasets)|
|2022|ISPRS JPRS| |[FAIR1M](https://www.sciencedirect.com/science/article/abs/pii/S0924271621003269)|[link](https://gaofen-challenge.com/benchmark)|
|2023|TPAMI| |[SODA-A](https://ieeexplore.ieee.org/abstract/document/10168277/)|[link](https://gcheng-nwpu.github.io/#Datasets)|


### Segmentation
|Year|Venue|Keywords|Name|Download|
|:-:|:-:|:-:|-|-|
|2020|Website| |BHP Watertanks|[link](http://patreo.dcc.ufmg.br/2020/07/29/bh-pools-watertanks-datasets/)|
|2024|arXiv| |[ChatEarthNet](https://arxiv.org/abs/2402.11325)|[link](https://github.com/zhu-xlab/ChatEarthNet)|
|2024|arXiv| |[FineGrip](https://arxiv.org/abs/2404.04608)|N/A|
|2018|RS| |[DLRSD](https://www.mdpi.com/2072-4292/10/6/964)|[link](https://sites.google.com/view/zhouwx/dataset#h.p_hQS2jYeaFpV0)|
|2021|TGRS| |[GEONRW](https://ieeexplore.ieee.org/document/9406194)|[link](https://ieee-dataport.org/open-access/geonrw)|


### Change Detection
|Year|Venue|Keywords|Name|Download|
|:-:|:-:|:-:|-|-|
|2018|ISPRS Archives| |[CDD](https://isprs-archives.copernicus.org/articles/XLII-2/565/2018/)|[link](https://drive.google.com/file/d/1GX656JqqOyBi_Ef0w65kDGVto-nHrNs9/edit)|
|2020|ISPRS JPRS| |[DSIFN](https://www.sciencedirect.com/science/article/abs/pii/S0924271620301532)|[link](https://github.com/GeoZcx/A-deeply-supervised-image-fusion-network-for-change-detection-in-remote-sensing-images/tree/master/dataset)|
|2023|GRSL| |[EGY BCD](https://ieeexplore.ieee.org/abstract/document/10145434/)|[link](https://github.com/oshholail/EGY-BCD)|





||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|
||| |[]()|[link]()|N/A|



