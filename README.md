## 数据集介绍
该数据集用于网络安全领域的命名实体识别任务。
- 实体类别：Malware, ThreatActor
- 标签列表：[B-Mal, I-Mal, B-Threat_Actor, I-Threat_Actor, B-Tool, I-Tool, O]
- 数据量：2399
- 数据格式：训练集、测试集和验证集的数据格式相同，数据分为两列，列与列之间用\t进行分隔。第一列为文本，第二列为标签，文本和标签都用空格进行分隔。


## 文件列表
```
├─ dataset
│  ├─ dev.txt      // 验证集
│  ├─ infer.txt    // 预测集
│  ├─ test.txt     // 测试集
│  ├─ train.txt    // 训练集
│  └─ vocab.txt    // 字典
├─ LICENSE
└─ README.md
```

## 备注
vocab.txt中预置了[PAD]、[CLS]、[SEP]、[MASK]、[UNK]这五个词


## 引用Citation
```
王 新凯 et al. (2022) TJGeminiLab/Threatintelligencesdodataset, GitHub. 北京天际友盟信息技术有限公司双子座实验室. Available at: https://github.com/TJGeminiLab/ThreatIntelligenceSDODataSet (Accessed: October 19, 2022). 
```

## LICENSE
Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License](./LICENSE).

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg