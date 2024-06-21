## RGBD-Tracking-Results-Datasets-and-Methods

**An investigation for RGBD tracking. 
Hopefully, it can help other researchers become familiar with multi-modal tracking as soon as possible.
This repository is started on 27/12/2023, and will keep on updating.**

-----
>This repository will give a detail investigation of the RGBD tracking community, including the Datasets, Results, and the Methods.
> 
>  - [x] Datasets
>  - [x] Results
>  - [x] Methods
>  -  ...
-----

## Survey Papers
* RGBD---- A Survey of RGB-Depth Object Tracking. Zhou Ou, Ge Ying, Dawei Zhang*, Zhonglong Zheng. Journal of Computer-Aided Design & Computer Graphics 2024. [[Paper](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.null.2023-00537)]
* RGBD/T ---- Multi-modal visual tracking: Review and experimental comparison. Zhang, Pengyu, Dong Wang*, and Huchuan Lu. Computational Visual Media 2024. [[Paper](https://link.springer.com/article/10.1007/s41095-023-0345-5)]
* RGBD---- Rgbd object tracking: An in-depth review. Jinyu Yang, Zhe Li, Song Yan, Feng Zheng*, Aleš Leonardis, Joni-Kristian Kämäräinen, Ling Shao. Arxiv 2022. [[Paper](https://arxiv.org/abs/2203.14134)]

## Datasets
***Real Data***

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| D2CUBE| CVRP'2023|[D2CUBE](https://github.com/yjybuaa/RGBDAerialTracking)|Resource-Efficient RGBD Aerial Tracking|
| ARKittrack| CVPR'2023 | [ARKittrack](https://github.com/lawrence-cj/ARKitTrack) |ARKitTrack: A New Diverse Dataset for Tracking Using Mobile RGB-D Data|
| RGBD1K | AAAI'2023 | [RGBD1K](https://github.com/xuefeng-zhu5/RGBD1K) |RGBD1K: A Large-Scale Dataset and Benchmark for RGB-D Object Tracking|
| VOT-RGBD2022 | VOT Community | [VOT-RGBD2022](https://www.votchallenge.net/vot2022/dataset.html) |The Tenth Visual Object Tracking VOT2022 Challenge Results|
| DepthTrack | ICCV'2021 | [DepthTrack](https://github.com/xiaozai/DeT) |DepthTrack: Unveiling the Power of RGBD Tracking|
| CDTB | ICCV'2019 | [CDTB](https://www.votchallenge.net/vot2019/dataset.html) |CDTB: A Color and Depth Visual Object Tracking Dataset and Benchmark|
| STC | ICCV'2019 | [STC](https://pan.baidu.com/s/1Y3z2JH-oR68-stWFVnHUVw) code:TZYD|Robust Fusion of Color and Depth Data for RGB-D Target Tracking Using Adaptive Range-Invariant Depth Models and Spatio-Temporal Consistency Constraints|
| PTB | ICCV'2013 | [PTB](https://tracking.cs.princeton.edu/index.html) |Tracking Revisited using RGBD Camera: Unified Benchmark and Baselines|

-----
## Results


<table>
    <tr> 
        <th colspan="1"></th> 
	<th colspan="1"></th> 
	<th colspan="1"></th> 
        <th colspan="3">CDTB</th> 
        <th colspan="3">DepthTrack</th> 
        <th colspan="3">VOT-RGBD2022</th>
    </tr>
    <tr>
    	<td> Methods</td>
    	<td>Venue</td>
	<td>Speed</td>
    	<td> Pr</td>
    	<td> Re</td>
    	<td> F-score</td>
   	<td> Pr</td>
    	<td> Re</td>
    	<td> F-score</td>
   	<td> Pr</td>
    	<td> Re</td>
    	<td> F-score</td>
    </tr>
    <tr>
    	<td> Methods</td>
    	<td>Venue</td>
	<td>Speed</td>
    	<td> Pr</td>
    	<td> Re</td>
    	<td> F-score</td>
   	<td> Pr</td>
    	<td> Re</td>
    	<td> F-score</td>
   	<td> A</td>
    	<td> R</td>
    	<td> EAO</td>
    </tr>
    <tr>
    	<td> CDAAT</td>
    	<td>SPL'2024</td>
	<td>59.5</td>
    	<td> 66.5</td>
    	<td> 73.7</td>
    	<td> 69.9</td>
   	<td> 57.8</td>
    	<td> 60.3</td>
    	<td> 59.0</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> FECD</td>
    	<td>PRL'2024</td>
	<td></td>
    	<td> 63.7</td>
    	<td> 62.4</td>
    	<td> 63.0</td>
   	<td> 57.8</td>
    	<td> 60.3</td>
    	<td> 59.0</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> SSLTrack</td>
    	<td>PR'2024</td>
	<td>31.4</td>
    	<td> 65.0</td>
    	<td> 62.0</td>
    	<td> 63.5</td>
   	<td> 56.5</td>
    	<td> 49.1</td>
    	<td> 52.5</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> VADT</td>
    	<td>ICASSP'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 60.6</td>
    	<td> 60.3</td>
    	<td> 61.0</td>
   	<td> 81.6</td>
    	<td> 87.3</td>
    	<td> 72.1</td>
    </tr>
    <tr>
    	<td> RGBD1K</td>
    	<td>AAAI'2023</td>
	<td></td>
    	<td> 65.4</td>
    	<td> 72.6</td>
    	<td> 68.8</td>
   	<td> 52.7</td>
    	<td> 54.9</td>
    	<td> 53.8</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> HMAD</td>
    	<td>ACMMMA'2023</td>
	<td>50.0</td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 62.6</td>
    	<td> 59.7</td>
    	<td> 61.1</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> DMTracker</td>
    	<td>ECCVW'2022</td>
	<td></td>
    	<td> 66.2</td>
    	<td> 65.8</td>
    	<td> 66.0</td>
   	<td> 61.9</td>
    	<td> 59.7</td>
    	<td> 60.8</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> DeT</td>
    	<td>ICCV'2021</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 56.0</td>
    	<td> 50.6</td>
    	<td> 53.2</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> TSDM</td>
    	<td>ICPR'2021</td>
	<td></td>
    	<td> 53.5</td>
    	<td> </td>
    	<td> </td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
	

<table>
    <tr> 
        <th colspan="1"></th> 
        <th colspan="1"></th> 
	<th colspan="1"></th> 
        <th colspan="3">RGBD1K</th> 
        <th colspan="3">D2CUBE</th> 
	<th colspan="3">ARKittrack</th>
    </tr>
    <tr>
    	<td> Methods</td>
    	<td>Venue</td>
	<td>Speed</td>
    	<td> Pr</td>
    	<td> Re</td>
    	<td> F-score</td>
   	<td> Pr</td>
    	<td> Re</td>
    	<td> F-score</td>
	<td> Pr</td>
    	<td> Re</td>
    	<td> F-score</td>
    </tr>
    <tr>
    	<td> CDAAT</td>
    	<td>SPL'2024</td>
	<td>59.5</td>
	<td> 54.9</td>
    	<td> 58.3</td>
    	<td> </td>
    	<td> </td>
   	<td> </td>
    	<td> </td>
	<td> </td>
   	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> SSLTrack</td>
    	<td>PR'2024</td>
	<td></td>
	<td>57.0</td>
    	<td> 47.8</td>
    	<td> 52.0</td>
    	<td> </td>
   	<td> </td>
    	<td> </td>
	<td> </td>
   	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> EMT</td>
    	<td>CVPR'2023</td>
	<td>120.3</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 65.3</td>
   	<td> 60.9</td>
    	<td> 63.0</td>
	<td> </td>
   	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> RGBD1K</td>
    	<td>AAAI'2023</td>
	<td></td>
    	<td> 54.5</td>
    	<td> 57.8</td>
    	<td> 56.1</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> HMAD</td>
    	<td>ACMMMA'2023</td>
	<td>50.0</td>
    	<td> 57.3</td>
    	<td> 55.2</td>
    	<td> 56.2</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
</table>

<table>
    <tr> 
        <th colspan="1"></th> 
	<th colspan="1"></th> 
	<th colspan="1"></th> 
        <th colspan="2">STC</th> 
        <th colspan="11">PTB</th> 
    </tr>
    <tr>
    	<td> Methods</td>
    	<td>Venue</td>
	<td>Speed</td>
    	<td> PR</td>
    	<td> SR</td>
    	<td> Human</td>
    	<td> Animal</td>
    	<td> Rigid</td>
    	<td> Large</td>
    	<td> Small</td>
    	<td> Slow</td>
    	<td> Faast</td>
    	<td> Occ.</td>
    	<td> No-Occ.</td>
    	<td> Passive</td>
    	<td> Active</td>
    </tr>
    <tr>
    	<td> SSLTrack</td>
    	<td>PR'2024</td>
	<td></td>
    	<td> </td>
    	<td> 64.0</td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td></td>
    	<td> </td>
    	<td> </td>
    </tr>

-----
## Contributors
- [Zhangyong Tang](https://github.com/Zhangyong_Tang)
- [PRCI-Lab](https://github.com/PRCI-Lab)

**Questions**

If you have any questions, please contact zhangyong_tang_jnu@163.com, and wechat: Tzy18861871359 is also welcomed.



 
