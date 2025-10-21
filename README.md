# Datasets

![image](https://github.com/udmurtNLP/docs/blob/main/imgs/datasets.png?raw=true)

## Text datasets

### Parallel corpora

- Russian-Udmurt parallel corpora (100k sentences) [Hugging Face](https://huggingface.co/datasets/udmurtNLP/udmurt-russian-parallel-corpora)
- Tatoeba (>3600 sentence pairs). [Hugging Face](https://huggingface.co/datasets/udmurtNLP/tatoeba-rus-udm-parallel-corpora) / [Source](https://tatoeba.org/ru/downloads)
- Finugorbib (>30k sentence pairs). [Hugging Face](https://huggingface.co/datasets/udmurtNLP/udmurt-bible-parallel-corpora) / [slone/finugorbib](https://huggingface.co/datasets/slone/finugorbib)
- Soviet geography book (>2700 sentence pairs). [Hugging Face](https://huggingface.co/datasets/udmurtNLP/soviet-geography-book-rus-udm-parallel-corpora)
- FLORES-250, translation benchmark. [Hugging Face](https://huggingface.co/datasets/udmurtNLP/flores-250-rus-udm) / [Other languages](https://huggingface.co/datasets/tartuNLP/smugri-flores-testset)

### Monolingual corpora

- Udmurt news (udmddn.ru and oshmes.info, in total 36k sentences). [Hugging Face](https://huggingface.co/datasets/tartuNLP/smugri-data)
- Wikipedia dump (more than 43k sentences). [Download](https://dumps.wikimedia.org/udmwiki/)
- MADLAD-400 (651k sentences, 9.5 million words) [Hugging Face](https://huggingface.co/datasets/udmurtNLP/madlad-400-udmurt) / [All languages](https://huggingface.co/datasets/allenai/MADLAD-400)
- Glot500-c (121k sentences) [GitHub](https://github.com/cisnlp/Glot500)
- Zerpal (1.4M sentences) [Hugging Face](https://huggingface.co/datasets/udmurtNLP/zerpal)
- FineWeb2 (13.5 million words) [Hugging Face](https://huggingface.co/datasets/HuggingFaceFW/fineweb-2)
- FinePDFs (however, the quality of Udmurt language texts is really bad) [Hugging Face](https://huggingface.co/datasets/HuggingFaceFW/finepdfs)
- FineWiki (> 5k texts) [Hugging Face](https://huggingface.co/datasets/HuggingFaceFW/finewiki)

### Classification

- Finno-Ugric SIB (SIB-SMUGRI) [Hugging Face](https://huggingface.co/datasets/tartuNLP/sib-smugri)
- Zerpal-udmdunne (8,154 rows, 5 labels) [Hugging Face](https://huggingface.co/datasets/udmurtNLP/zerpal-udmdunne)
- Zerpal-udmurtmedia (15,274 rows, 10 labels) [Hugging Face](https://huggingface.co/datasets/udmurtNLP/zerpal-udmurtmedia)

### POS-tagging

- Zerpal-pos-tagging (12,392 rows, 17 classes) [Hugging Face](https://huggingface.co/datasets/udmurtNLP/zerpal-pos-tagging)

### NER

- WikiANN (the transcription is problematic: Latin and Cyrillic are used inconsistently, Wikipedia Markup is parsed incorrectly, but if you want to use it, see `wikiann` directory)

### Question Answering

- MultiWikiQA (5k rows) [Hugging Face](https://huggingface.co/datasets/alexandrainst/multi-wiki-qa)

### Instruction

- MURI-IT (2,751 rows) [Hugging Face](https://huggingface.co/datasets/akoksal/muri-it-language-split)

## Audio datasets

- Volga Fairytales TTS Dataset (0.23 hours) [Hugging Face](https://huggingface.co/datasets/yasalma/fairytales)