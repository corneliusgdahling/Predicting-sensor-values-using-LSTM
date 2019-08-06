# Predicting sensor values using LSTM
## Used for paper: [Sensor Failure Identification in Industrial Big Data](https://ieeexplore.ieee.org/document/9467520)
&nbsp;
### Created for master thesis: [Anomaly Detection of Sensors in Unsupervised Long Time-Series Data](https://ntnuopen.ntnu.no/ntnu-xmlui/bitstream/handle/11250/2624514/no.ntnu%3ainspera%3a2548256.pdf?sequence=1&isAllowed=y)
\
&nbsp;


## Disclaimer
This is most likely not just plug and play. Your dataset will probably look much different and consequently the preprocessing will be different.
The dataset used with this code is private and not mine to make public, however I have tried to comment the code in such a way that the pre-processing steps make sense even though the data is not shown.

### Hierarchical clustering didn't really work
As mentioned this was part of a Master thesis, so I tried selecting sensors using both Hierarchical clustering and feature importance. Hierarchical clustering didn't really work, so just use feature importance, if you are trying to copy what I did.
