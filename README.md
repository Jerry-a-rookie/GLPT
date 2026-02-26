<img width="3006" height="2460" alt="image" src="https://github.com/user-attachments/assets/d0e7659f-ff30-4b6d-9360-2238a0ae2382" /># GLPT: "Global-Local Pyramid Transformer for Multivariate Time Series Forecasting."
Code of GLPT

## Key Designs
1.Global-Local Fusion: Integrate global temporal dependencies and local fine-grained patterns of multivariate time series to capture comprehensive temporal characteristics.

2.Pyramid Attention Mechanism: Adopt a pyramidal hierarchical structure to efficiently model long-range dependencies with low computational complexity, tailored for multivariate time series forecasting scenarios.

Structure of GLPT：
![Structure of GLPT](https://github.com/Jerry-a-rookie/GLPT/blob/main/Figure_1.png?raw=true)


Detail of PPI：
![Detail of PPI](https://github.com/Jerry-a-rookie/GLPT/blob/main/Figure_2.png?raw=true)


Results:
![Results](https://github.com/Jerry-a-rookie/GLPT/blob/main/leida.png?raw=true)

## Getting Started
1.Download data. Due to the large size of the datasets, you can download all the datasets from Autoformer. Create a separate folder ./dataset and put all the csv files in the directory.

2.Training. All the scripts are in the directory ./scripts/GLPT. The default model is GLPT. For example, if you want to get the multivariate forecasting results for weather dataset, just run the following command, and you can open ./result.txt to see the results.

## Acknowledgement
We appreciate the following github repo very much for the valuable code base and datasets:
https://github.com/thuml/Autoformer

https://github.com/cure-lab/LTSF-Linear

https://github.com/zhouhaoyi/Informer2020

https://github.com/MAZiqing/FEDformer

https://github.com/alipay/Pyraformer

https://github.com/ts-kim/RevIN

https://github.com/timeseriesAI/tsai

## Contact
If you have any question or want to use the code, please contact 2152761419@qq.com.

