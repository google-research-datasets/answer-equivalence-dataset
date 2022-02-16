# Answer Equivalence Dataset

This dataset is introduced and described in [Tomayto, Tomahto. Beyond Token-level Answer Equivalence for Question Answering Evaluation](http://arxiv.org/abs/2202.07654).


## Download the data

| AE Split  | # AE Examples | # Ratings |
|-----------|---------------|-----------|
| [Train](https://github.com/google-research-datasets/answer-equivalence-dataset/blob/main/v1/train.jsonl) | 9,090 | 9,090 |
| [Dev](https://github.com/google-research-datasets/answer-equivalence-dataset/blob/main/v1/ae_dev.jsonl) | 2,734 | 4,446 |
| [Test](https://github.com/google-research-datasets/answer-equivalence-dataset/blob/main/v1/ae_test.jsonl) | 5,831 | 9,724 |
| Total  | 17,655 | 23,260 |


| Split by system  | # AE Examples | # Ratings |
|------------------|---------------|-----------|
| [BiDAF dev predictions](https://github.com/google-research-datasets/answer-equivalence-dataset/blob/main/v1/dev_by_system/dev_bidaf.jsonl) | 5622 | 7522 |
| [XLNet dev predictions](https://github.com/google-research-datasets/answer-equivalence-dataset/blob/main/v1/dev_by_system/dev_xlnet.jsonl) | 2448 | 7932 |
| [Luke dev predictions](https://github.com/google-research-datasets/answer-equivalence-dataset/blob/main/v1/dev_by_system/dev_luke.jsonl) | 2240 | 4590 |
| Total  | 8,565 | 14,170 |


## How to cite AE? 

```
@article{bulian-etal-2022-tomayto,
  author    = {Jannis Bulian and
		Christian Buck  and
		Wojciech Gajewski and
		Benjamin B{\"o}rschinger and
		Tal Schuster},
  title     = {Tomayto, Tomahto. Beyond Token-level Answer Equivalence 
               for Question Answering Evaluation},
  journal   = {CoRR},
  volume    = {abs/2202.07654},
  year      = {2022},
  ee        = {http://arxiv.org/abs/2202.07654},
}
```


## Disclaimer

This is not an official Google product.


## Contact information

For help or issues, please submit a GitHub issue or contact the authors by email.
