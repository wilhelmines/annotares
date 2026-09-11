# Annotares: A Dataset for Extracting Logical Structures from German Statutory Texts

This repository contains the dataset for the following publication:

> Ronja Schwarz, Jannik Strötgen: [Annotares: A Dataset for Extracting Logical Structures from German Statutory Texts](https://arxiv.org/pdf/2608.03898)

Please cite this paper if you are using the dataset. For further question contact [Ronja Schwarz](mailto:mail@aesz.org).

## Purpose and Maintenance

The dataset is a prototype for a new task in the legal domain and part of the paper listed above. No further work on this dataset is planned.

## Dataset

This dataset is for the extraction of conditional information from german statutory texts. It consists of three different laws: the Baugesetzbuch (BauGB), the Bundesausbildungsförderungsgesetz (BAföG) und the Bundesdatenschutzgesetz (BDSG). The BDSG was annotated completely. The BauGB and the BAföG are sampled for 50 sentences each.

The annotation schema comprises three classes Tatbestand (legal condition), Rechtsfolge (legal consequence), and None.

Additional information can be found in the annotation guidelines available in the dataset sub-dir.

### Files

The provided files contain the templates and the intermediate steps as jsonl, and the preprocessed outputs in the conll format. A split into three different files with 80% for training, 10% for validation and 10% for testing for the BDSG is included aswell.

The preprocessing step is carried out by using stanza to add dependency and part-of-speech tags for each token.

## License

The work provided by this repository is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
