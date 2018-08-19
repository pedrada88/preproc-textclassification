## On the Role of Text Preprocessing in Neural Network Architectures: An Evaluation Study on Text Categorization and Sentiment Analysis
#### Jose Camacho Collados and Mohammad Taher Pilehvar

The following repository includes the pre-trained word embeddings and preprocessed text classification datasets for the paper *[On the Role of Text Preprocessing in Neural Network Architectures: An Evaluation Study on Text Categorization and Sentiment Analysis]()* .

### Pre-trained word embeddings

We release the 300-dimension word embeddings used in our experiments as binary *bin* files. The embeddings were trained on the UMBC corpus with the following preprocessing techniques:

- **Vanilla** (simple tokenization): Download [here](https://drive.google.com/file/d/1dBnoeLR20LjNy4hVjR2P5U923A1uqQbR/view?usp=sharing) [~1.8 GB]
- **Lowercased**: Download [here](https://drive.google.com/file/d/1vObC9pjcWiKpahziolHyTi5-lhiRw7xF/view?usp=sharing) [~1.6 GB]
- **Lemmatized**: Download [here](https://drive.google.com/file/d/1E-oVlug-Pu6LA7Ke6ZHHDMmL7wjz9P1l/view?usp=sharing) [~1.7 GB]
- **Multiword-grouped**: Download [here](https://drive.google.com/file/d/13fGiYIeXEpBQaNuKb3wRnfhCyxF02rDu/view?usp=sharing) [~2.1 GB]

### Preprocessed datasets

We also release the text categorization and sentiment analysis datasets already preprocessed.

- **Text categorization**: Available [here](https://drive.google.com/drive/folders/1xWc2-CP-e33ZQ9J9Meu0U1A4rAEvdRSC?usp=sharing)
- **Sentiment analysis**: Available [here](https://drive.google.com/drive/folders/1e7sez3iYJEQwmRwS7hl6ptfN8ULefNUq?usp=sharing)

Note 1: If you use any of these datasets, please acknowledge the original sources (you can find them in the reference paper).
Note 2: For each class file in the datasets each line corresponds to an instance in the corpus, be it a phrase, sentence or document depending on the dataset.


### Code

The code to reproduce our experiments is available in the following repository: https://github.com/pilehvar/sensecnn


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
