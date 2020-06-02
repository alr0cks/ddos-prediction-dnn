## ddos-prediction-dnn
A simple Feed Forward Neural Network to detect DDOS Attack packets.

Might reuse this NeuralNet for deployment over live production server for realtime packet sniffing Project.

### About Dataset

The dataset used is ([https://www.unb.ca/cic/datasets/ids.html] Intrusion Detection Evolution Dataset (ISCX-IDS-2012)) for testing and training.
Dataset is cleaned and converted from .pcap to .csv.

The full research paper outlining the details of the dataset and its underlying principles:

Ali Shiravi, Hadi Shiravi, Mahbod Tavallaee, Ali A. Ghorbani, ([http://www.sciencedirect.com/science/article/pii/S0167404811001672] Toward developing a systematic approach to generate benchmark datasets for intrusion detection), Computers & Security, Volume 31, Issue 3, May 2012, Pages 357-374, ISSN 0167-4048, 10.1016/j.cose.2011.12.012.

### Libraies Used
```
Pandas
Numpy
Seaborn
Matplotlib
Keras
Scikit-Learn
```

### Architecture
![Architecture](/Images/Architecture.png?raw=true "Graph")

### Accuracy
![Accuracy](/Images/Accuracy.png?raw=true "Graph")

### Loss
![Loss](/Images/Loss.png?raw=true "Graph")

### Analysis
![Analysis](/Images/ConfusionMatrix.png?raw=true "Graph")
