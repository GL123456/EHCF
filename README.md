# EHCF

This is our implementation of the paper:

*Chong Chen, Min Zhang, Weizhi Ma, Yongfeng Zhang, Yiqun Liu and Shaoping Ma. 2020. [Efﬁcient Heterogeneous Collaborative Filtering without Negative Sampling for Recommendation.](https://chenchongthu.github.io/files/AAAI_EHCF.pdf) 
In AAAI'20.*

**Please cite our AAAI'20 paper if you use our codes. Thanks!**

```
@inproceedings{chen2020efficient,
  title={Efﬁcient Heterogeneous Collaborative Filtering without Negative Sampling for Recommendation},
  author={Chen, Chong and Zhang, Min and Ma, Weizhi and Zhang, Yongfeng and Liu, Yiqun and Ma, Shaoping},
  booktitle={Thirty-Fourth AAAI Conference on Artificial Intelligence},
  year={2020},
}
```

Author: Chong Chen (cstchenc@163.com)

## Environments

- python
- Tensorflow
- numpy
- pandas

## Parameter settings

The parameters for Beibei datasets is:

self.weight = [0.1, 0.1, 0.1]

self.coefficient = [0.05, 0.8, 0.15]

The parameters for Taobao datasets is:

self.weight = [0.01, 0.01, 0.01]

self.coefficient = [3.0/6, 2.0/6, 1.0/6]



## Example to run the codes		

Train and evaluate the model:

```
python EHCF.py
```


First Update Date: Nov. 12, 2019
