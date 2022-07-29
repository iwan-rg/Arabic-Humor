# A Dataset for Detecting Humor in Arabic Text 
Humor detection is a complex and ambiguous task in natural language processing. This has made automatic humor detection challenging, particularly for languages with limited resources such as Arabic. In this paper, we attempt to solve this task by collecting and annotating Arabic humorous tweets (dialects) and text (Modern Standard Arabic -MSA) then performing automatic humor detection on the collected data. We experimented on the collected dataset by fine-tuning seven Arabic Pre-Trained language models which are: AraBERTv02, Arabertv02-twitter, QARIB, MarBERT, MARBERTv2, CAMeLBERT-DA, and CAMeLBERT-MIX to establish a baseline classification system. We concluded that CAMeLBERT-DA was the best-performing model and it achieved an F1-score and accuracy of 72.11%.

## File Specifications
- [humor.tsv](https://github.com/iwan-rg/) : File that contains tweets with two labels, "humor" and "non-humor"

## Citation
If you use this dataset please cite as:
```bibtex
@inproceedings{[Al-Khalifa et al., 2022],
  title={A Dataset for Detecting Humor in Arabic Text},
  author={Hend Al-Khalifa, Fetoun AlZahrani, Hala Qawara, Reema AlRowais, Sawsan Alowa  and Luluh AlDhubayi},
  booktitle={Submitted},
  year={2022}
}
```
## License

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg.
