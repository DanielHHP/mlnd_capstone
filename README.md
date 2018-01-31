# Udacity机器学习（进阶）毕业项目

## 选择的项目

[自然语言处理-文档归类](https://github.com/nd009/capstone/tree/master/document_classification)

[数据获取](http://scikit-learn.org/stable/datasets/twenty_newsgroups.html)

## 参考链接

- [题目仓库](https://github.com/nd009/capstone)
- [论文格式](https://jingyan.baidu.com/article/a948d65166e7880a2dcd2ebd.html)
- [使用scikitlearn进行分类](http://scikit-learn.org/stable/auto_examples/text/document_classification_20newsgroups.html)
- [tensorflow word2vec](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/tutorials/word2vec/word2vec_basic.py)
- [Comparison of FastText and Word2Vec](http://nbviewer.jupyter.org/github/jayantj/gensim/blob/683720515165a332baed8a2a46b6711cefd2d739/docs/notebooks/Word2Vec_FastText_Comparison.ipynb)

开题

- [开题报告模板](https://github.com/nd009/capstone/blob/master/capstone_proposal_template.md)
- [开题报告评审标准-英文](https://review.udacity.com/#!/rubrics/410/view)
- [开题报告评审标准-中文](https://review.udacity.com/#!/rubrics/484/view)

开题报告主要包括以下7个主题部分：

- **项目背景**：项目涉及的相关研究领域
- **问题描述**：解决办法所针对的具体问题
- **输入数据**：问题中涉及的数据或输入是什么
- **解决办法**：针对给定问题的解决方案
- **基准模型**：用来与你的解决方案进行比较的一些简单的、过去的模型或者结果
- **评估指标**：衡量你解决方案的标准
- **设计大纲**：你的解决方案如何实现，如何获取结果

项目报告

- [项目评审标准](https://review.udacity.com/#!/rubrics/273/view)

项目报告参考

[新闻组文件分类（英文）](http://cn-static.udacity.com/mlnd/Capstone_Poject_Sample01.pdf)

[识别街景数字](https://github.com/nd009/capstone/blob/master/report-example-1.pdf)

[文档分类](https://github.com/nd009/capstone/blob/master/report-example-2.pdf)

[银行客户分类](https://github.com/nd009/capstone/blob/master/report-example-3.pdf)

## 环境安装

```shell
conda create -n mlnd_capstone python=3.6
activate mlnd_capstone
conda install pandas matplotlib jupyter notebook scipy scikit-learn

# for cpu
conda install tensorflow

# for gpu
conda install tensorflow-gpu

# use pip install to keep tensorflow package
pip install keras

conda install gensim nltk lime
```

```python
# nltk data download
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```