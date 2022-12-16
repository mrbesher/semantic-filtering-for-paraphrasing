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

The folder `datasets` contains the file `human_annotations.csv`, which includes the human annotations for a sample of pairs from the OpenSubtitles2018, Tatoeba, and TED2013 datasets. The `src` column contains the source text for each pair, the `tgt` column contains the target text, and the `dataset` column indicates which dataset the pair is from. The `human` column indicates the overall label for the pair, based on the annotators' scores and agreement. If the annotators disagreed and the score difference was less than two, the label indicating less semantic similarity was chosen and recorded in the `human` column. If the label was discarded due to disagreement or any other reason, a value of -1 is recorded in the `human` column. The `annotator_1` and `annotator_2` columns contain the scores given by the two annotators for each pair.

## Model Checkpoints
You can access the finetuned model checkpoints from the links below:

- [mT5-base (OST)](https://huggingface.co/hyunussarioglu/paraphrase-mt5-base-ost): [mT5-base](https://huggingface.co/google/mt5-base) finetuned on the filtered OpenSubtitles2018 dataset.
- [mT5-base (TAT)](https://huggingface.co/hyunussarioglu/paraphrase-mt5-base-tat): [mT5-base](https://huggingface.co/google/mt5-base) finetuned on the filtered Tatoeba dataset.
- [trBART (OST)](https://huggingface.co/hyunussarioglu/tr-paraphrase-bart-ost): [trBART](https://huggingface.co/mukayese/transformer-turkish-summarization) finetuned on the filtered OpenSubtitles2018 dataset.
- [trBART (TAT)](https://huggingface.co/hyunussarioglu/tr-paraphrase-bart-tat): [trBART](https://huggingface.co/hyunussarioglu/tr-paraphrase-bart-tat) finetuned on the filtered Tatoeba dataset.

## Codes
__Will be added later.__
