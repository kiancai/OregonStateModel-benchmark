# OregonStateModel-benchmark

本项目基于 Oregon State 的微生物组预训练语言模型进行修改和适配，用于与 MiCoFormer 进行 benchmark 对比实验。**本仓库不是原始项目的直接副本**，代码和流程已根据对比实验需求做了调整。

## 原始项目

**"Learning a deep language model for microbiomes: the power of large scale unlabeled microbiome data"**

- 架构：基于 ELECTRA（Generator + Discriminator）的微生物组预训练模型
- 预训练数据：American Gut Project (AGP) 无标签样本
- 下游任务：IBD 分类（AGP / Halfvarson / Schirmer-HMP2）
- GitHub: [QuintinPope/microbiome_transformers](https://github.com/QuintinPope/microbiome_transformers)
- Zenodo: [10.5281/zenodo.13858903](https://doi.org/10.5281/zenodo.13858903)
- 原始 README: [README_raw.md](README_raw.md)
