# Datasets

![image](https://i.ibb.co/PccTKNX/datasets.png)

## Text datasets

### Parallel corpora

- Tatoeba (>3600 sentence pairs). [HuggingFace](https://huggingface.co/datasets/udmurtNLP/tatoeba-rus-udm-parallel-corpora) / [Source](https://tatoeba.org/ru/downloads)
- Finugorbib (>30k sentence pairs). [HuggingFace](https://huggingface.co/datasets/udmurtNLP/udmurt-bible-parallel-corpora)
- Soviet geography book (>2700 sentence pairs). [HuggingFace](https://huggingface.co/datasets/udmurtNLP/soviet-geography-book-rus-udm-parallel-corpora)
- FLORES-250, translation benchmark. [HuggingFace](https://huggingface.co/datasets/udmurtNLP/flores-250-rus-udm) / [Other languages](https://huggingface.co/datasets/tartuNLP/smugri-flores-testset)

### Monolingual corpora

- Udmurt news (udmddn.ru and oshmes.info, in total 36k sentences). [HuggingFace](https://huggingface.co/datasets/tartuNLP/smugri-data)
- Wikipedia dump (more than 43k sentences). [Download](https://dumps.wikimedia.org/udmwiki/)
- MADLAD-400 (651k sentences, 9.5 million words) [HuggingFace](https://huggingface.co/datasets/udmurtNLP/madlad-400-udmurt) / [All languages](https://huggingface.co/datasets/allenai/MADLAD-400)
- Glot500-c (121k sentences) [GitHub](https://github.com/cisnlp/Glot500)

### NER

- WikiANN (the transcription is problematic: Latin and Cyrillic are used inconsistently, Wikipedia Markup is parsed incorrectly, but if you want to use it, see `wikiann` directory)