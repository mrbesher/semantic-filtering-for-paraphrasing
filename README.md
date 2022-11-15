# Semantic Similarity Based Filtering for Turkish Paraphrase Dataset Creation
A repository of the codes and the datasets used in the paper "Semantic Similarity Based Filtering for Turkish Paraphrase Dataset Creation" (citation to be added when published).

The work in this paper was done by [Besher Alkurdi](https://github.com/mrbesher), [Hasan Yunus Sarioglu](https://github.com/hyunussarioglu) and [Mehmet Fatih Amasyali](https://github.com/mfatihamasyali).

## Datasets
You can access the filtered datasets that we used to train our models from the Hugging Face Hub at the links below:

- [OpenSubtitles2018](https://huggingface.co/datasets/mrbesher/tr-paraphrase-opensubtitles2018) (OST)
- [Tatoeba](https://huggingface.co/datasets/mrbesher/tr-paraphrase-tatoeba) (TAT)
- [TED2013](https://huggingface.co/datasets/mrbesher/tr-paraphrase-ted2013) (TED) __Not used for evaluation__

The raw (non-filtered versions) can be acessed from the links below:

- [OpenSubtitles2018 Raw](https://huggingface.co/datasets/mrbesher/tr-paraphrase-opensubtitles2018) (OST-RAW)
- [Tatoeba Raw](https://huggingface.co/datasets/mrbesher/tr-paraphrase-tatoeba-raw) (TAT-RAW)

## Model Checkpoints
You can access the finetuned model checkpoints from the links below:

- [mT5-base (OST)](https://huggingface.co/hyunussarioglu/paraphrase-mt5-base-ost): [mT5-base](https://huggingface.co/google/mt5-base) finetuned on the filtered OpenSubtitles2018 dataset.
- [mT5-base (TAT)](https://huggingface.co/hyunussarioglu/paraphrase-mt5-base-tat): [mT5-base](https://huggingface.co/google/mt5-base) finetuned on the filtered Tatoeba dataset.

## Codes
__Will be added later.__
