# Causal Fine-Tuning under Latent Confounded Shift

Example implementation of **Causal Fine-Tuning (CFT)** for the experiments in
our [ICML 2026 paper](https://proceedings.mlr.press/v306/yu26bx.html).

## Experiments

| Experiment | Notebooks |
| --- | --- |
| **1. Stop-word–label spurious correlations** (§6.1, Table 1) | [Amazon](experiment_1_stop_words/amazon.ipynb) · [Yelp](experiment_1_stop_words/yelp.ipynb) |
| **2. Data-source–label spurious correlations** (§6.2, Table 2), combining Amazon and Yelp | [Amazon + Yelp](experiment_2_data_source/amazon_yelp.ipynb) |

Each experiment notebook includes data preparation, baselines, CFT, and component
ablations. [visual/visualisation.ipynb](visual/visualisation.ipynb) contains plots from saved result arrays.

## Requirements

Use Python 3.11 with **Transformers 4.42.0** and **Evaluate 0.4.2**.

## Citation

```bibtex
@InProceedings{pmlr-v306-yu26bx,
  title={Causal Fine-Tuning under Latent Confounded Shift},
  author={Yu, Jialin and Zhou, Yuxiang and Li, Haoxuan and Yu, Junchi and Yang, Mengyue and He, Yulan and Zhang, Nevin L. and Torr, Philip and Silva, Ricardo},
  booktitle={Proceedings of the 43rd International Conference on Machine Learning},
  pages={151776--151797},
  year={2026},
  volume={306},
  series={Proceedings of Machine Learning Research},
  publisher={PMLR},
  url={https://proceedings.mlr.press/v306/yu26bx.html}
}
```

## License

[MIT](LICENSE).
