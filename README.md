# Temporal-3D-Fully-Convolutional-Network-for-Water-Hazard-Detection
## DICTA 2019  

Juntao Li^1  
College of Engineering and Computer Science, The Australian National University  

Chuong Nguyen^2, Shaodi You  
DATA61 - Cyber Physical Systems, CSIRO, Canberra, Australia  


The reporsitory is still under construction :)

### Water Puddle Detection
![Detection example](Screenshot.jpg)
The figure shows one example of water detection where red areas are water areas.

### Network Structure
![Nerwork structure](network-structure.jpg)
The figure shows the network structure of our paper, our proposed network introduces temporal dimensions into FCN using 3D convolutional neural network which gives compariable results as [1] while reduce the time and space consumption significantly.

### Result Comparison
POOLING COMPARISON ON ON-ROAD DATASET  

|Pool          |F1-measure|Precision|Recall   |Time(sec/frame)|
|--------------|----------|---------|---------|---------------|
|Average(ours) |0.648     |0.774    |0.578    |0.23103        |
|Max(ours)     |0.680     |0.710    |**0.662**|0.23001        |
|**Last(ours)**|**0.684** |**0.788**|0.616    |**0.22975**    |

PERFORMANCE COMPARISON ON ON-ROAD DATASET  

|Method                |F1-measure|Precision|Recall  |Time(sec/frame)|
|----------------------|----------|---------|--------|---------------|
|**T3D-FCN-LAST(ours)**|0.68      |**0.79** |0.62    |0.23           |
|2D-FCN (ours)         |0.51      |0.51     |0.49    |**0.20**       |
|FCN-8s-FL-RAU[8]      |**0.70**  |0.68     |**0.72**|0.32           |
|FCN-8s[14]            |0.57      |0.59     |0.55    |0.06           |
|DeepLab[4]            |0.22      |0.37     |0.16    |0.06           |
|GMM & polar[15]       |0.31      |0.19     |0.90    |NA             |

### DICTA 2019 PAPER
![Temporal-3D-Fully-Convolutional-Network-for-Water-Hazard-Detection](DICTA2019_Temporal_3D_fully_convolutional_network_for_water_hazard_detection.pdf)

### Reference


