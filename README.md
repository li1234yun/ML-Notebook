# 机器学习

## 环境初始化

### Pytorch

- poetry 使用私有 url 进行安装
  - [解决方案](https://github.com/python-poetry/poetry/issues/7685#issuecomment-1632693935)
  - [poetry 源配置](https://python-poetry.org/docs/repositories/#supplemental-package-sources)
- 安装步骤

  ```shell
  poetry source add --priority=explicit https://download.pytorch.org/whl/cpu
  poetry source add --priority=explicit pytorch-cpu https://download.pytorch.org/whl/cpu
  ```

## 学习笔记

### Machine Learning With PyTorch and Scikit-Learn

- [Machine Learning With PyTorch and Scikit-Learn](notebook/Machine%20Learning%20With%20Pytorch%20and%20Scikit-Learn/README.md)
