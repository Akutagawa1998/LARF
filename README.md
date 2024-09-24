# Difficult Task Yes but Simple Task No: Unveiling the Laziness in Multimodal LLMs - (EMNLP 2024 Findings)

[Sihang (Nagi) Zhao](https://akutagawa1998.github.io/)
               
### [Paper](our paper link) | [Project Page](our project page) | [LazyBench](our LazyBench)


![Teaser](imgs/teaser.png)


## Contents:
1. [Getting Started](#start)
2. [Benchmark](#benchmarks)
3. [Evaluation](#evaluation)
4. [License](#license)
5. [Citation](#citation)
6. [Acknowledgement](#acknowledgement)

## Getting Started <a name="start"></a>


### LazyBench
OurLazyBench is available [here](our hf page). It is specially crafted to measure **multimodal LLM's** laziness via VQA. 
The original version of LazyBench is separated into a folder containing 101 images. an annotation CSV file with questions and correct answers. The format of the data is:


```
├── lazy_images
│   ├── 1.jpg
│   ├── 2.jpg
│   ├── 3.jpg
│   ├── ...
│   └── 101.jpg (the original image amout in the paper is 101)
│   ├── ...
│   └── 210.jpg
└── lazy_labels.csv
└── lazy_labels_new.csv
```
We are continually expanding this LazyBench. The latest version of lazy_labels can be found in lazy_labels_new.csv.


## License <a name="license"></a>

This project is under the MIT license. See [LICENSE](LICENSE) for details.

## Citation <a name="citation"></a>
Please consider citing our paper if you find this project helpful for your research:
*Coming Soon*


## Acknowledgement <a name="acknowledgement"></a>
-  This work is built upon the [LLaVA](https://github.com/haotian-liu/LLaVA).
-  Many thanks to Xiaocui, the manti who came into my balcony and stayed with me during my experiments and paper writing.
