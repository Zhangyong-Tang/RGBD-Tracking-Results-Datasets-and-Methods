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

🫵Find our survey work at another [repo](https://github.com/Zhangyong-Tang/Survey-for-MultiModal-Visual-Object-Tracking)

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
| BoBoT | - | [BoBoT](http://www.iai.uni-bonn.de/~kleind/tracking/index.htm ) |BoBot - Bonn benchmark on tracking|
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
   	<td> A</td>
    	<td> R</td>
    	<td> EAO</td>
    </tr>
    <tr>
    	<td> 3DPT</td>
    	<td>ACCV'2024</td>
	<td></td>
    	<td>71.4</td>
    	<td>73.6</td>
    	<td>72.5</td>
   	<td>61.9</td>
    	<td>61.6</td>
    	<td>61.7</td>
   	<td> 82.2</td>
    	<td> 88.3</td>
    	<td>73.3</td>
    </tr>
    <tr>
    	<td> EMTrack</td>
    	<td>TCSVT'2024</td>
	<td>29.1/CPU</td>
    	<td></td>
    	<td></td>
    	<td></td>
   	<td>58.0</td>
    	<td>58.5</td>
    	<td>58.3</td>
   	<td> 80.6</td>
    	<td> 84.4</td>
    	<td>69.7</td>
    </tr>
    <tr>
    	<td> UBPT</td>
    	<td>IEEE Sensor Journal'2024</td>
	<td></td>
    	<td></td>
    	<td></td>
    	<td></td>
   	<td>61.5</td>
    	<td>62.0</td>
    	<td>61.7</td>
   	<td> 82.0</td>
    	<td> 87.1</td>
    	<td>72.1</td>
    </tr>
    <tr>
    	<td> DepthRefiner</td>
    	<td>ICME'2024</td>
	<td>32/A100</td>
    	<td>66.9</td>
    	<td>68.4</td>
    	<td>67.7</td>
   	<td>51.3</td>
    	<td>50.7</td>
    	<td>51.0</td>
   	<td> 79.7</td>
    	<td> 73.3</td>
    	<td>60.3</td>
    </tr>
    <tr>
    	<td> TABBTrack</td>
    	<td>PR'2024</td>
	<td>27/RTX3090</td>
    	<td>72.1</td>
    	<td>72.2</td>
    	<td>72.1</td>
   	<td>62.2</td>
    	<td>61.5</td>
    	<td>61.8</td>
   	<td> 82.1</td>
    	<td> 87.4</td>
    	<td>72.2</td>
    </tr>
    <tr>
    	<td> AMATrack</td>
    	<td>TIM'2024</td>
	<td>73/RTX3070</td>
    	<td>73.2</td>
    	<td>78.6</td>
    	<td>75.8</td>
   	<td>62.9</td>
    	<td>60.7</td>
    	<td>61.8</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> MixRGBX</td>
    	<td>Neurocomputing'2024</td>
	<td></td>
    	<td>72.8</td>
    	<td>81.6</td>
    	<td>76.9</td>
   	<td>59.3</td>
    	<td>60.9</td>
    	<td>60.1</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> OneTrack</td>
    	<td>CVPR'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 60.7</td>
    	<td> 60.4</td>
    	<td> 60.9</td>
   	<td> 87.2</td>
    	<td> 81.9</td>
    	<td> 72.7</td>
    </tr>
    <tr>
    	<td> UnTrack</td>
    	<td>CVPR'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 61.3</td>
    	<td> 61.0</td>
    	<td> 61.2</td>
   	<td> 87.1</td>
    	<td> 81.5</td>
    	<td> 72.1</td>
    </tr>
    <tr>
    	<td> SDSTrack</td>
    	<td>CVPR'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 61.9</td>
    	<td> 60.9</td>
    	<td> 61.4</td>
   	<td> 88.3</td>
    	<td> 81.2</td>
    	<td> 72.8</td>
    </tr>
    <tr>
    	<td> XTrack</td>
    	<td>Arxiv'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 59.8</td>
    	<td> 59.7</td>
    	<td> 59.7</td>
   	<td> 86.5</td>
    	<td> 81.2</td>
    	<td> 71.4</td>
    </tr>
    <tr>
    	<td> Seqtrackv2</td>
    	<td>Arxiv'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 62.9</td>
    	<td> 63.4</td>
    	<td> 63.2</td>
   	<td> 81.9</td>
    	<td> 91.8</td>
    	<td> 75.5</td>
    </tr>
    <tr>
    	<td> MINet</td>
    	<td>IVC'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 60.3</td>
    	<td> 60.5</td>
    	<td> 60.4</td>
   	<td> 81.6</td>
    	<td> 87.7</td>
    	<td> 72.3</td>
    </tr>
    <tr>
    	<td> KSTrack</td>
    	<td>TCSVT'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 60.0</td>
    	<td> 57.4</td>
    	<td> 58.7</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
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
    	<td> ViPT</td>
    	<td>CVPR'2023</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 59.2</td>
    	<td> 59.6</td>
    	<td> 59.4</td>
   	<td> 87.1</td>
    	<td> 81.5</td>
    	<td> 72.1</td>
    </tr>
    <tr>
    	<td> FDAFT</td>
    	<td>PRCV'2023</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 62.5</td>
    	<td> 61.5</td>
    	<td> 62.0</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> SPT</td>
    	<td>AAAI'2023</td>
	<td>25.3</td>
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
    	<td> ProTrack</td>
    	<td>ACMMM'2022</td>
	<td> </td>
    	<td> 74.7</td>
    	<td> 76.7</td>
    	<td> 65.6</td>
   	<td> 58.3</td>
    	<td> 57.3</td>
    	<td> 57.8</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> DeT</td>
    	<td>ICCV'2021</td>
	<td></td>
    	<td> 67.4</td>
    	<td> 64.2</td>
    	<td> 65.7</td>
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
    <tr>
    	<td> SiamOC</td>
    	<td>ICSP'2021</td>
	<td></td>
    	<td> 41.1</td>
    	<td> 34.6</td>
    	<td> 37.6</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> DAL</td>
    	<td>ICPR'2021</td>
	<td>20</td>
    	<td> </td>
    	<td> </td>
    	<td> 61.8</td>
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
    	<td> DepthRefiner</td>
    	<td>ICME'2024</td>
	<td>32/A100</td>
	<td>50.0</td>
    	<td> 52.9</td>
    	<td> 51.6</td>
    	<td> </td>
   	<td> </td>
    	<td> </td>
	<td>51.0</td>
   	<td>47.8</td>
    	<td>49.3</td>
    </tr>
    <tr>
    	<td> TABBTrack</td>
    	<td>PR'2024</td>
	<td>27/RTX3090</td>
	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> </td>
    	<td> </td>
	<td>51.0</td>
   	<td>47.8</td>
    	<td>49.3</td>
    </tr>
    <tr>
    	<td> CDAAT</td>
    	<td>SPL'2024</td>
	<td>59.5</td>
	<td> 54.9</td>
    	<td> 58.3</td>
    	<td> 56.6</td>
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
	<td>25.3</td>
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
<!--     <tr>
    	<td> DMTracker</td>
    	<td>ECCVW'2022</td>
	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 66.9</td>
    	<td> 64.4</td>
    	<td> 65.6</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr> -->
    <tr>
    	<td> DeT</td>
    	<td>ICCV'2021</td>
	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 60.8</td>
    	<td> 58.7</td>
    	<td> 59.7</td>
   	<td> 42.8</td>
    	<td> 40.5</td>
    	<td> 41.6</td>
    </tr>
    <tr>
    	<td> DAL</td>
    	<td>ICPR'2021</td>
	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 52.9</td>
    	<td> 56.5</td>
    	<td> 54.7</td>
   	<td> 44.6</td>
    	<td> 32.9</td>
    	<td> 37.8</td>
    </tr>
    <tr>
    	<td> TSDM</td>
    	<td>ICPR'2021</td>
	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 52.1</td>
    	<td> 49.2</td>
    	<td> 50.6</td>
   	<td> 38.9</td>
    	<td> 29.2</td>
    	<td> 33.4</td>
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
    	<td> Fast</td>
    	<td> Occ.</td>
    	<td> No-Occ.</td>
    	<td> Passive</td>
    	<td> Active</td>
    </tr>
    <tr>
    	<td> KSTrack</td>
    	<td>TCSVT'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 77.3</td>
    	<td> 84.9</td>
    	<td> 83.6</td>
    	<td> 79.8</td>
    	<td> 83.3</td>
    	<td> 82.6</td>
    	<td> 81.3</td>
    	<td> 73.4</td>
    	<td> 96.8</td>
    	<td> 80.3</td>
    	<td> 82.2</td>
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
    <tr>
    	<td> FECD</td>
    	<td>PRL'2024</td>
	<td></td>
    	<td> </td>
    	<td> 63.0</td>
    	<td> 65.0</td>
    	<td> 85.0</td>
    	<td> 88.0</td>
    	<td> 75.0</td>
    	<td> 80.0</td>
    	<td> 88.0</td>
    	<td> 73.0</td>
    	<td> 65.0</td>
    	<td> 94.0</td>
    	<td> 89.0</td>
    	<td> 73.0</td>
    </tr>
	    <tr>
    	<td> RGBD1K</td>
    	<td>AAAI'2023</td>
	<td>25.3</td>
    	<td> </td>
    	<td> 67.0</td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
	    <tr>
    	<td> DMTracker</td>
    	<td>ECCVW'2022</td>
	<td></td>
    	<td> </td>
    	<td> 63.0</td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> TSDM</td>
    	<td>ICPR'2021</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 71.0</td>
    	<td> 85.0</td>
    	<td> 86.0</td>
    	<td> 77.0</td>
    	<td> 81.0</td>
    	<td> 87.0</td>
    	<td> 76.0</td>
    	<td> 69.0</td>
    	<td> 94.0</td>
    	<td> 84.0</td>
    	<td> 78.0</td>
    </tr>
    <tr>
    	<td> 3s-RGBD</td>
    	<td>Neurocomputing'2021</td>
	<td> </td>
    	<td> 59.0</td>
    	<td> 49.0</td>
    	<td> 77.0</td>
    	<td> 68.0</td>
    	<td> 81.0</td>
    	<td> 76.0</td>
    	<td> 77.0</td>
    	<td> 81.0</td>
    	<td> 75.0</td>
    	<td> 71.0</td>
    	<td> 85.0</td>
    	<td> 85.0</td>
    	<td> 74.0</td>
    </tr>
    <tr>
    	<td> DAL</td>
    	<td>ICPR'2021</td>
	<td>20</td>
    	<td> 85.0</td>
    	<td> 64.0</td>
    	<td> 78.0</td>
    	<td> 86.0</td>
    	<td> 81.0</td>
    	<td> 76.0</td>
    	<td> 84.0</td>
    	<td> 83.0</td>
    	<td> 80.0</td>
    	<td> 72.0</td>
    	<td> 93.0</td>
    	<td> 78.0</td>
    	<td> 82.0</td>
    </tr>
    <tr>
    	<td> WCO</td>
    	<td>IEEE Sensors Journal'2020</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 78.0</td>
    	<td> 67.0</td>
    	<td> 80.0</td>
    	<td> 76.0</td>
    	<td> 75.0</td>
    	<td> 78.0</td>
    	<td> 73.0</td>
    	<td> 66.0</td>
    	<td> 86.0</td>
    	<td> 85.0</td>
    	<td> 72.0</td>
    </tr>
    <tr>
    	<td> RF-CFF</td>
    	<td>Applied Soft Computing Journal'2020</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 62.0</td>
    	<td> 79.0</td>
    	<td> 78.0</td>
    	<td> 69.0</td>
    	<td> 73.0</td>
    	<td> 81.0</td>
    	<td> 68.0</td>
    	<td> 57.0</td>
    	<td> 91.0</td>
    	<td> 80.0</td>
    	<td> 68.0</td>
    </tr>
    <tr>
    	<td> CF-RGBD</td>
    	<td>Engineering Applications of Artificial Intelligence'2020</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 61.0</td>
    	<td> 75.0</td>
    	<td> 80.0</td>
    	<td> 71.0</td>
    	<td> 71.0</td>
    	<td> 79.0</td>
    	<td> 68.0</td>
    	<td> 56.0</td>
    	<td> 91.0</td>
    	<td> 80.0</td>
    	<td> 67.0</td>
    </tr>
    <tr>
    	<td> CA3DMS</td>
    	<td>TMM'2019</td>
	<td>63</td>
    	<td> </td>
    	<td> </td>
    	<td> 64.0</td>
    	<td> 73.0</td>
    	<td> 81.0</td>
    	<td> 73.0</td>
    	<td> 72.0</td>
    	<td> 80.0</td>
    	<td> 69.0</td>
    	<td> 61.0</td>
    	<td> 88.0</td>
    	<td> 83.0</td>
    	<td> 68.0</td>
    </tr>
    <tr>
    	<td> Depth-CCF</td>
    	<td>GSKI'2019</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 70.0</td>
    	<td> 65.0</td>
    	<td> 79.0</td>
    	<td> 71.0</td>
    	<td> 73.0</td>
    	<td> 78.0</td>
    	<td> 70.0</td>
    	<td> 64.0</td>
    	<td> 84.0</td>
    	<td> 84.0</td>
    	<td> 67.0</td>
    </tr>
    <tr>
    	<td> H-FCN</td>
    	<td>INFFUS'2019</td>
	<td>19.47</td>
    	<td> </td>
    	<td> </td>
    	<td> 81.0</td>
    	<td> 74.0</td>
    	<td> 80.0</td>
    	<td> 82.0</td>
    	<td> 77.0</td>
    	<td> 78.0</td>
    	<td> 74.0</td>
    	<td> 83.0</td>
    	<td> 87.0</td>
    	<td> 80.0</td>
    	<td> 78.0</td>
    </tr>
    <tr>
    	<td> OTR</td>
    	<td>CVPR'2019</td>
	<td></td>
    	<td> 59.0</td>
    	<td> 49.0</td>
    	<td> 77.0</td>
    	<td> 68.0</td>
    	<td> 81.0</td>
    	<td> 76.0</td>
    	<td> 77.0</td>
    	<td> 81.0</td>
    	<td> 75.0</td>
    	<td> 71.0</td>
    	<td> 85.0</td>
    	<td> 85.0</td>
    	<td> 74.0</td>
    </tr>
    <tr>
    	<td> RGBD-OD</td>
    	<td>CIS'2019</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 72.0</td>
    	<td> 71.0</td>
    	<td> 73.0</td>
    	<td> 74.0</td>
    	<td> 71.0</td>
    	<td> 76.0</td>
    	<td> 70.0</td>
    	<td> 65.0</td>
    	<td> 82.0</td>
    	<td> 77.0</td>
    	<td> 70.0</td>
    </tr>
    <tr>
    	<td> HST</td>
    	<td>CCIFER'2019</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 66.0</td>
    	<td> 62.0</td>
    	<td> 77.0</td>
    	<td> 69.0</td>
    	<td> 69.0</td>
    	<td> 74.0</td>
    	<td> 68.0</td>
    	<td> 62.0</td>
    	<td> 79.0</td>
    	<td> 78.0</td>
    	<td> 66.0</td>
    </tr>
    <tr>
    	<td> ECO_TA</td>
    	<td>IEEE Sensors Journal'2019</td>
	<td>13.1</td>
    	<td> </td>
    	<td> </td>
    	<td> 77.0</td>
    	<td> 65.0</td>
    	<td> 79.0</td>
    	<td> 77.0</td>
    	<td> 74.0</td>
    	<td> 79.0</td>
    	<td> 74.0</td>
    	<td> 68.0</td>
    	<td> 85.0</td>
    	<td> 84.0</td>
    	<td> 72.0</td>
    </tr>
    <tr>
    	<td> GFL</td>
    	<td>Complexity'2019</td>
	<td>20.74</td>
    	<td> </td>
    	<td> </td>
    	<td> 82.0</td>
    	<td> 75.0</td>
    	<td> 78.0</td>
    	<td> 81.0</td>
    	<td> 74.0</td>
    	<td> 82.0</td>
    	<td> 73.0</td>
    	<td> 81.0</td>
    	<td> 84.0</td>
    	<td> 79.0</td>
    	<td> 68.0</td>
    </tr>
    <tr>
    	<td> DM-DCF</td>
    	<td>ICPR'2018</td>
	<td>8.3</td>
    	<td> </td>
    	<td> </td>
    	<td> 76.0</td>
    	<td> 58.0</td>
    	<td> 77.0</td>
    	<td> 72.0</td>
    	<td> 73.0</td>
    	<td> 75.0</td>
    	<td> 72.0</td>
    	<td> 69.0</td>
    	<td> 78.0</td>
    	<td> 82.0</td>
    	<td> 69.0</td>
    </tr>
    <tr>
    	<td> CSRDCF_RGBD++</td>
    	<td>ECCVW'2018</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 77.0</td>
    	<td> 65.0</td>
    	<td> 76.0</td>
    	<td> 75.0</td>
    	<td> 73.0</td>
    	<td> 80.0</td>
    	<td> 72.0</td>
    	<td> 70.0</td>
    	<td> 79.0</td>
    	<td> 79.0</td>
    	<td> 72.0</td>
    </tr>
    <tr>
    	<td> MMDFF</td>
    	<td>Complexity'2018</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 83.0</td>
    	<td> 86.0</td>
    	<td> 85.0</td>
    	<td> 85.0</td>
    	<td> 86.0</td>
    	<td> 82.0</td>
    	<td> 83.0</td>
    	<td> 87.0</td>
    	<td> 87.0</td>
    	<td> 82.0</td>
    	<td> 83.0</td>
    </tr>
    <tr>
    	<td> OAPCF</td>
    	<td>IEEE Access'2018</td>
	<td>17</td>
    	<td> </td>
    	<td> </td>
    	<td> 70.0</td>
    	<td> 66.0</td>
    	<td> 68.0</td>
    	<td> 69.0</td>
    	<td> 70.0</td>
    	<td> 75.0</td>
    	<td> 67.0</td>
    	<td> 73.0</td>
    	<td> 76.0</td>
    	<td> 71.0</td>
    	<td> 69.0</td>
    </tr>
   <tr>
    	<td> KCFDF</td>
    	<td>ICONIP'2017</td>
	<td>10.49</td>
    	<td> </td>
    	<td> </td>
    	<td> 45.0</td>
    	<td> 72.0</td>
    	<td> 75.0</td>
    	<td> 55.0</td>
    	<td> 67.0</td>
    	<td> 73.0</td>
    	<td> 57.0</td>
    	<td> 43.0</td>
    	<td> 87.0</td>
    	<td> 69.0</td>
    	<td> 59.0</td>
    </tr>
   <tr>
    	<td> DBM</td>
    	<td>Sensors'2017</td>
	<td>0.1</td>
    	<td> </td>
    	<td> </td>
    	<td> 80.1</td>
    	<td> 72.9</td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> 82.3</td>
    	<td> 77.5</td>
    	<td> 81.2</td>
    	<td> 82.6</td>
    	<td> </td>
    	<td> </td>
    </tr>
   <tr>
    	<td> DLS</td>
    	<td>ICPR'2016</td>
	<td> </td>
    	<td> </td>
    	<td> </td>
    	<td> 77.0</td>
    	<td> 69.0</td>
    	<td> 73.0</td>
    	<td> 80.0</td>
    	<td> 70.0</td>
    	<td> 73.0</td>
    	<td> 74.0</td>
    	<td> 66.0</td>
    	<td> 85.0</td>
    	<td> 72.0</td>
    	<td> 75.0</td>
    </tr>
   <tr>
    	<td> OAPF</td>
    	<td>CVIU'2016</td>
	<td>0.9</td>
    	<td> </td>
    	<td> </td>
    	<td> 64.2</td>
    	<td> 84.8</td>
    	<td> 77.2</td>
    	<td> 72.7</td>
    	<td> 73.4</td>
    	<td> 85.1</td>
    	<td> 68.4</td>
    	<td> 64.4</td>
    	<td> 85.1</td>
    	<td> 77.7</td>
    	<td> 71.4</td>
    </tr>
   <tr>
    	<td> 3D-T</td>
    	<td>CVPR'2016</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 81.0</td>
    	<td> 64.0</td>
    	<td> 73.0</td>
    	<td> 80.0</td>
    	<td> 71.0</td>
    	<td> 75.0</td>
    	<td> 75.0</td>
    	<td> 73.0</td>
    	<td> 78.0</td>
    	<td> 79.0</td>
    	<td> 73.0</td>
    </tr>
   <tr>
    	<td> DOHR</td>
    	<td>FSKD'2016</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 45.0</td>
    	<td> 49.0</td>
    	<td> 42.0</td>
    	<td> 48.0</td>
    	<td> 42.0</td>
    	<td> 50.0</td>
    	<td> 43.0</td>
    	<td> 38.0</td>
    	<td> 54.0</td>
    	<td> 54.0</td>
    	<td> 41.0</td>
    </tr>
</table>

-----
## Contributors
- [Zhangyong Tang](https://github.com/Zhangyong_Tang)
- [PRCI-Lab](https://github.com/PRCI-Lab)

**Questions**

If you have any questions, please contact zhangyong_tang_jnu@163.com, and wechat: Tzy18861871359 is also welcomed.



 
