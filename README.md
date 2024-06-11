# Investigating-the-Arithmetic-of-Visual-Embeddings
This research delves into the influence of various visual pre-training paradigms, including self-supervised and language supervision, on the properties of image embeddings. Drawing inspiration from the well-established NLP example of semantic arithmetic (e.g., "King - Male + Woman = Queen"), we aim to assess how different pre-training methodologies affect the geometric properties of image embeddings. Given the inherent diversity across model architectures, it is anticipated that the resulting embeddings will exhibit distinct properties. Such an investigation is of paramount importance in multi-modal spaces where both textual and visual data are integrated, as it contributes to a deeper understanding of geometric relationships and facilitates vector-oriented reasoning. Through a comprehensive examination, this study endeavors to shed light on the intricate interplay between pre-training paradigms and image embedding properties, thus paving the way for enhanced multi-modal learning techniques.

Image Dataset : https://drive.google.com/drive/folders/1S5zIpY8Tqayh_ln810Xa1CQ0LJsEug2i?usp=drive_link

## Description of files:
| File      | Description |
| ----------- | ----------- |
| Analogy-pairs.txt      | list of word pairs used in our study       |
| analogy-pair-creation.py  | Python script used for pre-processing of analogy pairs         |
| dataset-creation.py | Python script for creation of the image dataset   |
| evaluate-arithmetic-properties.ipynb | Helper functions for evaluating arithmetic properties |
| experiments.ipynb | Contains the experiments performed using different models |
| image_downloader.ipynb | script used to download images for the dataset |


## Models used
1. CLIP: https://huggingface.co/sentence-transformers/clip-ViT-B-32
2. Word2Vec: https://huggingface.co/fse/word2vec-google-news-300
3. ResNet50: https://huggingface.co/microsoft/resnet-50
