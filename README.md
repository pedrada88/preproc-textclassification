## On the Role of Text Preprocessing in Neural Network Architectures: An Evaluation Study on Text Categorization and Sentiment Analysis
#### Jose Camacho Collados and Mohammad Taher Pilehvar

The following repository includes the pre-trained word embeddings and preprocessed text classification datasets for the paper *[On the Role of Text Preprocessing in Neural Network Architectures: An Evaluation Study on Text Categorization and Sentiment Analysis]()* .

### Pre-trained word embeddings

We release the 300-dimension word embeddings used in our experiments, trained on UMBC with the following preprocessing techniques:

- **Vanilla** (simple tokenization): Download [here](https://drive.google.com/file/d/1dBnoeLR20LjNy4hVjR2P5U923A1uqQbR/view?usp=sharing) [~300 MB]
- **Lowercased**: Download [here](https://drive.google.com/file/d/1vObC9pjcWiKpahziolHyTi5-lhiRw7xF/view?usp=sharing) [~300 MB]
- **Lemmatized**: Download [here](https://drive.google.com/file/d/1E-oVlug-Pu6LA7Ke6ZHHDMmL7wjz9P1l/view?usp=sharing) [~300 MB]
- **Multiword-grouped**: Download [here](https://drive.google.com/file/d/13fGiYIeXEpBQaNuKb3wRnfhCyxF02rDu/view?usp=sharing) [~300 MB]

### Preprocessed datasets

We also release the text categorization and sentiment analysis datasets already preprocessed.

- **Text categorization**: Available [here]() [~300 MB]
- **Sentiment analysis**: Available [here]() [~300 MB]

Note: If you use any of these datasets, please acknowledge the original sources that you can find in our paper.

### Code

The code is available in the following repository: https://github.com/pilehvar/sensecnn


If you use any of these resources, please cite the following paper:
```bash
@InProceedings{camacho:preprocessing2018,
  author = 	"Camacho-Collados, Jose and Pilehvar, Mohammad Taher",
  title = 	"On the Role of Text Preprocessing in Neural Network Architectures: An Evaluation Study on Text Categorization and Sentiment Analysis",
  booktitle = 	"Proceedings of the EMNLP Workshop on Analyzing and interpreting neural networks for NLP",
  year = 	"2018",
  publisher = 	"Association for Computational Linguistics", and -
  location = 	"Brussels, Belgium",
}

```
