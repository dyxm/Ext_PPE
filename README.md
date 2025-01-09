# Ext_PPE: Personal Protective Equipment (PPE) Detection in Extreme Construction Conditions
[Paper](https://www.researchgate.net/publication/378755234_Personal_Protective_Equipment_Detection_in_Extreme_Construction_Conditions) | [Dataset](#dataset) | [Citation](#citation)

<p align="justify">
      Object detection has been widely applied for construction safety management, especially personal protective equipment (PPE) detection. Though the existing PPE detection models trained on conventional datasets have achieved excellent results, their performance dramatically declines in extreme construction conditions. A robust detection model NST-YOLOv5 is developed by combining the neural style transfer (NST) and YOLOv5 technologies. Five extreme conditions are considered and simulated via the NST module to endow the detection model with excellent robustness, including low light, intense light, sand dust, fog, and rain. Experiments show that the NST has great potential as a tool for extreme data synthesis since it is better at simulating extreme conditions than other traditional image processing algorithms and helps the NST-YOLOv5 achieve 0.141 and 0.083 mAP_(05:95) improvements in synthesized and real-world extreme data. This study provides a new feasible way to obtain a more robust detection model for extreme construction conditions.
</p>

**Keywords:** Construction safety management, Personal protective equipment (PPE) detection, Object detection, Extreme construction conditions, neural style transfer (NST), You only look once v5 (YOLOv5)

## Dataset
An extreme real-world construction image dataset for PPE detection, labeled with 3 objects: **Worker**, **Vest**, and **Helmet**.
![image](https://github.com/dyxm/Ext_PPE/assets/17799440/1d9d7235-c5f3-486b-a4ef-fddb20de2fb2)

The dataset can be accessed:
- at the [TeraBox](https://terabox.com/s/1aiSECQBLpDQtkKk69mwaqw).
- or, at the [Baidu Netdisk](https://pan.baidu.com/s/1LcDkWN_Rs4RKpbfJxISwag) using the code: **mulk**


## Citation
If you find the dataset useful, consider citing it using:
```
@inproceedings{ding_personal_2024,
      address = {Corvallis, Oregon},
      title = {Personal protective equipment detection in extreme construction conditions},
      isbn = {978-0-7844-8524-8},
      url = {https://ascelibrary.org/doi/10.1061/9780784485248.081},
      doi = {10.1061/9780784485248.081},
      language = {en},
      urldate = {2024-04-17},
      booktitle = {Computing in {Civil} {Engineering} 2023},
      publisher = {American Society of Civil Engineers},
      author = {Ding, Yuexiong and Luo, Xiaowei},
      month = jan,
      year = {2024},
      pages = {672--679},
}
```
