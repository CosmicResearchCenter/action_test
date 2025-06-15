# GitHub Actions 测试 Demo

这是一个用于测试GitHub Actions的简单Python项目。

## 功能

- 简单的计算器模块，包含基本数学运算
- 完整的单元测试覆盖
- GitHub Actions自动化测试流程

## 本地运行

```bash
# 运行主程序
python calculator.py

# 运行测试
python -m pytest test_calculator.py -v

# 代码风格检查
flake8 .
```

## GitHub Actions

项目配置了自动化测试流程，会在以下情况触发：
- 推送到 main 或 develop 分支
- 创建 pull request 到 main 分支

测试矩阵包含 Python 3.8, 3.9, 3.10, 3.11 版本。
