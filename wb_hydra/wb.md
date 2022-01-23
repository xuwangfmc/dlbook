---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.12
    jupytext_version: 1.6.0
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Weights&Bias



Weights&Bias是一个机器学习平台，可以帮助开发人员分析和调整自己的模型。开发人员可通过使用Weight&Bias的轻量级工具、快速跟踪实验表现、迭代模型与数据集版本、评估模型的表现、调整模型的超参数以及与同事协作开发。



![uEtWSEb.png](https://s2.loli.net/2022/01/22/6DLuGHQEf21O3MZ.png)



**Artifacts**可用于数据集和模型版本控制，追踪模型训练的依赖及结果。Artifacts可以看作是各版本数据的文件夹。用户可以将整个数据集直接存储到Artifact当中，也可能使Artifact指向S3，GCP或者用户自己的系统进行存储。

**Sweeps**能够帮助搜索超参数空间以找到性能最好的模型参数参数配置。超参数扫描提供了一种有效的方式来选择表现最好的模型。具体是通过自动搜索超参数值的组合(如学习率、批量大小、隐藏层数、优化器类型)来实现此目的。

**Tables**不仅可以记录、查询和分析表格数据，还可以记录数据模型预测的可视化结果。


:::{admonition} Work in progress
Article building functionality for Jupyter Book is still under design and development.
This functionality may change over time!
If you have ideas, suggestions, or would like to help out, please [see the contributing guide](../contribute/intro.md).
:::