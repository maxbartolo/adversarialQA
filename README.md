# Adversarial QA

## Paper
[**Beat the AI: Investigating Adversarial Human Annotation for Reading Comprehension**](https://arxiv.org/abs/2002.00293)

## Dataset
Version 1.0 is available here: https://dl.fbaipublicfiles.com/adversarialQA/aqa_v1.0.zip.

## Leaderboard

If you want to have your model added to the leaderboard, please reach out to us.

Model | Reference | Overall (F1)
---|---|---
RoBERTa-Large | [Liu et al., 2019](https://arxiv.org/abs/1907.11692) | 64.4%
BERT-Large | [Devlin et al., 2018](https://arxiv.org/abs/1810.04805) | 62.7%
BiDAF | [Seo et al., 2016](https://arxiv.org/abs/1611.01603) | 28.5%

## Implementation

For training and evaluating BiDAF models, we use [AllenNLP](https://allennlp.org/).

For training and evaluating BERT and RoBERTa models, we use [Transformers](https://huggingface.co/transformers/).

We welcome researchers from various fields (linguistics, machine learning, cognitive science, psychology, etc.) to work on adversarialQA.
You can use the code to reproduce the results in our paper or even as a starting point for your research.

We use [SQuAD v1.1](https://arxiv.org/abs/1606.05250) as training data for the adversarial models used in the data collection process. We also combine this dataset with the datasets we collect for some of our experiments.


## Other References

We use the following resources in training our models used for adversarial human annotation and in our analysis:
- [SQuAD v1.1](https://arxiv.org/abs/1606.05250)
- [DROP](https://arxiv.org/abs/1903.00161)
- [Natural Questions](https://research.google/pubs/pub47761/)


## Citation
```
@article{bartolo2020beat,
  title={Beat the AI: Investigating Adversarial Human Annotations for Reading Comprehension},
  author={Bartolo, Max and Roberts, Alastair and Welbl, Johannes and Riedel, Sebastian and Stenetorp, Pontus},
  journal={arXiv preprint arXiv:2002.00293},
  year={2020}
}
```

## License
AdversarialQA is licensed under Creative Commons-Non Commercial 4.0. See the LICENSE file for details.
