# AlphaGenome_tutorial

## 配置环境

本教程使用 `uv` 配置环境

### 初始化项目

```bash
uv init AlphaGenome_tutorial
```

### 安装依赖

```bash
uv add git+https://github.com/google-deepmind/alphagenome
```

## 使用示例

```bash
uv run python main.py
```

运行上述命令会在 `data` 目录下生成一个 `rna_seq_variant_plot.png` 文件,
是 AlphaGenome 通过 Variant 预测 RNA-Seq 的结果.

## 参考文档

- [AlphaGenome GitHub](https://github.com/google-deepmind/alphagenome)
- [AlphaGenome API 文档](https://www.alphagenomedocs.com/index.html)
