# OLMo 3 Code 150M Pre-train

**Status: Graduated**

This experiment has graduated to its own repository:

**[Training-Datasmith/olmo3-code-150m-pretrain](https://github.com/Training-Datasmith/olmo3-code-150m-pretrain)**

## Summary

Pre-training a ~150M parameter code-specialized language model using the OLMo 3 architecture (GQA, SWA, SwiGLU, RoPE) on PHP/JS/Python/C source code from the Training-Datasmith organization's forked repositories.

## Graduation Notes

This notebook started as an experiment in kaggle-experiments and was promoted to its own repo after demonstrating consistent loss reduction across multiple training runs on Kaggle T4 x2 GPUs.
